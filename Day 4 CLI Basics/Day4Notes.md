# What I Learned

In this lab, I learned how to configure the basic settings on a router and switch using the CLI.

I learned how to change the hostname of a router and switch using the `hostname` command in global configuration mode. I changed the device names to **R1** and **SW1**.

I also learned how to configure an unencrypted password using `enable password`. I configured the password as **yahyak**, exited back to user EXEC mode, and then tested the password by returning to privileged EXEC mode.

After that, I used the `show running-config` command to view the password in the running configuration.

I then learned how to encrypt passwords using the `service password-encryption` command. This ensures that the current password, as well as future passwords, are encrypted. I used `show running-config` again to verify that the password was now encrypted.

Next, I configured a more secure encrypted enable password using the `enable secret` command and set the password to **Yahyak**.

After exiting back to user EXEC mode and returning to privileged EXEC mode, I learned that the **enable secret** password is the one that must be used. I also used `show running-config` to view the encrypted passwords and compare the different encryption types.

Finally, I learned how to save the running configuration to the startup configuration using the `write` command. This ensures that the configuration is saved and will not be lost after the device is restarted.

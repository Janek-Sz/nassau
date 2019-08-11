Here are things I did on my Virtual Box. Saved in case I would need to install it again. *Which is highly possible.* It's kinda my notepad.

## Disable password authentication

Step 1
Log into Ubuntu and open your Terminal program.

Step 2
Type "sudo nano /etc/sshd_config" (without quotation marks here and throughout) and enter your administrative login password when prompted.

Step 3
Press "Ctrl+W" to open a search window; type in "PasswordAuthentication" and press "Enter."

Step 4
Remove the "#" sign at the start of the PasswordAuthentication label, then replace "Yes" with "No" so that the line reads: PasswordAuthentication no

Save the file and restart the server.

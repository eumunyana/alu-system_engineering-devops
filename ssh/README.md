Background Context


Along with this project, you have been attributed an Ubuntu server, living in a datacenter far far away. You will connect using ssh command by using the RSA key. We’ve configured your server with the public key you will create (“How-To” below) and share it in your intranet profile.

You can access your server information in the my servers section of the intranet, each line with contains the IP and username you should use to connect via ssh.

0. Use a private key
mandatory
Write a Bash script that uses ssh to connect to your server using the private key ~/.ssh/school with the user ubuntu.

1. Create an SSH key pair
mandatory
Write a Bash script that creates an RSA key pair.

2. Client configuration file
mandatory
Your machine has an SSH configuration file for the local SSH client, let’s configure it to our needs so that you can connect to a server without typing a password. Share your SSH client configuration in your answer file.

3. Let me in!
mandatory
Now that you have successfully connected to your server, we would also like to join the party.

Add the SSH public key below to your server so that we can connect using the ubuntu user.

4. Client configuration file (w/ Puppet)
#advanced
Let’s practice using Puppet to make changes to our configuration file. Just as in the previous configuration file task, we’d like you to set up your client SSH configuration file so that you can connect to a server without typing a password.

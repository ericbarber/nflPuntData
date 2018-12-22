*****README*****

To access your instance:
Open an SSH client. (find out how to connect using PuTTY)
Locate your private key file:
	(EricN.Virginia_NFLData.pem)
The wizard automatically detects the key you used to launch the instance.

Your key must not be publicly viewable for SSH to work. Use this command if needed:
	chmod 400 EricN.Virginia_NFLData.pem

Connect to your instance using its Public DNS:
	ec2-54-208-152-68.compute-1.amazonaws.com

Example:
	ssh -i "EricN.Virginia_NFLData.pem" ec2-user@ec2-54-208-152-68.compute-1.amazonaws.com

Please note that in most cases the username above will be correct,
however please ensure that you read your AMI usage instructions to ensure
that the AMI owner has not changed the default AMI username.
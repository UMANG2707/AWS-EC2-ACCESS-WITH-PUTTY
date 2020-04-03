# AWS-EC2-ACCESS-WITH-PUTTY
How to access AWS EC2 ubuntu instances using PuTTY.


###  3 Steps to connect to the instance.
1. Create Instance
2. Download and install PuTTY.
3. Generate Key using PuTTYgen.
4. Connect to the instance using PuTTY.

### Step 1 Create Instance
- Login to AWS Educate Account.
- Go to the services and click on EC2.
- Click on launch Instance.

<img width="960" alt="2020-04-03 (1)" src="https://user-images.githubusercontent.com/48994342/78326131-305af400-7597-11ea-955e-8b27a8fd1004.png">

- Select an Amazone Machine Image as Ubuntu Server 16.04.
- Choose an instance type t2.micro (Which is free).
- Click on Launch.
- Create key pair value if you already have you can choose that exist key pair.
- Download that key pair.
- Click on Lounch Instance.
- Instance is Launched.
- Now, Click on View Instances.
- You can edit the name of instances.
- For edit the name of instance click on pen sign which is in Name column.

### step 2 Download and Install PuTTY.
- For Download PuTTY open link given below.
 ##### https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html
- Now, Download PuTTY installer.
- After that install PuTTY.

### step 3 Generate Key using PuTTYgen.
- Open PuTTYgen.
- Load Keypair file which we have download.(keypair.pen)
- Save Private key (.ppk file).

### step 4 Connect to the instance.
- Open PuTTY.
- Select Private IPV4 of instance.
- Give that ip as host.
- Click on Connection -> SSH -> Auth.
- Browse that private key file which we have generated using PuTTYgen.
- Click on Open.

##### Now you can access your instace.

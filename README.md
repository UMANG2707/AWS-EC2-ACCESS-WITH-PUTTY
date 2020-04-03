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

<img width="960" alt="2020-04-03 (32)" src="https://user-images.githubusercontent.com/48994342/78326240-8760c900-7597-11ea-9b01-c4ea8475420e.png">

- Click on launch Instance.

<img width="960" alt="2020-04-03 (1)" src="https://user-images.githubusercontent.com/48994342/78326131-305af400-7597-11ea-955e-8b27a8fd1004.png">

- Select an Amazone Machine Image as Ubuntu Server 16.04.

<img width="960" alt="2020-04-03 (2)" src="https://user-images.githubusercontent.com/48994342/78326647-87ad9400-7598-11ea-8e6b-1c1792efb282.png">

- Choose an instance type t2.micro (Which is free).

<img width="960" alt="2020-04-03 (3)" src="https://user-images.githubusercontent.com/48994342/78326662-91cf9280-7598-11ea-9faa-dbc3b683ab6f.png">

- Click on Launch.

<img width="960" alt="2020-04-03 (4)" src="https://user-images.githubusercontent.com/48994342/78326672-97c57380-7598-11ea-9f41-76d26ceac3fa.png">

- Create key pair value if you already have you can choose that exist key pair.
- Give Key Pair Name.
- Download that key pair file (Key pair name + .pen).

<img width="960" alt="2020-04-03 (5)" src="https://user-images.githubusercontent.com/48994342/78326681-9e53eb00-7598-11ea-954b-c764a1515816.png">

- Click on Lounch Instance.

<img width="960" alt="2020-04-03 (7)" src="https://user-images.githubusercontent.com/48994342/78326692-a3b13580-7598-11ea-8ca6-16afcbb3dee6.png">

- Instance is Launched.
- Now, Click on View Instances.


<img width="960" alt="2020-04-03 (9)" src="https://user-images.githubusercontent.com/48994342/78326702-a7dd5300-7598-11ea-83c6-310169c18353.png">

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

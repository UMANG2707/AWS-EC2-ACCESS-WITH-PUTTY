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

<img width="960" alt="2020-04-03 (10)" src="https://user-images.githubusercontent.com/48994342/78327751-4074d280-759b-11ea-9fcb-dbbbd8bb1274.png">

- For edit the name of instance click on pen sign which is in Name column.

### step 2 Download and Install PuTTY.
- For Download PuTTY open link given below.
 ##### https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html
 
 <img width="890" alt="2020-04-03 (11)" src="https://user-images.githubusercontent.com/48994342/78327753-41a5ff80-759b-11ea-9f5f-a41cd2c04db1.png">

- Now, Download PuTTY installer.
- After that install PuTTY.

### step 3 Generate Key using PuTTYgen.
- Open PuTTYgen.

<img width="515" alt="2020-04-03 (12)" src="https://user-images.githubusercontent.com/48994342/78327759-42d72c80-759b-11ea-87c0-8bb80c70f680.png">

- Load Keypair file which we have download.(keypair.pen)

<img width="365" alt="2020-04-03 (13)" src="https://user-images.githubusercontent.com/48994342/78327769-466ab380-759b-11ea-8c04-7d638f29aced.png">

- Select key Pair Name file which we have downloaded during step 1 process.(.pen File)

<img width="455" alt="2020-04-03 (14)" src="https://user-images.githubusercontent.com/48994342/78327773-48cd0d80-759b-11ea-8c7d-0dead6180316.png">

- It will show you only private key (.ppk) files for selecting .pen file select All Files *.

<img width="461" alt="2020-04-03 (15)" src="https://user-images.githubusercontent.com/48994342/78327792-51254880-759b-11ea-8fbe-4ed3d449306b.png">

- Save Private key (.ppk file).'

<img width="346" alt="2020-04-03 (17)" src="https://user-images.githubusercontent.com/48994342/78327804-55516600-759b-11ea-97c1-32ed4cdb5082.png">

<img width="450" alt="2020-04-03 (18)" src="https://user-images.githubusercontent.com/48994342/78327807-56829300-759b-11ea-88f9-3b44fa1bd5ed.png">

### step 4 Connect to the instance.
- Open PuTTY.

<img width="572" alt="2020-04-03 (19)" src="https://user-images.githubusercontent.com/48994342/78327810-58e4ed00-759b-11ea-94d3-f217dc8be7b3.png">

- Select Private IPV4 of instance.

<img width="813" alt="2020-04-03 (20)" src="https://user-images.githubusercontent.com/48994342/78327825-5c787400-759b-11ea-961c-d135c7d00d29.png">

- Give that ip as host.


- Click on Connection -> SSH -> Auth.
- Browse that private key file which we have generated using PuTTYgen.
- Click on Open.

##### Now you can access your instace.

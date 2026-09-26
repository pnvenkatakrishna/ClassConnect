# Developer Machine


##  System level setup

- Windows 
	- windows 10 
	- windows 11 
	
- macos 
	- command line interface `Terminal` 

- GUI 
- NON-GUI ( Commmad line interface)
	- create files/directories or folder
	- delete 
	- move 
	- copy 
	- rename
	- sort 
	- find 


- shell 
### Command line interface for windows 
- command prompt (older) 
- powershell ( new) 


Application - Windows Terminal 
	 - windows 11 ( By default) 
	 - windows 10 ( from microsoft store download) 

- any command line interface 


- install - windows terminal  - we can interact with any cli over wt. 
- Settings 	
	- default profil - powershell
	- default terminal application - windows terminal 
	 
	 
### file name extensions and hidden items 

- enable file name extension 
	 windows file explorer - view - show - file name extenstion 
	 
- hiddenitems 
	- any file/ folder start with `.`
	- windows file explorer - view - show - hiddenitems 
	

- Relative path and Absolute path 

Realtive path 

i am in 601 quality thougths     - current location   `.` 

Absolute path 

i am in india, telengana hyderabad ameerpet niligiri block 601   
parent location   `..` 


windows shortcut to open file explorer - `start .`


### git 

- git  -> version control system  - download in machine 
- gitbash  -> cli which can support `linux commands`  - cli support linux 
	- add gitbash profile to windows terminal( while installing) 
 
	


## Package Manager 

- linux 
	- debian family - apt or apt-get 
	- redhat family - yum or dnf 
- windows 
	- chacolatey 
	- winget( by default you will be having)  
		- winget --version


- winget.run 
- winstall.App


### visual studio code 
```bash
winget install -e --id Microsoft.VisualStudioCode
code --version
```

#### extenstions 
	- python 
	- jupyter notebook
	- vscode icons 
	
	

### python 

winget install -e --id Python.Python.3.13
python --version
- pip -> package manager for python

### uv   
winget install -e --id astral-sh.uv

uv --version




### Running powershell/windows terminal regual user or administrator priviliges 


### Cloud clis 
	- aws cli
	`winget install -e --id Amazon.AWSCLI`
	
	- azure cli
	`winget install -e --id Microsoft.AzureCLI`
	- gcp cli
	`winget install -e --id Google.CloudSDK`
		- cli + sdk 
			- cli - support commands`
			- sdk - programatic interaction 
			
	Note: run the command before installing gcp cli
		- execution policy in windows 
		`Set-ExecutionPolicy Unrestricted`
		
		
			
	```bash
	aws --version
	az version
	gcloud --version
	```
	
### creating cloud accounts(free trail) 

- Gcloud account 
	- 300 $ as credit for 3 months 
	- free account in india - deposit 1000/-rs to your gcp cloud account. 
		- 2000/- rs you have to maintain balance. 
	- any other country - no need 
	- everyone has to verify 2/-rs ( refundable) 
	
- gmail 
- bank which supports gcp 
``` 
you are an expert in gcp cloud free account,
i want to create free tier
i have <bankname> and <visa/rupay/master>, will it support to create gcp
```
- card/upi 
	- card 
		- enable international transcations
		- enable e-commerce transcations
		- enable online trancations
	- upi 
		- enable international transcations
		- 15000/- autopay limit, we need to enable 
		- pay as you go that time based upon u're usage. 


notedown 
which bank card 

## aws ( 2 priority ) 

- 100$ for 6 months 
- 5 tasks -> 100$ 
- 12 months basic services 
- gmail 
- bank which supports gcp 
``` 
you are an expert in gcp cloud free account,
i want to create free tier
i have <bankname> and <visa/rupay/master>, will it support to create gcp
```
- card/upi 
	- card 
		- enable international transcations
		- enable e-commerce transcations
		- enable online trancations
	- upi 
		- enable international transcations
		- 15000/- autopay limit, we need to enable 
		- pay as you go that time based upon u're usage. 
- we need submit id proof
	- adhar - DIGI Locker
	- pan
	- voter
	- dirving license
NOTE:
	- Use only one of them 
		

## Azure 
- 200$ for 1 month 
- 12 months basic services 
- gmail 
- bank which supports gcp 
``` 
you are an expert in gcp cloud free account,
i want to create free tier
i have <bankname> and <visa/rupay/master>, will it support to create gcp
```
- card
	- card 
		- enable international transcations
		- enable e-commerce transcations
		- enable online trancations
	


### How to configure gcp cli to gcp cloud 

open terminal 
run
``` 
gcloud init  ## verifies gcloud components
gcloud auth login  ## cli configuration 
gcloud auth application-default login ## sdk configuration 


to verify 

gcloud auth list
gcloud projects list
glcoud config list 
```


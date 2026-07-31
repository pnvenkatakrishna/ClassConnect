# Developer Machine Setup

* clone the project/code
* install dependencies 
* run the application 
* commit the code 
* push it to github

![maya joined office](Images/maya.png)

## windows configurations
- in windows file explorer 
	- enable hidden files 
    	- [refer](https://github.com/pnvenkatakrishna/devops-cloud-setup-guide/blob/main/00-Prerequisites/01-windows-system-settings.md)
	- enable filename extenstions
	- windows file expolere setting( enable details) 

- windows terminal
  - - windows11
	- windows10 ( microsoft store) (win+R --> winver) 
	- powershell is interpreter
	- choose default application is terminal

![alt text](Images/windows.png)

- Verb - Noun  pattern commands follow in windows
`New-item apple.txt`
	
- **setup exectionpolicy** 
	- **open powershell; as run adminstrator** 
		- `Set-ExecutionPolicy Unrestricted`
		- 
- To verify the status `Get-ExecutionPolicy` it has to show `unrestricted`  

- To run scripts in mahcine we need setup exection policy
![alt text](Images/remotesevers.png)

## Development softwares

- git and github 
- gitbash  - can support linux Environment 

[refer here](https://git-scm.com/install/windows)

- To verify 
```bash
git --version
bash --version
```

- i have prepared [docs](https://github.com/pnvenkatakrishna/devops-cloud-setup-guide/tree/main/00-Prerequisites)  to install the softwares check once. 



- **vscode**
[refer here ](https://winstall.app/apps/Microsoft.VisualStudioCode)


- To verfiy `code --version`

- system level - installing softwares 

* windows tools - winget  (package manager) 
* To check the version `winget --version`

these two websites are supporting for windows to get the commands. 

* winstall.app
* winget.run 

**Exercise:** 
Successfully verified installer hash why it is ?  

## Python Environment 
- python 3.13
	- pip (package manager) comes with python.
  [refer here](https://winstall.app/apps/Python.Python.3.13) 

- To check the version `python --version`


- uv (package manager) 
  
  [refer here ](https://winstall.app/apps/astral-sh.uv)

- To verify the version `uv --version`

- project level work check the recording 

- create folder for your course 
![alt text](Images/image.png)


## Version Control system configuration
- create github account with your mail 
[refer here](https://github.com/)  to create the github account. 

# macos 
tool - `Homebrew`  

[refer here](https://brew.sh/) to intall brew in macos

* vscode
* Python
* uv 
* azure cli
* aws cli
* gcp cli
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)" 

brew install --cask visual-studio-code
brew install python@3.13
brew install uv
brew install azure-cli
brew install awscli
brew install --cask gcloud-cli
```

### cloud cli 

- **aws**
  - [refer here](https://winget.run/pkg/Amazon/AWSCLI) aws cli
  
* To check the version `aws --version`

- **azure** 
  -  - [refer here](https://winstall.app/apps/Microsoft.AzureCLI) to install azure cli

* To check the version `az version`

- **gcp** 
  - [refer here](https://winget.run/pkg/Google/CloudSDK) to install gcp cli
- To check the version `gcloud --version`


#### NOTE: 
- before installing gcp cli 
  -  set exection policy as unrestriced or remotesigned


![alt text](Images/cloudconnect.png)
 

# Create cloud accounts


### GCP 
- 300$ for 3 months free plan  2/- 
- 1000/- rs from india (refundable)
[refer here](https://cloud.google.com/) to creat google cloud account 

* i have prepared [docs](https://github.com/pnvenkatakrishna/genai-setup-guide/blob/main/Google-Cloud-Setup/00.google-cloud-freetier-creation.md) to create gcp check once.

 

## aws 
- 100$ for 6 months 
- 5 tasks  one more 100$ 
- 200$ for 6 months as credits
  [refer here](https://aws.amazon.com/free/?trk=78c55dff-53b9-4938-8ed3-d071891360dd&sc_channel=ps&trk=78c55dff-53b9-4938-8ed3-d071891360dd&sc_channel=ps&ef_id=CjwKCAjw7KvTBhA6EiwAWnutYVnGb-6WWudExOEXWtplTSHX3AL_h3s0mWxTSzavB_MyhSS-NDCqQxoCnhMQAvD_BwE:G:s&s_kwcid=AL!4422!3!808712755158!e!!g!!aws!23846236475!198027716802&gad_campaignid=23846236475&gbraid=0AAAAADjHtp9gccaGz2UKWaRnkaQK8Uzj6&gclid=CjwKCAjw7KvTBhA6EiwAWnutYVnGb-6WWudExOEXWtplTSHX3AL_h3s0mWxTSzavB_MyhSS-NDCqQxoCnhMQAvD_BwE) to create aws account. 

* i have prepared [docs](https://github.com/pnvenkatakrishna/devops-cloud-setup-guide/blob/main/03-AWS/01.aws-freetier-creation.md)  to create aws account

## azure  
- for 1 month - 200$ 
[refer here](https://azure.microsoft.com/en-in/pricing/purchase-options/azure-account/search/?ef_id=_k_CjwKCAjw7KvTBhA6EiwAWnutYZL9uWJEmWM24wV31gqq3oJBGey4d2fWAzcDESlhKj64WFUT0-8E8BoCDYIQAvD_BwE_k_&OCID=AIDcmmx83tg6nu_SEM__k_CjwKCAjw7KvTBhA6EiwAWnutYZL9uWJEmWM24wV31gqq3oJBGey4d2fWAzcDESlhKj64WFUT0-8E8BoCDYIQAvD_BwE_k_&gad_source=1&gad_campaignid=23650569745&gbraid=0AAAAADcJh_txHVkto6br9vLktPSjOi6nj&gclid=CjwKCAjw7KvTBhA6EiwAWnutYZL9uWJEmWM24wV31gqq3oJBGey4d2fWAzcDESlhKj64WFUT0-8E8BoCDYIQAvD_BwE) to create azure cloud account. 

Note: before creating cloud accounts check above details

## How to create  cloud accounts ? 

* gmail
* mobile number 
* upi/bank credit/debit 
* mastercard/rupay/visa check this card supporting cloud accounts

* Prompt: 
```text
you are an expert in creating cloud accounts 
i have sbi bank with visa debit card, is it help me create aws azure gcp 

How to enable international transcations
``` 

* for infinity,signal group  
contact: lavanya - 9515151992 
* lab timings : 11 am 6 pm 


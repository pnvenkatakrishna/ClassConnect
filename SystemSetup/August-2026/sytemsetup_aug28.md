# Developer Machine setup

* clone the project 
* run in your machine 
* add new feature(task)
* push to feature branch 

![alt text](Images/august1.png)

# windows 

## System level 
* windows 11/windows10 
	* windows file explorer 
		* enable hiddenitems 
		* filename extensions(.py .yaml .java .tf etc)
		
* open file explorer and click view -> show -> enable 

* any folder or file start with . is called as hiddenfile/folder/directory

* GUI 
  * windows support commandleds 
	* Verb - Noun
		ex: Get-location
		    Get-Timezone
			New-Item <filename>
			Remove-Item <filename>
			Set-Location Downloads\project
			
			
* windows clis
	* command prompt ( older)
	* powershell(primary focus)
	
* windows terminal application
	* can help us to open multiple clis
	* windows 10 - download microsoft store 
	
* to open file explorer from terminal `start .`

* here . means current directory 
 
* Set-Location Downloads\project

* . is current directory 
* .. is parent directory 

* what is realtive path and absolute path ?
	
	

* absolute path 
india/telengana/hyderabad/ameerpet/adithy enclave/nilgiriblock/601



* relatvie path 

niligiriblock/601

* to create folder/directory
	* mkdir <folder>
	
* if we want to work with linux commands  in windows 
* 
	* git
	* gitbash(to perform actions with linux commands) 
	
* download manually 
* enable "add gitbash profile to windows terminal" 


* python 

* version 3.13 version

* python --version

*  python package manager `pip`


* uv is also package manager for python 

* uv --version
	* winget install -e --id astral-sh.uv



* package manager 
* windwos 
1 chacolatey (older)
2 winget (primary) 
```bash
PS C:\Users\nagav> winget --version
v1.29.290
```

* these are supporting windows 
	* winstall.app
	* winget.run 



* visual studio code 
	* winget install -e --id Microsoft.VisualStudioCode
	* code --version

## project level 

# macos 
* to open finder from terminal `open .`

`HomeBrew`

* refer here for macos package manager https://brew.sh/

	* brew install python@3.13

	* python3 --version 

* uv 
brew install uv
* To check the version 
	* uv --version 
	

* visual studio code 
	* brew install --cask visual-studio-code
	* code --version

* linux
	* pwd -- prsent working directory
	* touch -- empty files 
	* cat - to view content commands 

* Refer Here for systemsetup [documentation](https://github.com/pnvenkatakrishna/devops-cloud-setup-guide)
* Refer here for genai [setup guide](https://github.com/pnvenkatakrishna/genai-setup-guide) 
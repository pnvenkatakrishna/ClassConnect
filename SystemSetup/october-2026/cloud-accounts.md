# Cloud Accounts creation 

1. Google Cloud Account 
* 3 months free trail - 300$ as credits 
* for some basic services 1 year. 

### How to create google cloud account
* gmail
* Debit/Credit card/UPI 
* for verfication 2/- deduct ( refundable)
* To get the free, deposit 1000/- ( only for india)
  * if you cancel subscription, close it after 3 months 
* for every month 1st to 30th. 
  * caluculate, what resources you have utlized. 
    * 1st week of month, due date. 
NOTE: 
* Never upgrade your free tier to `full account`. 
```
you are an expert in creating free cloud accounts like GCP, AWS and AZURE.
I have <Bank Name> and <card type>, will it support to create free cloud accont.
if yes, guide me how to enable international transcations. 
``` 

### AWS 
* 6 Months free tier, 100$ 
  * 5 tasks -> each task can give you 20$ 
            -> 100$ 
* Total credits - 200$ 
* for 1 year basic services 

### How to create aws account 

* gmail
* Mobile
* Id card ( voter/Driving/Pan/Adhar)
* Debit/credit/upi
* for verfication 2/- rs (refundable)


### AZURE 
* 200 $ as in free credits for 1 month. 
* * gmail
* Mobile
* Id card ( voter/Driving/Pan/Adhar)
* Debit/credit
* for verfication 2/- rs (refundable)

## cloud cli
* aws cli
```bash
winget install -e --id Amazon.AWSCLI  # windows
brew install awscli  # for macos
aws --version  # to check the version
```
* azure cli
```bash
winget install -e --id Microsoft.AzureCLI
brew install --cask azure-cli
az version
```
* gcp cli 
```bash
winget install -e --id Google.CloudSDK  
#here, if needed add arguments --include-unknown
brew install --cask gcloud-cli
gcloud --version
```
NOTE: 
* Run the command before installing gcp cli
* open powershell as adminstrator and run `Set-ExecutionPolicy Unrestricted`


## How to authenticate gcp cli your machine 
```bash 
gcloud init 
gcloud auth login 
gcloud auth application-default login
``` 

## aws 
* IAM user - some privliges 
`aws configure` 

## Azure 
* az login 


## gcp cloud account 
```bash
gcloud projects list
gcloud auth list 
```

### aws 
``` bash 
aws s3 ls
```

### azure 
```bash
az group list
```
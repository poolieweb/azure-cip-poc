# Azure CIP Deployment Scripts


These are demo scripts for setting up resources within Azure.
You will need an active subscription to deploy to.

AzureAD will not be setup within these scripts, therefore co-administrators will have to be added within the portal.

## Setup

To setup the console to deploy the script you can use Azure CLI or Powershell.
As the Azure CLI is cross platform, we will outline the steps in this document.

For Powershell please see:
Using Azure PowerShell with Azure Resource Manager
https://azure.microsoft.com/en-gb/documentation/articles/powershell-azure-resource-manager/

### Install Node.js (once per machine)

Install Node.js and NPM

https://nodejs.org/

Make sure that npm (Node Package Manager) is installed with Node.js

Test by typing
 npm
in any console window. (You might have to restart a console window)

### Install Azure-CLI (once per machine)

In the console window type
 npm install azure-cli -g
Test by typing
 azure
in the console window.

### Login and open target subscription

Use the following commands

 azure login
 azure account list
 azure account set <yoursubscriptionid>
 azure config mode arm

## Storage and Network setup

Create a Azure Resource Group as a container for the solution
 azure group create -n CIPPoCResourceGroup


## Security Groups

## Availability Sets

## VPN

## Web Layer

## Spak Layer (App)

## Database

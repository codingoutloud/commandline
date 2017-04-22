# Exploring the Azure Command Line in PowerShell and/or CLI

## Format for this document: 

* PowerShell Option
* CLI v2.0 Option

## Install (PowerShell cmdlets or CLI):

* https://docs.microsoft.com/en-us/powershell/azure/install-azurerm-ps
* https://docs.microsoft.com/en-us/cli/azure/install-azure-cli

## Doc:

* https://docs.microsoft.com/en-us/powershell/azure/overview
* https://docs.microsoft.com/en-us/cli/azure/overview

## Login

* Login-AzureRmAccount
* az login

## Choose Subscription (MAY NOT NEED TO DO THIS)

* Select-AzureRmSubscription -SubscriptionName <SUBSCRIPTION NAME HERE>
* Get-AzureRmSubscription

* az account set --subscription <SUBSCRIPTION NAME HERE>
* az account show

## List VMs

* Get-AzureRmVM
* az vm list

## Formatting Example

* 
* https://gist.github.com/codingoutloud/bca4ebf1bf28313acce29e3c84934108

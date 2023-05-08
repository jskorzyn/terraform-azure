terraform {
  required_providers {
    azurerm = {
      source  = "hashicorp/azurerm"
      version = "3.50.0"
    }
  }
}
provider "azurerm" {
  features {}

  # client_id       = 
  # client_secret   = 
  # tenant_id       = 
  # subscription_id = 
}

resource "azurerm_resource_group" "rg" {
  name     = "jsk-demo-grp"
  location = "westeurope"
}

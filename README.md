manageiq-apb
======================

## What it does
An APB for deploying [ManageIQ](http://manageiq.org/).

## Requirements

## Parameters


## Running the application
`docker run -e "OPENSHIFT_TARGET=<openshift_target>" -e "OPENSHIFT_TOKEN=<token>" ansibleplaybookbundle/manageiq-apb provision`

## Tearing down the application
`docker run -e "OPENSHIFT_TARGET=<openshift_target>" -e "OPENSHIFT_TOKEN=<token>" ansibleplaybookbundle/manageiq-apb deprovision`

<a href="https://www.cortex-ia.co.uk/" target="_blank"><img src="https://github.com/CortexIATest/CTXImages/blob/master/Cortex-350-120.png" alt="Welcome to Cortex!" width="350" height="120" border="0"></a>

# CTX-User-Access-Management
The User Access Management module should be used as the single authority to manage authentication and authorisation within a system. This module contains the Cortex flows and subtasks to perform authentication and authorisation. 

The module allows users to perform the following functionality:
* Authenticate a user
* End user session
* Manage active sessions
* Create user session
* Check authorisation token

## Table of Contents
1) [Dependencies](#dependencies)
    * [Cortex Version](#cortex-version)
    * [OCIs](#ocis)
    * [Files](#files)
    * [Other](#other)
1) [Installation](#installation)
1) [How to use](#how-to-use)
1) [How you can contribute](#how-you-can-contribute)
1) [Versioning](#versioning)
1) [Licensing](#licensing)

## Dependencies
### Cortex Version
This version of the CTX-User-Access-Management module was developed in Cortex v6.4.0. Some functionality may not be available in earlier versions of Cortex.

### OCIs
The CTX-User-Access-Management module requires the following Cortex OCIs:
* Cortex Database OCI
* If to be used with Active Directory integration:
	* Cortex Active Directory OCI 
* If to be used with Cortex Vista security integration:
	* Cortex PowerShell OCI
	* [CTX-Vista-User-Management module]()


### Files
The CTX-User-Access-Management module requires the following files:
* [CTX-User-Access-Management Studio Package]()

### Other Requisites
The CTX-User-Access-Management module has no additional requirements.

## Installation
Details of how the module should be imported into Cortex can be found in the [Deployment Plan](#Installation).

## How to use
A detailed User Guide has been provided with instructions on how to use the module, available [here](). Configuration of each flow/subtask's inputs and outputs are detailed in notes on the flow/subtask workspace.

## How you can contribute
Unfortunately, we cannot offer pull requests at this time or accept any improvements.

## Versioning
The CTX-User-Access-Management module has the following versions, starting with the most recent:

Version | Release | Functionality | Notes
------------ | ------------- | ----------- | -----------
v1.1 | 28/01/2019 | Authenticate User | Updated: A bug has been fixed that caused the User Active Directory groups to be all the Domain groups instead of only the groups the User belonged to.
v1.0 | 04/01/2019 | Authenticate User | Created
v1.0 | 04/01/2019 | End user session | Created
v1.0 | 04/01/2019 | Session Management| Created
v1.0 | 04/01/2019 | Create user session | Created
v1.0 | 04/01/2019 | Check authorisation token | Created

## Licensing
All functionality within this module is licensed under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).

Copyright 2018 Cortex Limited

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
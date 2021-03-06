+++
Categories = ["agenda","workshop"]
Tags = ["logistics","speakers"]
date = "2017-11-08T21:44:03+04:00"
title = "Welcome to the Pivotal Cloud Foundry Workshop @ Solera"
type = "Introduction"
weight = 1
+++

##### Date and Time
Date: **November 8 2017**

Time: **9:00 AM - 4:00 PM**

Click on the title to get the Agenda, Prerequisites and Setup for the workshop.

<!--more-->


#### Agenda
* Introductions
* Marketplace Observations
* Cloud Native Architecture
* Introduction to Pivotal Cloud Foundry
* PCF at Audatex
* Lab: Deploying applications
* Services
* Lab: Bind to a Service
* Logging and Metrics
* Lab: Scale an Application
* Lab: Bind to an external service
* Domains and Routing
* Lab: Blue Green Deployments
* Buildpacks
* Spring Cloud Services
* Lab: Spring Cloud Services
* Concourse

---

#### Speakers
+ Rick Ross - Platform Architect at Pivotal
+ Jenny McLaughlin - Platform Architect at Pivotal


---

#### Prerequisites
1. Java SDK 1.8 [Java from Oracle](http://www.oracle.com/technetwork/java/javase/downloads/index.html)

          **DO NOT use Java SDK 1.9**
          
          Set the JAVA_HOME variable to the installation dir, in case it is not automatically set
          
          Add %JAVA_HOME%\bin to your PATH
          
    To verify that you have installed it properly, run the following command from a command prompt or shell:
          
    ```bash
    javac -version
    ```

2. Git CLI for [Windows](https://github.com/git-for-windows/git/releases/download/v2.9.0.windows.1/Git-2.9.0-64-bit.exe)
   or Git from [github.com](https://desktop.github.com)

    If you have installed the Git command line, you can validate the installation by running the following command:
        
    ```bash
    git --version
    ```

3. Cloud Foundry CLI for [Mac](https://github.com/cloudfoundry/cli/releases) or [Windows](http://docs.cloudfoundry.org/devguide/installcf/install-go-cli.html#windows)

    To validate the installation, run the following command from a command prompt or shell:

    ```bash
    cf --version
    ```

4. Curl for [Windows](http://winampplugins.co.uk/curl/)
   Or for [Mac] (http://pdb.finkproject.org/pdb/package.php/curl)

    To validate the installation, run the following command from a command prompt or shell:
        
    ```bash
    curl --version
    ```

5. An account on your PCF Environment

##### Setup

1. Install the Prerequisites software (cf cli)

2. Check if you are able to use the cf cli to connect your PCF  Environment.

          cf login -a https://api.sys.cloud.rick-ross.com  --skip-ssl-validation

3. Check if you are able to connect to Git repo and download / clone the repo using CLI
4. Login to the App Manager Console at

        https://app.cloud.rick-ross.com



#### EBooks
Beyond the Twelve-Factor App - https://pivotal.io/beyond-the-twelve-factor-app
Cloud Foundry: The Cloud Native Platform - https://pivotal.io/cloud-foundry-the-cloud-native-platform
Migrating to Cloud Native Application Architectures - https://pivotal.io/platform/migrating-to-cloud-native-application-architectures-ebook

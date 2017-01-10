![](common/images/header.png)

# Introduction #

This is repository that contains labs material for Cloud Native XWeeks.

## Important to verify before you start ##

Your labs will not work if replication policy on Storage Cloud Service is not set. To set replication policy you need:
+ Login to your cloud account
+ Select on the dashboard Storage Cloud Service
+ Open a Service Console
+ Clink in the top line into RED link "Set Replication Policy" (If you miss this link it means your replication policy was set in advance)
+ Click "Set"
+ Click "Confirm"

----

RECOMMENDED NETWORK:
+ IT WAS REPORTED THAT clear-guest NETWORK IS BLOCKING PORTS AND PROTOCOLS - PLEASE DON'T USE IT!
+ If You use clear netowrk or VPN please open VPN BEFORE launching VM inside VirtualBox. While you work with VM don't change netowrk on the host - every time you do so you need to restart the VM. While you are in VPN please set up properly settings according to [Lab2 document] (cloud-native-devops/CloudWorkshop_CloudNative_200_v1.4.pdf) page 68 / step 27
+ If you make your lab outside Oracle Network - please don't use VPN

----
### Lab 1-4 ###
+ [Official external Cloud Native DevOps workshop](cloud-native-devops/README.md)

### Lab 5 ###

+ [Deploy complex cloud environment using Oracle Cloud Stack Manager](stack/README.md)

### Lab 6 ###


####Integrate telemetry into continuous delivery and monitor an application using the Oracle Management Cloud ####

+ [Create Oracle Developer Cloud Service project for SpringBoot application](springboot-sample/create.devcs.project.md)
+ [Create continuous build integration using Oracle Developer Cloud Service and Oracle Application Container Cloud Service](springboot-sample/devcs.accs.ci.md)
+ [Deploying APM Agent on Apache Tomcat based application and setting up Application Performance Monitoring](apm/README.md)


---

## [Contributing](CONTRIBUTING.md)
Pull Requests are currently not being accepted. See [CONTRIBUTING](CONTRIBUTING.md) for details.

## [License](LICENSE.md)
Copyright (c) 2014, 2016 Oracle and/or its affiliates
The Universal Permissive License (UPL), Version 1.0

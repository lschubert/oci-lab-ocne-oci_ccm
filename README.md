# oci-lab-ocne-oci_ccm
Automation to set up OCNE with OCI Cloud Controller Manager in Oracle provided free lab environment (https://luna.oracle.com/lab/5571f277-3eb9-435f-b3b3-fe421fb9747e)

At the time this code was created the lab timeslot is limited to 1,5 hours. This automation code is inteded to execute the lab steps to save some time.

This automation is best executed within the Luna Lab environment using Visual Studio Code.

# Pre-Requisites on execution machine
- git client, ansible installed
    - verify with ```git version``` and ```ansible --version```

# Instructions to setup

1. Launch Lab

    1.1. Wait until the lab ressources are provisioned. Setting up the underlying OCNE cluster as pre-requisite is part of the free lab provisioning process and takes approximately 30 minutes to finish after launch. The Resources Tab will show a checkamr and further details about provisioned resources once ready. 

2. Checkout this git repo in Luna Lab Visual Studio Code

    2.1 Open Visual Studio Code. Select Topmost left Icon ("Explorer") and press "Clone Repository" button.
    
    Provide github URL: https://github.com/lschubert/oci-lab-ocne-oci_ccm.git
    
    Select "Open Folder" and choose the local path of cloned repo

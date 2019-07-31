# Lab 0b. Installing Pre-requisites

During this session, you will need to have CLI tools installed on your workstation. If you already have these tools installed, you can skip to the next section.

> Note: You need either Mac, Linux or Windows 10 (or later) workstation during this lab. Windows 7 platform is not recommended.
 

## Obtaining and installing the CLI tools on non-Windows 7 platform

1. Docker Toolbox (select your platform from the left-side menu for instructions for Linux, MacOS, Microsoft Windows): https://docs.docker.com/install/

2. Git scm ( if installing on Windows, the git bash shell can be handy too ) https://git-scm.com/downloads

3. IBM Cloud stand-alone CLI: https://cloud.ibm.com/docs/cli/reference/ibmcloud?topic=cloud-cli-install-ibmcloud-cli

4. Installing plugins for the CLI. After installing the IBM Cloud CLI, run these two commands to install the kubernetes and container registry plugins:
    ```
    ibmcloud plugin install kubernetes-service -r Bluemix    
    
    ibmcloud plugin install container-registry -r Bluemix
    ```

    For both of these binaries, copy the code (after unpacking if it is a tarball) to your system path.

5. Install kubectl (our clusters will be set with 1.13.6 - but latest of 1.14 will be ok) https://kubernetes.io/docs/tasks/tools/install-kubectl/






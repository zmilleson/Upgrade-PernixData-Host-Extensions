# Upgrade-PernixData-Host-Extensions
A vCenter Orchestrator workflow to upgrade PernixData host extensions across an entire cluster or selected hosts within cluster.

For a full overview of the workflow process, please visit the following page:

http://www.get-vm.com/blog/2015/01/17/vco-workflow-update-pernixdata-host-extensions/

Prerequisites:

    1. Turn off Write-Back mode on all VMs in the FVP cluster.
    2. Upload the PernixData .zip upgrade file to the /opt/vcofiles directory on the vCO appliance.
    3. Ensure that the zip file in /opt/vcofiles is set to CHMOD 777
    4. have the correct credentials for hosts and vCO appliance.

Disclaimer:

Even though this workflow has worked in my environment, it does NOT mean it will work in yours. 
Make sure you read PernixData’s official documentation and know the process as well as comb over the workflow itself 
to ensure it won’t cause issues within your environment. Use at your own risk and remember, I am not responsible 
if this workflow causes issues within your environment.

Automate all the things!

-Zach

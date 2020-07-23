### VirtualBox

Vagrant uses another program called VirtualBox to actually create this "virtual" machine. Vagrant basically pulls together a few tools to setup and start a virtual machine. VirtualBox is the tool that actually creates the virtual machine.

Let's install that now too.
- if you face any errors please read the instruction/steps thoroughly

[VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- Ensure to install vitual box 6.1 version

![](https://github.com/khanmaster/vb_vagrant_installtion/blob/master/images/VB_Version.png)

We won't actually use VirtualBox directly. Vagrant will handle everything.

> NOTE: Windows user, after installing Virtual Box, you will need to manually install the drivers:

> 1. In File Explorer, navigate to `C:\Program Files\Oracle\VirtualBox\drivers\vboxdrv`
> 2. Right click on the **VBoxDrv.inf** Setup Information file and and select Install
> 3. When it's finished installing, open up a new terminal window and run `sc start vboxdrv`
> 4. Press the Windows Key and search for **Control Panel**, go from there to **Network and Internet**, then **Network and Sharing Centre**, then **Change Adapter Settings**.
> 5. Right click on **VirtualBox Host-Only Network** and choose **Properties**
> 6. Click on **Install => Service**
> 7. Under **Manufacturer** choose **Oracle Corporation** and under **Network Service**, choose **VirtualBox NDIS6 Bridged Networking driver**

> This should install all the drivers you need to run Virtual Box on Windows.

### We are ready to create our virtual environment with vagrant Linux VM/OS!

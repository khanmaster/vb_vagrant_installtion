### Vagrant

- We're going to use a program called Vagrant to do this.
- Vagrant is a program that will run on the developers machine to create a "virtual" machine inside it.

> IMPORTANT NOTE : Try not to think that Vagrant is the only way to do this. It's just one of many possible tools we could use. But it's very common and very popular. This goes for every other tool we use too.

- We can control this virtual machine completely.
- We can install any operating system on it we like and it is kept completely separate and independent of the developer's machine.

Let's install Vagrant now. You can get the program from the following link for Mac, PC or Linux.

[Install vagrant](https://www.vagrantup.com/)

If you are running this on Windows, you will have to do the following things:

> * Make sure that if they have **Hyper-V** disabled. Check via **Turn Windows features on or off**, and disable it and restart if need be.
> * From this point onward to the end of the course, make sure they're **ALWAYS** running their terminal as an administrator, to make sure they have the rights to access whatever they need.

Once you have vagrant installed you can test it by opening a terminal and typing the following:

```bash
vagrant

# You should see the following

vagrant
Usage: vagrant [options] <command> [<args>]

    -v, --version                    Print the version and exit.
    -h, --help                       Print this help.

Common commands:
     box             manages boxes: installation, removal, etc.
     connect         connect to a remotely shared Vagrant environment
     destroy         stops and deletes all traces of the vagrant machine
     global-status   outputs status Vagrant environments for this user
     halt            stops the vagrant machine
     help            shows the help for a subcommand
     hosts           Information about hostnames managed by the vagrant-hosts plugin
     hostsupdater    
     init            initializes a new Vagrant environment by creating a Vagrantfile
     login           log in to HashiCorp\'s Atlas
     package         packages a running vagrant environment into a box
     plugin          manages plugins: install, uninstall, update, etc.
     port            displays information about guest port mappings
     powershell      connects to machine via powershell remoting
     provision       provisions the vagrant machine
     push            deploys code in this environment to a configured destination
     rdp             connects to machine via RDP
     rebuild         plugin: vagrant-digitalocean: destroys and ups the vm with the same ip address
     reload          restarts vagrant machine, loads new Vagrantfile configuration
     resume          resume a suspended vagrant machine
     share           share your Vagrant environment with anyone in the world
     snapshot        manages snapshots: saving, restoring, etc.
     ssh             connects to machine via SSH
     ssh-config      outputs OpenSSH valid configuration to connect to the machine
     status          outputs status of the vagrant machine
     suspend         suspends the machine
     up              starts and provisions the vagrant environment
     vbguest         
     version         prints current and latest Vagrant version

For help on any individual command run `vagrant COMMAND -h`

Additional subcommands are available, but are either more advanced
or not commonly used. To see all subcommands, run the command
`vagrant list-commands`.
```

# The next step is to install virtual box
- Please go to Virtual box folder in this repository for setup guide

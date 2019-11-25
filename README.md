# HW4-510

**HOW TO RUN THE PLAYBOOK?**
> ***ansible-playbook uschatto.yml -i inventory***. This command will do the required installations and necessary setups on another machine whose IP address must be mentioned in the inventory file. A sample inventory file has been provided in this repository. Also ssh keys needs to be setup. For example, if you wish to ssh from machine A to B run ssh-keygen -t rsa on machine A and copy the id_rsa.pub and paste it in machine B's authorized_keys file. This playbook will perform all the setups and run the tasks namely run the app which we will verify via the command forever list and also via the web browser.

<p align="center"> 
<img src="https://media.github.ncsu.edu/user/12214/files/bdc97000-0f35-11ea-9faf-38fc9109a93d" width="600" height="500">
</p>

<p align="center"> 
<img src="https://media.github.ncsu.edu/user/12214/files/637cdf00-0f36-11ea-8bd4-abe66dff2e78" width="900" height="150">
</p>


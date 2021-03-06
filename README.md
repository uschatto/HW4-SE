# HW4-510

**HOW TO RUN THE PLAYBOOK?**
> ***ansible-playbook uschatto.yml -i inventory***. This command will do the required installations and necessary setups on another machine whose IP address must be mentioned in the inventory file. A sample inventory file has been provided in this repository. Also ssh keys needs to be setup. For example, if you wish to ssh from machine A to B run ssh-keygen -t rsa on machine A and copy the id_rsa.pub and paste it in machine B's authorized_keys file. This playbook will perform all the setups and run the tasks namely run the app which we will verify via the command forever list and also via the web browser.

<p align="center"> 
<img src="https://media.github.ncsu.edu/user/12214/files/bdc97000-0f35-11ea-9faf-38fc9109a93d" width="600" height="500">
</p>

<p align="center"> 
<img src="https://media.github.ncsu.edu/user/12214/files/637cdf00-0f36-11ea-8bd4-abe66dff2e78" width="900" height="100">
</p>

[**LINK TO PLAYBOOK**](https://github.ncsu.edu/uschatto/HW4-510/blob/master/uschatto.yml)

**CONCEPTS**
> ***Explain continuous integration. How is it used on a project?***
<p align="justify"> Continuous Integration involves an automatic trigger of a build and further testing and analyzing for each and every change committed to the source repository. The software developers practicing continuous integration keep merging their code changes back to the main branch as often as possible. The developers' changes are validated by triggering an automated build and running integration tests against that build. This avoids the integration messup that usually happens, when people wait for the D-day to merge their respective changes from other branches into the release branch. It also puts a great emphasis on testing automation to check that the build does not break whenever new commits are integrated into the main branch.</p> 

> ***Why should developers use configuration management tools to manage their software programs? What can go wrong if they don't?***
<p align="justify"> Configuration Management Tools help developers establish, maintain the consistency of a system or product, throughout its software development lifetime. They provide the task of tracking and controlling changes in the software, part of the larger cross-disciplinary field of configuration management. They include revision control and the establishment of baselines. If something goes wrong, these tools can determine what was changed and who changed it. If a configuration is working well, tools can determine how to replicate it across many hosts. These tools ensure that the current design and build state of the system is known and recorded; and doesn’t rely on the tacit knowledge of the development team. These tools are basically a collection of competencies, techniques and tools; whose purpose is to ensure the consistency of the system’s requirements, functional attributes and physical properties. For project management and audit purposes, and development activities such as debugging, configuration management tools saves the historical record of system development. For example, to know what has changed between one set of tests and the next, to help identify what could possibly be causing a fault. Moreover, these tools enable developers to formally and safely record all nuanced changes in detail. Particularly, it also records what was changed in the product, but why it was changed is also recorded. It is also necessary to rebuild old versions of products to reproduce problems for customers, such as the military, haven’t upgraded their tools to the latest versions. For these types of upgradations, configuration management tools play an important role. Efficient and properly built configuration management tools enable a system to be rebuilt correctly in the event of mistakes, failures and catastrophes. A few examples of different types of configuration management tools available are: Visual source safe, TortoiseSVN, Subversion, Soncurrent verison system etc. Wrong design being implemented, wrong requirements being accepted, wrong tools being used for development, wrong software being tested, wrong version of software being released or wrong test suite being used or built are some of the ways which would lead to huge amount of wasted efforts, money, late deliveries in turn leading to a loss of customer base. </p>

[**SCREENCAST**](https://drive.google.com/open?id=1wCBvEc_pClzHeESnRNAEuslXSwWM2MDh)

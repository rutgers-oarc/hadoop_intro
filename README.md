# hadoop_intro
a few resources to start exploring the hadoop ecosystem

This repo will contain some simple examples for various bits of hadoop. As well, some other details to setup a personal computer to run a tiny but full version of hadop
Setup for a personal pc has two parts - download software that supports running virtual machines and download a 'personal sandbox' version of hadoop.

There are a few options for supporting virtual machines. For this we will use Virtual box.

https://www.virtualbox.org/
Click on the blue button

https://www.virtualbox.org/wiki/Downloads

Under 'VirtualBox 5.2.6 platform packages' select your operating system and down load!

The manual can be found here: https://www.virtualbox.org/manual/UserManual.html
and the instructions for installation can be found here: https://www.virtualbox.org/manual/ch02.html

We will cover setting up a virtual machine in the workshop.
If you choose to create your own, select 8 gigs of ram if you can. and select 64-bit OS when importing (don't just click on the .ova file). Also note that some anti-virus software may not like virtual box or similar software.

For the hadoop part, we will use Hortonwork's distribution. (Again there are other reasonable choices)

Goto https://hortonworks.com/
and find the dark green box marked 'Get started today with Hortonworks Sandbox' and select the bright green box 'Download HPD Sandbox' 

Download from https://hortonworks.com/products/sandbox/
Select 'Download for Virtualbox' (this should be the top option)

This will bring up a screen asking for contact info. 

This will download an .ova file.
Instructions for importing the virtual machine into VirtualBox

https://hortonworks.com/tutorial/sandbox-deployment-and-install-guide/section/1/#import-the-hortonworks-sandbox

Follow their directions to import the ova file



# k8s-ps
Docs repository for Kubernetes Problem-Solving ATO Workshop

The following is key information about getting setup for this workshop. This information is also at the start of the setup doc.

This workshop assumes you have a working knowledge of Kubernetes.  This is a prerequisite for success in this workshop.

This workshop has labs and it is intended that you use your own computer to do these on, so plan to bring a laptop with you ALREADY SETUP per the directions in the setup doc in this repository.
There will not be time to get everything setup at the workshop.

You may choose to setup your laptop environment either by running the application VirtualBox and a preconfigured virtual machine (VM) with all of the applications already installed and setup on it. Or you may configure your own environment by installing and configuring the applications yourself directly on your system.  
Instructions for the VirtualBox approach are in the setup doc under the heading "Option B: VirtualBox Option." 
Instructions for the self-configured approach are in the setup doc under the heading "Option A: Manual setup".

(The location of the VirtualBox image will be shared via email to attendees.)

While the VirtualBox Option is the simplest in terms of steps required and is the recommended approach, there are times when students may run into issues with running VirtualBox on their systems.  For that case, or if you prefer not to run VirtualBox, you may install the applications separately on your laptop and run them there. 

For either option, it is important that you verify you can get to and use a Kubernetes environment on your laptop prior to the workshop.  At a minimum, you should be able to run the following commands and see appropriate output. 
"kubectl get ns"
"helm version"

After setting up the environment, follow the pre-req steps at the bottom of the document under "Startup - to do before first lab" to be ready for the workshop.


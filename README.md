

<h1>Using Vagrant to automate VM lab creation</h1>

Vagrant is a tool for building and managing virtual machine environments in a single workflow. With an easy-to-use workflow and focus on automation, Vagrant lowers development environment setup time, increases production parity, and makes the works on my machine excuse a relic of the past.

<h2>Description</h2>
Project consists of a utilizing Vagrant and git bash to automate the deployment of VMs locally for testing purposes.

![VM2](https://user-images.githubusercontent.com/85902399/203842471-44d8404c-41e0-4bc5-a85e-785d17fe0cee.png)


<br />


<h2>Languages and Utilities Used</h2>

- <b>Git Bash</b> 
- <b>Oracle VM Virtualbox 6.1 </b>
- <b>Vagrant boxes</b>
- <b>https://app.vagrantup.com/boxes/search</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Ubuntu 18 server
- <b>CentOS7

<h2>Program walk-through:</h2>

<p align="left">
- Search Vagrantup.com and copy Vagrant setup text. <br/>

<img width="507" alt="vagrantfile" src="https://user-images.githubusercontent.com/85902399/203842828-34ac9bac-6a50-4537-8acd-21fee76e8fac.png">


<br />
<br />
using the Vagrant setup text, we run Vagrant init ubuntu/bionic64  <br/>
  
<img width="628" alt="creating Ubuntu18 vm" src="https://user-images.githubusercontent.com/85902399/203843074-7c8304b2-f672-426b-ae47-4303827984c8.png">


<br />
<br />
Once the VM is deployed, we can SSH into it using Vagrant ssh command <br/>

<img width="402" alt="ubuntu ssh" src="https://user-images.githubusercontent.com/85902399/203843301-68234a4d-8d58-4db9-9d39-d3b71a4b6660.png">

<br />
<br />
<img width="391" alt="Vagrant ssh" src="https://user-images.githubusercontent.com/85902399/203843356-1570ab84-2119-4d30-b410-19c0764f0ef6.png">


<br />

We can utilize Vagrant halt to stop the VM and Vagrant destroy to delete it when finished with testing.

<img width="537" alt="halt and destroy" src="https://user-images.githubusercontent.com/85902399/203843732-43e15ab9-8b26-42a2-b541-e4af31b122c9.png">

<br/>
<br/>
  
If I need to recreate a new VM, I just path to the folder and run Vagrant up.  I can create and destroy VM's easily as needed.
  
  <img width="490" alt="recreating vm" src="https://user-images.githubusercontent.com/85902399/203847857-b19e62b4-30f5-435f-a14f-35d418a3f7f0.png">

 
</p>

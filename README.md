# grouppvm

**GrouppVM** is a vulnerable Windows Server 2012 VM made for practicing specific Active Directory attacks. 

# Introduction
While doing Practical Ethical Hacking course from [TCMS Academy](https://academy.tcm-sec.com/) I noticed that one of the attacks required a HackTheBox subscription. After finishing the course, I realized thats the only attack which needs a HTB subscription in order to practice it. So, I ended up making this machine in order to help people get hands-on experience, without having to spend money on the subscription which isnt needed anywhere else in the course.                   

Although that was the main inspiration, this machine is free for use to anyone who wants to practice his Active Directory pentesting skills or have some fun.
# Installation
Installation Files (install one of them):
- OVA: https://mega.nz/file/JLkQXRoT#3MA99LOwYMc4Pacft9oJReruMwm81Ukskwy0zqq--tQ
- OVF: https://mega.nz/file/YK8niATB#5wve9VWtx8W1GZsGv8vj86ZM8rJGBpitK1xv1YlY_2Q
- Disk (Use only if first two files fail to import, should never be used on VirtualBox): 

  https://mega.nz/file/QDcVABob#mE5TfldYYbMF7z3OHld_Z8oDaEg7wOHuVJOjititCWM


Installation is pretty straight-forward:
- Download .ova/.ovf file, unzip it if needed.
- VMWare installation: `Open a new virtual machine` > Select Group.ova / Select Group.ovf.
- VirtualBox installation: `File` > `Import appliance` > Select Group.ova / Select Group.ovf.
- Configure network settings, RAM and CPU and play the machine!


Disk installation:
(Use this only in case of VMWare not importing the .ova or .ovf files. Instructions are specific to VMWare)
- Download the disk file,
- Unzip it
- Click "Create a new virtual machine"
- Select "I will install operating system later" > Next
- Select "Microsoft Windows", Version: "Windows Server 2012" > Next
- For Virtual Machine name you can put whatever you want, for example: "Groupp"
- Set "Maximum disk size" to 10GB, and select "Store virtual disk as a single file". We will remove this disk anyways.
- Finish
- After that, click on a newly made virtual machine, click "Edit virtual machine settings", select Hard Disk and click "- Remove".
- After you remove it, click "+ Add" > Hard Disk > SCSI > Use an existing virtual disk > Select the downloaded .vmdk file > Select "Convert" when the window pops up.
- You're finished, play the machine and enjoy!

# Special Thanks
- Dewalt - Support along the way: https://github.com/Dewalt-arch
- imhasin - Tester


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
(Use this only in case of VMWare not importing the .ova or .ovf files, therefore, instructions are specific to VMWare)
- Download the disk file,
- Unzip it
- Create a new virtual machine, advanced and use existing hard disk
- Point to the vmdk file
- Make that disk SATA instead of SCSI (SCSI might cause bluescreen errors when it tries to boot)
- Select 'Convert' rather than 'Keep existing format'

# Special Thanks
- Dewalt - Support along the way: https://github.com/Dewalt-arch
- imhasin - Tester


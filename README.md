# Window Java VM

This project can be used to created a Windows virtual machine
pre-loaded\* with Java, Git, 7-Zip, the Heroku toolbelt and some other
things. It's based on [ievms](https://github.com/xdissent/ievms).

To use it, put the files in this project on your PATH, then run:

```sh-session
$ windows-create 
Checking for VirtualBox
Checking for Oracle VM VirtualBox Extension Pack
Pack no. 0:   Oracle VM VirtualBox Extension Pack
Building IE9 VM
Checking for existing OVA at /Users/jkutner/.ievms/IE9 - Win7.ova
Checking for existing IE9 - Win7 VM
Creating IE9 - Win7 VM (disk: /Users/jkutner/.ievms/IE9 -
Win7-disk1.vmdk)
0%...10%...20%...30%...40%...50%...60%...70%...80%...90%...100%
Interpreting /Users/jkutner/.ievms/IE9 - Win7.ova...
OK.
Disks:  vmdisk1 135291469824    -1
http://www.vmware.com/interfaces/specifications/vmdk.html#streamOptimized
IE9 - Win7-disk1.vmdk   -1      -1
Virtual system 0:
 0: Suggested OS type: "Windows7"
    (change with "--vsys 0 --ostype <type>"; use "list ostypes" to list
all possible values)
 1: VM name specified with --vmname: "IE9 - Win7"
 2: Number of CPUs: 2
    (change with "--vsys 0 --cpus <n>")
 3: Guest memory: 1024 MB
    (change with "--vsys 0 --memory <MB>")
 4: Sound card (appliance expects "", can change on import)
    (disable with "--vsys 0 --unit 4 --ignore")
 5: USB controller
    (disable with "--vsys 0 --unit 5 --ignore")
 6: Network adapter: orig NAT, config 3, extra slot=0;type=NAT
 7: CD-ROM
    (disable with "--vsys 0 --unit 7 --ignore")
 8: IDE controller, type PIIX4
    (disable with "--vsys 0 --unit 8 --ignore")
 9: IDE controller, type PIIX4
    (disable with "--vsys 0 --unit 9 --ignore")
10: SATA controller, type AHCI
    (disable with "--vsys 0 --unit 10 --ignore")
11: Hard disk image: source image=IE9 - Win7-disk1.vmdk, target
path=/Users/jkutner/.ievms/IE9 - Win7-disk1.vmdk,
controller=10;channel=0
0%...10%...20%...30%...40%...50%...60%...70%...80%...90%...100%
Successfully imported the appliance.
Building IE9 - Win7 VM
build_ievm_ie9
Found ievms control ISO at /Users/jkutner/.ievms/ievms-control-0.2.1.iso
- skipping download
MD5 check succeeded for /Users/jkutner/.ievms/ievms-control-0.2.1.iso
Attaching ievms control ISO
Starting VM IE9 - Win7
Waiting for VM "IE9 - Win7" to power on...
VM "IE9 - Win7" has been successfully started.
Waiting for IE9 - Win7 to shutdown...
Waiting for IE9 - Win7 to shutdown...
Ejecting ievms control ISO
Attaching Guest Additions
Starting VM IE9 - Win7
Waiting for VM "IE9 - Win7" to power on...
VM "IE9 - Win7" has been successfully started.
Waiting for IE9 - Win7 to shutdown...
Waiting for IE9 - Win7 to shutdown...
Waiting for IE9 - Win7 to shutdown...
Waiting for IE9 - Win7 to shutdown...
Waiting for IE9 - Win7 to shutdown...
Waiting for IE9 - Win7 to shutdown...
Waiting for IE9 - Win7 to shutdown...
Waiting for IE9 - Win7 to shutdown...
Waiting for IE9 - Win7 to shutdown...
Waiting for IE9 - Win7 to shutdown...
Waiting for IE9 - Win7 to shutdown...
Waiting for IE9 - Win7 to shutdown...
Waiting for IE9 - Win7 to shutdown...
Waiting for IE9 - Win7 to shutdown...
Waiting for IE9 - Win7 to shutdown...
Ejecting Guest Additions
Tagging VM with ievms version
Creating clean snapshot
0%...10%...20%...30%...40%...50%...60%...70%...80%...90%...100%
Done!
Starting VM IE9 - Win7
Waiting for VM "IE9 - Win7" to power on...
VM "IE9 - Win7" has been successfully started.
Waiting for IE9 - Win7 to be available for guestcontrol...
Waiting for IE9 - Win7 to be available for guestcontrol...
Waiting for IE9 - Win7 to be available for guestcontrol...
Waiting for IE9 - Win7 to be available for guestcontrol...
Waiting for IE9 - Win7 to be available for guestcontrol...
Found 7-Zip at /Users/jkutner/.ievms/7z920.exe - skipping download
MD5 check succeeded for /Users/jkutner/.ievms/7z920.exe
Copying 7z920.exe to /Users/IEUser/Desktop/7z920.exe
Now go manually install 7-zip because Windows (press any key to
continue)

# This is where you have to go manually double click the 7-zip file on
the desktop :(

Copying 7zip-setup.bat to /Users/IEUser/7zip-setup.bat
Found OpenJDK 7 at /Users/jkutner/.ievms/openjdk7.zip - skipping
download
MD5 check succeeded for /Users/jkutner/.ievms/openjdk7.zip
Copying openjdk7.zip to /Users/IEUser/openjdk7.zip
Copying jdk-setup.bat to /Users/IEUser/jdk-setup.bat
Found Apache Maven at /Users/jkutner/.ievms/maven.zip - skipping
download
^[[BMD5 check succeeded for /Users/jkutner/.ievms/maven.zip
Copying maven.zip to /Users/IEUser/maven.zip
Copying maven-setup.bat to /Users/IEUser/maven-setup.bat
Found Git at /Users/jkutner/.ievms/Git-1.9.4-preview20140929.exe -
skipping download
MD5 check succeeded for
/Users/jkutner/.ievms/Git-1.9.4-preview20140929.exe
Copying Git-1.9.4-preview20140929.exe to
/Users/IEUser/Desktop/Git-1.9.4-preview20140929.exe
Now go manually install Git because Windows (press any key to continue)

# Manual again. The Installer will be on the desktop
# Be sure to check "Use Git from Windows prompt" if you need it

Copying git-setup.bat to /Users/IEUser/git-setup.bat
Downloading Heroku Toolbelt from
https://s3.amazonaws.com/assets.heroku.com/heroku-toolbelt/heroku-toolbelt.exe
to /Users/jkutner/.ievms/heroku-toolbelt.exe (attempt 1 of 3)
  % Total    % Received % Xferd  Average Speed   Time    Time     Time
Current
                                 Dload  Upload   Total   Spent    Left
Speed
100 32.3M  100 32.3M    0     0  2994k      0  0:00:11  0:00:11 --:--:--
3529k
MD5 check failed for /Users/jkutner/.ievms/heroku-toolbelt.exe (wanted
d4721f525acad2a7ffcd6dff98b33e18, got 28330b03630b437184c00fdb7d524757)
Redownloading Heroku Toolbelt
Found Heroku Toolbelt at /Users/jkutner/.ievms/heroku-toolbelt.exe -
skipping download
MD5 check failed for /Users/jkutner/.ievms/heroku-toolbelt.exe (wanted
d4721f525acad2a7ffcd6dff98b33e18, got 28330b03630b437184c00fdb7d524757)
Check failed - redownloading Heroku Toolbelt
Downloading Heroku Toolbelt from
https://s3.amazonaws.com/assets.heroku.com/heroku-toolbelt/heroku-toolbelt.exe
to /Users/jkutner/.ievms/heroku-toolbelt.exe (attempt 2 of 3)
  % Total    % Received % Xferd  Average Speed   Time    Time     Time
Current
                                 Dload  Upload   Total   Spent    Left
Speed
100 32.3M  100 32.3M    0     0  2851k      0  0:00:11  0:00:11 --:--:--
3219k
MD5 check failed for /Users/jkutner/.ievms/heroku-toolbelt.exe (wanted
d4721f525acad2a7ffcd6dff98b33e18, got 28330b03630b437184c00fdb7d524757)
Redownloading Heroku Toolbelt
Found Heroku Toolbelt at /Users/jkutner/.ievms/heroku-toolbelt.exe -
skipping download
MD5 check failed for /Users/jkutner/.ievms/heroku-toolbelt.exe (wanted
d4721f525acad2a7ffcd6dff98b33e18, got 28330b03630b437184c00fdb7d524757)
Check failed - redownloading Heroku Toolbelt
Downloading Heroku Toolbelt from
https://s3.amazonaws.com/assets.heroku.com/heroku-toolbelt/heroku-toolbelt.exe
to /Users/jkutner/.ievms/heroku-toolbelt.exe (attempt 3 of 3)
  % Total    % Received % Xferd  Average Speed   Time    Time     Time
Current
                                 Dload  Upload   Total   Spent    Left
Speed
100 32.3M  100 32.3M    0     0  2894k      0  0:00:11  0:00:11 --:--:--
3464k
MD5 check failed for /Users/jkutner/.ievms/heroku-toolbelt.exe (wanted
d4721f525acad2a7ffcd6dff98b33e18, got 28330b03630b437184c00fdb7d524757)
Failed to download
https://s3.amazonaws.com/assets.heroku.com/heroku-toolbelt/heroku-toolbelt.exe
to /Users/jkutner/.ievms//Users/jkutner/.ievms/heroku-toolbelt.exe
(attempt 3 of 3)
```




\* It's windows so you occasionally have to pause and do a step manually

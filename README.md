# violyOS - The secure operating System of the Future.
![violyOS](https://raw.githubusercontent.com/violyOS/violyOS/master/violyOS.png)


## Table of Contents
1. What is violyOS?
2. What are the goals of violyOS ?
3. Developement
4. Building
5. Support
6. Licensing and Copyright
7. Frequently Asked Questions [FAQ]


## What is violyOS ?
violyOS is a GNU/Linux Distribution, which aims to be a secure, perfomant, good-looking and minimal Operating System.  violyOS is not yet production ready so please use on your own risk.

## What are the goals of violyOS ?
We want to build a System that is realiable, fast, secure and modern. Also we want to bring Linux to the Desktop for normal Users. So we our Operating System also aims to be easy to use. Our operating System is completly anonymous, no data of the user will be tracked. Our biggest goal is to replace Windows and OS X as fast as possible.

## Developement
Developement happens in 'dev' branch. New versions will be merged to master.
If you have any Ideas/Improvements feel free to implement them and make a pull request.

## Building
You can build violyOS like this:
git clone https://github.com/violyOS/violyOS.git
cd violyOS
cp source/customrepo /home/YOUR_USERNAME
sudo your_prefered_editor ~/archmid-iso/pacman.conf and edit Server=file:///home/YOUR_USERNAME/customrepo/$arch (near the bottom)
cd ~/customrepo/x86_64
sudo repo-add customrepo.db.tar.gz *.tar.xz
go to the violyOS/source folder
sudo ./build.sh

## Support
If you have any Problems our Questions feel free to contatc us at violy-org@protonmail.com

## Licensing and Copyright
We are licensed under GPLv3. You can read the license details in [LICENSE](https://github.com/violyOS/violyOS/blob/master/LICENSE "LICENSE")

## Frequently Asked Questions [FAQ]
**Q** - Why is violyOS open-source ?  
**A** - violyOS is open-source because we think that Code should be free. Also we are focussed on security and privacy and therefore it is important that our users don't have to trust us, they simply can read the code.

**Q** - Will violyOS stay free ?  
**A** - violyOS will always stay free.

**Q** - Will there be a server version ?  
**A** - No, because Linux already has good server distributions such as CentOS or Ubuntu and only needs help on the Desktop.

**Q** - How can i contribute to this Project ?  
**A** - If you have any Ideas feel free to implement them and make a pull request. If you can't code open a new Issue with the label "feature"

# Net&Sys Assignment: Running Containers for Application Development

Group Name: __Fill your team name__. 

Team Mates:
1. Muhamad Zikry Adib Bin Mohd Suhaimi 2112197
2. __Fill name__ and __matric no__
3. __Fill name__ and __matric no__

## Rules
1. You are allowed to have **3 group** members.
2. When you complete the assignment, make sure to submit the repository link of your cloned project. Make sure all the files are as what you aspect in your repository. 
3. Answer all questions in the **README.md**, in your own repository. Either use the online VSCode, terminal or github to edit. Answers are expected where you see __Fill answer here__.
4. Learn how to use markdown. https://www.w3schools.io/file/markdown-introduction/

## Forking this project repository
1. First thing you need in doing this assignment is to have a github account. Make sure to sign up at https://www.github.com
2. The second thing you need is to fork the Net&Sys Assignment repository in your own github account. 

    1. Go to https://github.com/ZainabBashi/NatSysProject and click fork to copy the project into your own repository
    2. Make sure that the new fork is now in your own repository

***Questions:***

1. What is the link of the fork Net&Sys Assignment in your repository. ***(1 mark)*** _https://github.com/zikry997/NatSysProject_
2. How many files and folders are in this repository. ***(1 mark)***  1 files and 3 folder.


## Exploring github codespaces

1. The next thing that we will be doing is exploring codespaces. First of all, read about codespaces https://docs.github.com/en/codespaces/overview#what-is-a-codespace
2. Then go to the link https://github.com/codespaces and we shall start a new codespace.  
3. Click on ***New codespace***.
4. Choose your own Net&Sys Assignment repository to start your codespace.

 <img src="./images/newcodespace.png" width="50%">

5. Once you have created you codespace, you will see the following. You might already be familiar with this, since it will look similar to VSCode. 

 <img src="./images/UIwebvscode.png" width="70%">

6. You will see the [README file](./README.md) file. One is a preview of how it looks like on the web, and the other is the editing view in markdown language. 
7. Edit the [README file](./README.md). Make sure you have your group details correct, ie, group name and team members along with their matric Numbers. 
8. Once you have finish editing, click File->Save or ***ctrl-s*** to save it. 
9. After saving, you will notice an M or U next to your file. You will need to commit any changes, whenever you make changes so that it is uploaded to the github repository. 

 <img src="./images/SourceControlUI.png" width="70%">

10. Click on the source control, hint: its on the left side panel, and it will list down the files that have been modified or updated. Click on commit. It will then ask you "Would you like to stage all your changes and commit them directly?" Just say yes, and a new tab will appear. Type a message to log what you have done, and click on the check mark. 

 <img src="./images/CommittingUI.png" width="70%">

11. After that, sync the changes to the main repository. 
12. Make sure to commit and sync your files to the main repository, or else, your work will be lost since it is not saved into the main repository when you submit your project.

***Questions:***

1. What is default OS used to run the virtual environment for codespaces. ***(1 mark)*** Linux
2. What are the two options of RAM, disk and vcpu configuration you can have in running codespaces . ***(1 mark)*** __from 2 cores, 8 GB RAM, and 32 GB storage, up to 32 cores, 64 GB RAM, and 128 GB storage.__.
3. Why must we commit and sync our current work on source control? ***(1 mark)*** __Ensures version control and collaboration by tracking changes, facilitating backup, supporting continuous integration, and enabling code review.__

## Exploring the Terminal

1. Look at the TERMINAL tab. Explore and run commands according to the questions below. 
2. You can include your answers as images, or cut and paste the output here. If you are cutting and pasting your answers, wrap your answers in the codeblock clause in markdown. For example, if i run the command **whoami** the the output would look like the one below.
```bash
@joeynor ➜ /workspaces/OSProject (main) $ whoami 
codespace
```



***Questions:***

Look at the TERMINAL tab. Run the following commands and provide the output here. 

1. Run the command **pwd** . ***(1 mark)***
```pwd 
@zikry997 ➜ /workspaces $ pwd
/workspaces
```
2. Run the command **cat /etc/passwd** . ***(1 mark)***
```cat /etc/passwd
@zikry997 ➜ /workspaces $ cat /etc/passwd
root:x:0:0:root:/root:/bin/bash
daemon:x:1:1:daemon:/usr/sbin:/usr/sbin/nologin
bin:x:2:2:bin:/bin:/usr/sbin/nologin
sys:x:3:3:sys:/dev:/usr/sbin/nologin
sync:x:4:65534:sync:/bin:/bin/sync
games:x:5:60:games:/usr/games:/usr/sbin/nologin
man:x:6:12:man:/var/cache/man:/usr/sbin/nologin
lp:x:7:7:lp:/var/spool/lpd:/usr/sbin/nologin
mail:x:8:8:mail:/var/mail:/usr/sbin/nologin
news:x:9:9:news:/var/spool/news:/usr/sbin/nologin
uucp:x:10:10:uucp:/var/spool/uucp:/usr/sbin/nologin
proxy:x:13:13:proxy:/bin:/usr/sbin/nologin
www-data:x:33:33:www-data:/var/www:/usr/sbin/nologin
backup:x:34:34:backup:/var/backups:/usr/sbin/nologin
list:x:38:38:Mailing List Manager:/var/list:/usr/sbin/nologin
irc:x:39:39:ircd:/var/run/ircd:/usr/sbin/nologin
gnats:x:41:41:Gnats Bug-Reporting System (admin):/var/lib/gnats:/usr/sbin/nologin
nobody:x:65534:65534:nobody:/nonexistent:/usr/sbin/nologin
_apt:x:100:65534::/nonexistent:/usr/sbin/nologin
systemd-timesync:x:101:101:systemd Time Synchronization,,,:/run/systemd:/usr/sbin/nologin
systemd-network:x:102:103:systemd Network Management,,,:/run/systemd:/usr/sbin/nologin
systemd-resolve:x:103:104:systemd Resolver,,,:/run/systemd:/usr/sbin/nologin
messagebus:x:104:105::/nonexistent:/usr/sbin/nologin
codespace:x:1000:1000::/home/codespace:/bin/bash
sshd:x:105:65534::/run/sshd:/usr/sbin/nologin
```
3. Run the command **df** . ***(1 mark)*** 
```df
@zikry997 ➜ /workspaces $ df
Filesystem     1K-blocks     Used Available Use% Mounted on
overlay         32847680 10504708  20648876  34% /
tmpfs              65536        0     65536   0% /dev
shm                65536        8     65528   1% /dev/shm
/dev/root       30298176 24573224   5708568  82% /vscode
/dev/loop3      32847680 10504708  20648876  34% /workspaces
/dev/sda1       46127956      268  43752112   1% /tmp
```
4. Run the command **du** . ***(1 mark)***
```du
@zikry997 ➜ /workspaces $ du
36      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETCore/System.IO.FileSystem
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETCore/System.Diagnostics.Contracts
508     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETCore/System.Private.DataContractSerialization
24      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETCore/System.Security.Principal.Windows
40      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETCore/System.ComponentModel.Annotations
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETCore/System.IO.Compression.ZipFile
44      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETCore/System.Security.Cryptography.Algorithms
11228   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETCore
52      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/VisualStudio
120     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Telerik/Telerik.Web.Mvc
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Telerik/Telerik.Windows.Controls.GridView
140     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Telerik
3968    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETStandard/netstandard
3972    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETStandard
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/SimpleInjector
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/Spark.Web.Mvc
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/Caliburn.Micro.Core
160     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/Ninject
24      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/NLog
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/Castle.Windsor
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/AutoMapper
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/JulMar.Wpf.Helpers
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/DryIoc
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/RazorLight
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/Caliburn.Micro
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/ReactiveUI
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/FakeItEasy
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/Prism
84      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/NUnit.Framework
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/Asp.Versioning/Asp.Versioning.Http
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/Asp.Versioning
28      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/System.Threading
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/Nancy.ViewEngines.Razor
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/Stashbox
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/Catel.Core
80      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/xUnit.net
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/Newtonsoft.Json
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/Autofac
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/Statiq.Razor
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/ReactiveUI.Fody.Helpers
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/StructureMap
56      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/Dapper
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/Unity.Abstractions
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/LightInject
28      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/System.Collections.Immutable
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/Storyteller
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/Grace
24      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/log4net
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/Stylet
36      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc/DokanNet
780     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Misc
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Silverlight/System.Windows
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Silverlight
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/SimpleMvvm/SimpleMvvmToolkit
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/SimpleMvvm/SimpleMvvmToolkit_WPF
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/SimpleMvvm
1180    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Data
328     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.ServiceModel.Discovery
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Web.DynamicData.Design
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/Microsoft.Web.WebPages.OAuth
176     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Web.DynamicData
76      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Xaml
160     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Management
512     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Data.Services
40      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.ServiceModel.Extensions
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/Microsoft.Vsa
160     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Xml.Serialization
476     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.IdentityModel
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Web.Helpers
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/Microsoft.Vsa.Vb.CodeDOMProcessor
216     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.DirectoryServices
1876    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Web
276     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Web.Extensions.Design
424     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/WindowsBase
2108    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/PresentationCore
104     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Messaging
580     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Speech
40      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/WindowsFormsIntegration
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/PresentationFramework.Luna
28      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/Microsoft.ServiceModel.Channels.Mail
3500    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.ServiceModel
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.ComponentModel.Composition.Initialization
4292    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Data.Entity
240     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Drawing
104     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Transactions
56      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Data.DataSetExtensions
60      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/UIAutomationClient
560     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Web.Mobile
576     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Data.Services.Client
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/PresentationCFFRasterizer
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Windows.Controls.Navigation
140     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.EnterpriseServices
44      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Windows.Controls
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Xaml.Hosting
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Json
72      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.ComponentModel.DataAnnotations
580     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.ServiceModel.Web
108     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/Microsoft.Build.Utilities.v4.0
156     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Security
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/Microsoft.Build.Conversion.v4.0
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/Microsoft.VisualBasic.Compatibility.Data
36      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.ServiceModel.PollingDuplex
708     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/Microsoft.JScript
2772    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/mscorlib
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.ServiceModel.Channels
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Device
352     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Printing
112     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Web.Entity
940     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Runtime.Serialization
60      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Drawing.Design
32      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.ServiceModel.Web.Extensions
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Web.WebPages.Deployment
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/Microsoft.Build.Framework
164     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.AddIn
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Activities.DurableInstancing
620     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Data.SqlXml
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Web.WebPages.Administration
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/Microsoft.ServiceModel.Channels.Mail.ExchangeWebService
32      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/Microsoft.Build.Utilities
460     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.WorkflowServices
28      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/Microsoft.VisualC.STLCLR
156     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/PresentationBuildTasks
224     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.ComponentModel.Composition
604     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/Microsoft.Transactions.Bridge
84      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Windows.Controls.Ribbon
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Web.ApplicationServices
1340    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Xml
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.IO.Compression
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.ServiceModel.ServiceMoniker40
76      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Windows.Controls.Data
80      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.ServiceModel.Routing
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Windows.Forms.DataVisualization.Design
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Configuration.Install
1024    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Workflow.Activities
204     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Deployment
224     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Configuration
144     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/Microsoft.Build.Tasks
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Net.Http
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Web.Http
3512    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/PresentationFramework
132     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/PresentationUI
772     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/Microsoft.VisualBasic
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/Microsoft.Workflow.Compiler
472     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Web.DataVisualization
1144    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Workflow.ComponentModel
288     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Activities
304     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Data.Entity.Design
308     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/Microsoft.Build.Tasks.v4.0
436     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Workflow.Runtime
968     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Data.Linq
144     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Xml.Linq
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/StdFormat
84      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.IO.Log
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/UIAutomationProvider
432     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Web.Services
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Windows.Controls.Input
84      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Xml.XPath
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.AddIn.Contract
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.ServiceModel.Install
44      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.ServiceModel.NetTcp
28      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Runtime.Caching
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.ServiceProcess
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/Microsoft_VsaVB
28      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Web.Routing
24      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Windows.Input.Manipulations
68      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Runtime.DurableInstancing
40      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.IdentityModel.Selectors
1148    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Core
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.ServiceModel.Activation
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/PresentationFramework.Aero2
192     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Activities.Core.Presentation
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/Microsoft.VisualBasic.Vsa
324     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.DirectoryServices.AccountManagement
688     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/Microsoft.CSharp
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/PresentationFramework.Aero
576     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/Microsoft.Build.Engine
116     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/Microsoft.VisualBasic.Compatibility
1596    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Design
1676    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System
220     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Runtime.Remoting
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Numerics
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Xml.Utils
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/Microsoft.Data.Entity.Build.Tasks
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/PresentationFramework.Royale
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Dynamic
3712    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Web.Mvc
88      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.ServiceModel.Syndication
80      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Windows.Forms.DataVisualization
448     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Windows
632     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/Microsoft.Build
92      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.DirectoryServices.Protocols
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/ADODB
212     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Data.OracleClient
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Windows.Data
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/Microsoft.VisualBasic.Activities.Compiler
96      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Web.WebPages
144     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Management.Instrumentation
32      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/SMDiagnostics
32      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Web.Abstractions
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/WebMatrix.WebData
44      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/Microsoft.Transactions.Bridge.Dtc
116     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/UIAutomationClientsideProviders
800     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Web.Extensions
88      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Web.Entity.Design
76      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Net
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/UIAutomationTypes
40      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Runtime.Serialization.Json
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/PresentationFramework.AeroLite
32      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Web.DataVisualization.Design
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/PresentationFramework.Classic
80      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Runtime.Serialization.Formatters.Soap
648     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Activities.Presentation
144     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Data.Services.Design
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Windows.Controls.Data.Input
1076    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Windows.Forms
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Web.WebPages.Razor
548     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/ReachFramework
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Windows.Presentation
56      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.Windows.Browser
80      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.ServiceModel.Activities
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework/System.IO.Compression.ZipFile
55692   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/.NETFramework
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Catel/Catel.Core
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Catel/Catel.Silverlight
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Catel
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Xamarin
196     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/ReactiveExtensions/System.Reactive.Providers
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/ReactiveExtensions/System.Reactive.Windows.Threading
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/ReactiveExtensions/System.Reactive.Windows.Forms
208     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/ReactiveExtensions/System.Reactive
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/ReactiveExtensions/Microsoft.Reactive.Testing
440     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/ReactiveExtensions
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Xamarin.Forms/Xamarin.Forms.Core
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Xamarin.Forms
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Microsoft/Microsoft.AspNetCore.Mvc.Abstractions
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Microsoft/Microsoft.Practices.Web.UI.WebControls
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Microsoft/Microsoft.AspNetCore.Mvc
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Microsoft/Microsoft.JSInterop
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Microsoft/Microsoft.AspNetCore.Mvc.Razor
72      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Microsoft/EntityFramework
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Microsoft/Microsoft.Extensions.Logging.Abstractions
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Microsoft/Microsoft.CodeAnalysis
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Microsoft/Microsoft.AspNetCore.Routing
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Microsoft/Microsoft.Azure.WebJobs
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Microsoft/Microsoft.AspNetCore.Components
76      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Microsoft/Microsoft.AspNetCore.Mvc.Core
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Microsoft/Microsoft.Practices.Unity
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Microsoft/Microsoft.EntityFrameworkCore.Relational
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Microsoft/Microsoft.AspNetCore.Blazor
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Microsoft/Microsoft.AspNetCore.Mvc.TagHelpers
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Microsoft/Microsoft.Toolkit.Mvvm
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Microsoft/Microsoft.AspNetCore.Routing.Abstractions
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Microsoft/Microsoft.AspNetCore.Http.Abstractions
204     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Microsoft/Microsoft.AspNetCore.Mvc.ViewFeatures
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Microsoft/Microsoft.AspNetCore.Mvc.Razor.Host
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Microsoft/Microsoft.AspNetCore.Mvc.RazorPages
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Microsoft/Microsoft.Practices.Prism
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Microsoft/Microsoft.EntityFrameworkCore
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Microsoft/Microsoft.AspNetCore.Mvc.Versioning
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Microsoft/Microsoft.CodeAnalysis.CSharp
580     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/Microsoft
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/GalaSoft/GalaSoft.MvvmLight.WP71
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/GalaSoft/GalaSoft.MvvmLight.SL5
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/GalaSoft/GalaSoft.MvvmLight.WP7
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/GalaSoft/GalaSoft.MvvmLight
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/GalaSoft/GalaSoft.MvvmLight.WPF4
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/GalaSoft/GalaSoft.MvvmLight.SL4
52      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/GalaSoft
48      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/WinRT/Windows.Phone.PhoneContract
776     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/WinRT/Windows.Foundation.UniversalApiContract
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/WinRT/Windows.Foundation.FoundationContract
652     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/WinRT/Windows
1492    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations/WinRT
74516   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/ExternalAnnotations
2380    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/netcoreapp3.0
384     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/XUnit/net40
416     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/XUnit/netstandard2.0
384     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/XUnit/net45
752     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/XUnit/net35
1944    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/XUnit
108     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/UWP/net451
112     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/UWP
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/net451/pl
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/net451/fr
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/net451/de
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/net451/ru
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/net451/it
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/net451/ko
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/net451/zh-Hans
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/net451/pt-BR
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/net451/tr
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/net451/ja
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/net451/es
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/net451/cs
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/net451/zh-Hant
4036    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/net451
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/netstandard2.0/lib/pl
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/netstandard2.0/lib/fr
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/netstandard2.0/lib/de
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/netstandard2.0/lib/ru
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/netstandard2.0/lib/it
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/netstandard2.0/lib/ko
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/netstandard2.0/lib/zh-Hans
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/netstandard2.0/lib/pt-BR
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/netstandard2.0/lib/tr
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/netstandard2.0/lib/ja
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/netstandard2.0/lib/es
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/netstandard2.0/lib/cs
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/netstandard2.0/lib/zh-Hant
2456    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/netstandard2.0/lib
2580    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest/netstandard2.0
6632    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/MsTest
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/net451/pl
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/net451/fr
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/net451/de
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/net451/ru
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/net451/it
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/net451/ko
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/net451/zh-Hans
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/net451/pt-BR
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/net451/tr
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/net451/ja
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/net451/es
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/net451/cs
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/net451/zh-Hant
4032    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/net451
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/netstandard2.0/pl
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/netstandard2.0/fr
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/netstandard2.0/de
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/netstandard2.0/ru
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/netstandard2.0/it
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/netstandard2.0/ko
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/netstandard2.0/zh-Hans
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/netstandard2.0/pt-BR
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/netstandard2.0/tr
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/netstandard2.0/ja
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/netstandard2.0/es
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/netstandard2.0/cs
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/netstandard2.0/zh-Hant
2572    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest/netstandard2.0
6620    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/VsTest
176     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/NUnit3/net40/lib
1008    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/NUnit3/net40
132     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/NUnit3/netstandard2.0/lib
2452    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/NUnit3/netstandard2.0
176     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/NUnit3/net35/lib
1384    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/NUnit3/net35
4852    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/NUnit3
320     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/NUnit2/net40/lib
404     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/NUnit2/net40
320     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/NUnit2/net35/lib
776     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/NUnit2/net35
1188    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters/NUnit2
21352   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/Adapters
2368    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/netcoreapp2.0
1832    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/net472
1664    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner/net35
29624   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/TestRunner
2508    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost/macos-arm64
610064  ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/ReSharperHost
24      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/pty4j/linux/x86-64
28      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/pty4j/linux
32      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib/pty4j
1369680 ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/lib
307512  ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/bin/icons
168     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/bin/Bridge.framework/Versions/A/Resources
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/bin/Bridge.framework/Versions/A/_CodeSignature
336     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/bin/Bridge.framework/Versions/A
340     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/bin/Bridge.framework/Versions
344     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/bin/Bridge.framework
852     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/bin/JBDevice.framework/Versions/A/Resources
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/bin/JBDevice.framework/Versions/A/_CodeSignature
1168    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/bin/JBDevice.framework/Versions/A
1172    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/bin/JBDevice.framework/Versions
1176    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/bin/JBDevice.framework
319840  ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/bin
336     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/license
76      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/lib/jfr
23640   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/lib/server
7924    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/lib/fonts
348     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/lib/security
27828   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/lib/locales
367020  ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/lib
260     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/bin
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.xml.dom
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/java.security.sasl
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.internal.le
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/java.smartcardio
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/java.prefs
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.security.auth
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.zipfs
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/java.se
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.hotspot.agent
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/java.transaction.xa
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.management.jfr
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/java.logging
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/java.naming
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.compiler
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/java.net.http
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/java.datatransfer
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.naming.rmi
44      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/java.desktop
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.jdi
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.internal.jvmstat
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.management.agent
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.charsets
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.attach
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/java.instrument
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.unsupported.desktop
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/java.management.rmi
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/java.scripting
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/java.compiler
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.crypto.ec
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.localedata
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.jcmd
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/java.sql.rowset
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/java.sql
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.internal.ed
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/java.management
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.javadoc
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.jsobject
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.security.jgss
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/java.rmi
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.accessibility
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.net
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.httpserver
92      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/java.base
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.jfr
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.jdwp.agent
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.sctp
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/java.security.jgss
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.dynalink
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.internal.vm.ci
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/java.xml.crypto
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.crypto.cryptoki
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.unsupported
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.naming.dns
52      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/java.xml
4       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal/jdk.management
444     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/legal
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/include/linux
228     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/include
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/conf/sdp
32      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/conf/management
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/conf/security/policy/unlimited
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/conf/security/policy/limited
36      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/conf/security/policy
100     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/conf/security
160     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr/conf
368120  ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/jbr
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/keymap-visualAssist/lib
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/keymap-visualAssist
224     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dev/lib
228     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dev
209000  ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/DatabaseTools/lib
209004  ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/DatabaseTools
996     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-theme-pack/lib
1000    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-theme-pack
24      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/keymap-resharper/lib
28      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/keymap-resharper
1588    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/grid-core-impl/lib
1592    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/grid-core-impl
768     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/platform-images/lib
772     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/platform-images
2340    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-cpp/lib
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-cpp/projectTemplates/CppGoogleTestTemplate/.template.config
28      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-cpp/projectTemplates/CppGoogleTestTemplate
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-cpp/projectTemplates/CppDynamicLibraryTemplate/.template.config
32      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-cpp/projectTemplates/CppDynamicLibraryTemplate
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-cpp/projectTemplates/CppStaticLibraryTemplate/.template.config
28      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-cpp/projectTemplates/CppStaticLibraryTemplate
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-cpp/projectTemplates/CppConsoleApplicationTemplate/.template.config
28      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-cpp/projectTemplates/CppConsoleApplicationTemplate
128     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-cpp/projectTemplates
2472    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-cpp
5324    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/vuejs/lib
60      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/vuejs/vue-service/node_modules/entities/lib/maps
80      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/vuejs/vue-service/node_modules/entities/lib
96      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/vuejs/vue-service/node_modules/entities
76      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/vuejs/vue-service/node_modules/htmlparser2/lib
96      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/vuejs/vue-service/node_modules/htmlparser2
32      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/vuejs/vue-service/node_modules/ws-typescript-vue-plugin
228     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/vuejs/vue-service/node_modules
232     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/vuejs/vue-service
5560    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/vuejs
240     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/nodeJS-remoteInterpreter/lib
244     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/nodeJS-remoteInterpreter
384     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/performanceTesting-yourkit/lib
11832   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/performanceTesting-yourkit/bin
12220   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/performanceTesting-yourkit
75396   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/space/lib
75400   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/space
1344    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/sh/lib
1348    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/sh
28000   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cwm-plugin-projector/lib/projector
28020   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cwm-plugin-projector/lib
28024   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cwm-plugin-projector
2100    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/ForTea/lib
1228    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/ForTea/dotnet
3332    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/ForTea
7900    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/markdown/lib
7904    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/markdown
24      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/xpath/lib/rt
2568    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/xpath/lib
2572    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/xpath
2208    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/terminal/lib
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/terminal/fish
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/terminal/zsh
2236    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/terminal
8916    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/css-impl/lib
8920    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/css-impl
11896   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/lib
36      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/helpers/jb_declarative_formatters/parsers/natvis
52      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/helpers/jb_declarative_formatters/parsers
108     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/helpers/jb_declarative_formatters
112     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/helpers
164     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/helpers/renderers
192     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/helpers
36      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/renderers/lldb_formatters
40      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/renderers
40      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/x64/lib/python3.8/site-packages/lldb/utils
72      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/x64/lib/python3.8/site-packages/lldb/formatters/cpp
100     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/x64/lib/python3.8/site-packages/lldb/formatters
28      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/x64/lib/python3.8/site-packages/lldb/plugins
876     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/x64/lib/python3.8/site-packages/lldb
916     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/x64/lib/python3.8/site-packages
4564    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/x64/lib/python3.8/lib-dynload
5540    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/x64/lib/python3.8
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/x64/lib/cmake/libxml2
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/x64/lib/cmake
112792  ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/x64/lib
26892   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/x64/bin
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/x64/share/licenses/expat
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/x64/share/licenses/llvm
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/x64/share/licenses/lldb
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/x64/share/licenses/zlib
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/x64/share/licenses/libxml2
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/x64/share/licenses/python
92      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/x64/share/licenses/xz
180     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/x64/share/licenses
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/x64/share/aclocal
196     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/x64/share
139884  ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/x64
40      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/aarch64/lib/python3.8/site-packages/lldb/utils
72      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/aarch64/lib/python3.8/site-packages/lldb/formatters/cpp
100     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/aarch64/lib/python3.8/site-packages/lldb/formatters
28      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/aarch64/lib/python3.8/site-packages/lldb/plugins
932     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/aarch64/lib/python3.8/site-packages/lldb
972     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/aarch64/lib/python3.8/site-packages
6952    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/aarch64/lib/python3.8/lib-dynload
7984    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/aarch64/lib/python3.8
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/aarch64/lib/cmake/libxml2
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/aarch64/lib/cmake
109492  ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/aarch64/lib
26544   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/aarch64/bin
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/aarch64/share/licenses/expat
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/aarch64/share/licenses/llvm
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/aarch64/share/licenses/lldb
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/aarch64/share/licenses/zlib
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/aarch64/share/licenses/libxml2
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/aarch64/share/licenses/python
92      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/aarch64/share/licenses/xz
180     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/aarch64/share/licenses
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/aarch64/share/aclocal
196     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/aarch64/share
136236  ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux/aarch64
276124  ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb/linux
276360  ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin/lldb
276476  ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin/bin
288376  ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cidr-debugger-plugin
68492   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotCommon/lib
27196   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotCommon/DotFiles/linux-x64
28      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotCommon/DotFiles/VsTestDataCollectors/net451
28      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotCommon/DotFiles/VsTestDataCollectors/netcoreapp2.1
60      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotCommon/DotFiles/VsTestDataCollectors
684     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotCommon/DotFiles/NetCore
28      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotCommon/DotFiles/TestRunner/ClientControllers/Profiler/netstandard2.0
28      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotCommon/DotFiles/TestRunner/ClientControllers/Profiler/net461
28      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotCommon/DotFiles/TestRunner/ClientControllers/Profiler/net35
88      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotCommon/DotFiles/TestRunner/ClientControllers/Profiler
92      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotCommon/DotFiles/TestRunner/ClientControllers
96      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotCommon/DotFiles/TestRunner
34192   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotCommon/DotFiles
102688  ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotCommon
56      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/gateway-terminal/lib
60      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/gateway-terminal
104     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/webComponents/lib
108     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/webComponents
6396    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/tasks/lib
6400    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/tasks
2096    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/vcs-perforce/lib
2100    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/vcs-perforce
4664    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/sass/lib
4668    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/sass
588     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/fileWatcher/lib
592     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/fileWatcher
7584    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/w3validators/lib
7588    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/w3validators
592     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/less/lib
596     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/less
7312    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/restClient/lib
7316    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/restClient
1432    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-unity/lib
184     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-unity/dotnetDebuggerWorker
116     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-unity/dotnet/Extensions/com.intellij.resharper.unity/annotations
120     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-unity/dotnet/Extensions/com.intellij.resharper.unity
124     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-unity/dotnet/Extensions
5640    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-unity/dotnet
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-unity/projectTemplates/UnityCSharpProjectTemplate/Properties
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-unity/projectTemplates/UnityCSharpProjectTemplate/.template.config
28      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-unity/projectTemplates/UnityCSharpProjectTemplate
32      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-unity/projectTemplates
56      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-unity/DotFiles
4368    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-unity/EditorPlugin
11716   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-unity
212     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/ini/lib
216     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/ini
804     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/js-liveEdit/lib
808     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/js-liveEdit
376     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotCover/lib
28      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotCover/DotFiles/UnityTestRunner/ClientControllers/Profiler/net461
32      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotCover/DotFiles/UnityTestRunner/ClientControllers/Profiler
36      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotCover/DotFiles/UnityTestRunner/ClientControllers
40      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotCover/DotFiles/UnityTestRunner
6300    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotCover/DotFiles
6680    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotCover
3832    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/vagrant/lib
3836    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/vagrant
2076    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/searchEverywhereMl/lib
2080    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/searchEverywhereMl
784     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotTrace/lib
168     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotTrace/DotFiles/windows-arm64
10784   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotTrace/DotFiles/linux-x64
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotTrace/DotFiles/macos-x64
204     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotTrace/DotFiles/linux-arm64
1828    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotTrace/DotFiles/NetCore
172     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotTrace/DotFiles/windows-x64
152     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotTrace/DotFiles/macos-arm64
58820   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotTrace/DotFiles
59608   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dotTrace
5468    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/angularJS/lib
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/angularJS/ngCli/commands
68      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/angularJS/ngCli
5540    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/angularJS
15432   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/swagger/lib
15436   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/swagger
2400    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/vcs-changeReminder/lib
2404    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/vcs-changeReminder
3332    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/grid-impl/lib
3336    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/grid-impl
4732    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/uml/lib
4736    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/uml
12224   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/gateway-plugin/lib/remote-dev-workers
5964    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/gateway-plugin/lib/gateway-standalone
23440   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/gateway-plugin/lib
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/gateway-plugin/resources
23452   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/gateway-plugin
1716    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/vcs-hg/lib
1720    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/vcs-hg
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/keymap-visualStudio2022/lib
24      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/keymap-visualStudio2022
84      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-publish-custom-server/lib
88      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-publish-custom-server
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/lib
28      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/bin
27604   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/lib
2148    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/bin
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/X11/xkb/keycodes/digital_vndr
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/X11/xkb/keycodes/sgi_vndr
132     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/X11/xkb/keycodes
72      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/X11/xkb/types
684     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/X11/xkb/rules
236     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/X11/xkb/symbols/sun_vndr
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/X11/xkb/symbols/nec_vndr
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/X11/xkb/symbols/fujitsu_vndr
24      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/X11/xkb/symbols/sharp_vndr
36      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/X11/xkb/symbols/digital_vndr
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/X11/xkb/symbols/sony_vndr
84      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/X11/xkb/symbols/macintosh_vndr
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/X11/xkb/symbols/sgi_vndr
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/X11/xkb/symbols/hp_vndr
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/X11/xkb/symbols/jolla_vndr
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/X11/xkb/symbols/xfree68_vndr
120     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/X11/xkb/symbols/nokia_vndr
2340    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/X11/xkb/symbols
48      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/X11/xkb/geometry/digital_vndr
48      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/X11/xkb/geometry/sgi_vndr
416     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/X11/xkb/geometry
80      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/X11/xkb/compat
3728    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/X11/xkb
3732    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/X11
592     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/fontconfig/fonts
600     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained/fontconfig
34088   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server/selfcontained
34128   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remote-dev-server
408     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cloudConfig/lib
412     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/cloudConfig
484     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/UnrealLink/lib
244     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/UnrealLink/dotnet
636     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/UnrealLink/EditorPlugin
1368    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/UnrealLink
1240    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/yaml/lib
1244    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/yaml
9256    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/qodana/lib
9260    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/qodana
8616    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/vcs-github/lib
8620    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/vcs-github
1164    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/completionMlRanking/lib
1168    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/completionMlRanking
37392   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-cwm/lib
2888    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-cwm/quiche-native/darwin-x86-64
1736    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-cwm/quiche-native/linux-aarch64
2224    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-cwm/quiche-native/linux-x86-64
2220    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-cwm/quiche-native/win32-x86-64
2224    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-cwm/quiche-native/darwin-aarch64
11296   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-cwm/quiche-native
48696   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-cwm
52      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/keymap-visualStudio/lib
56      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/keymap-visualStudio
644     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/jade/lib
648     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/jade
128     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-cpp-debugger/lib
132     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-cpp-debugger
27472   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/vcs-svn/lib
27476   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/vcs-svn
292     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-fsharp/lib
7748    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-fsharp/fantomas
29264   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-fsharp/dotnet
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-fsharp/projectTemplates/FSharpClassLibraryTemplate/.template.config
32      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-fsharp/projectTemplates/FSharpClassLibraryTemplate
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-fsharp/projectTemplates/FSharpConsoleApplicationTemplate/.template.config
28      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-fsharp/projectTemplates/FSharpConsoleApplicationTemplate
64      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-fsharp/projectTemplates
220     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-fsharp/typeProviders
37592   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-fsharp
3176    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/nodeJS/lib
52      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/nodeJS/js/mocha-intellij/lib
80      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/nodeJS/js/mocha-intellij
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/nodeJS/js/nodeunit
104     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/nodeJS/js
3284    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/nodeJS
1148    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/properties/lib
1152    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/properties
88      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/performanceTesting-async/lib
92      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/performanceTesting-async
368     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/webpack/lib
372     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/webpack
616     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/tslint/lib
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/tslint/js/languageService
28      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/tslint/js
648     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/tslint
2300    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-razor/lib
2304    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-razor
376     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/html-tools/lib
380     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/html-tools
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/diff/syntaxes
32      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/diff
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/twig/src/languages
28      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/twig/src/hover
84      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/twig/src/syntaxes
36      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/twig/src/snippets
168     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/twig/src
36      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/twig/snippets
236     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/twig
76      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/markdown-basics/syntaxes
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/markdown-basics/snippets
108     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/markdown-basics
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/hlsl/syntaxes
40      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/hlsl
44      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/java/syntaxes
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/java/snippets
76      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/java
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/docker/syntaxes
32      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/docker
32      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/kotlin/syntaxes
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/kotlin/snippets
52      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/kotlin
2136    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/cpp/syntaxes
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/cpp/snippets
2172    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/cpp
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/log/syntaxes
28      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/log
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/css/.vscode
72      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/css/syntaxes
104     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/css
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/search-result/syntaxes
160     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/search-result
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/mdx/syntaxes
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/mdx
80      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/perl/syntaxes
108     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/perl
120     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/csharp/syntaxes
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/csharp/snippets
152     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/csharp
72      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/erlang/grammar
88      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/erlang
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/less/syntaxes
40      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/less
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/dart/syntaxes
40      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/dart
36      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/groovy/syntaxes
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/groovy/snippets
72      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/groovy
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/ini/syntaxes
36      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/ini
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/vb/syntaxes
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/vb/snippets
44      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/vb
24      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/bat/syntaxes
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/bat/snippets
56      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/bat
32      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/go/syntaxes
56      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/go
752     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/latex/syntaxes
792     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/latex
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/restructuredtext/syntaxes
44      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/restructuredtext
24      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/pug/syntaxes
48      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/pug
60      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/scss/syntaxes
84      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/scss
372     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/objective-c/syntaxes
396     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/objective-c
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/json/syntaxes
44      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/json
44      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/fsharp/syntaxes
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/fsharp/snippets
76      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/fsharp
28      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/yaml/syntaxes
52      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/yaml
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/git-base/languages
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/git-base/syntaxes
60      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/git-base
92      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/html/syntaxes
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/html/snippets
124     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/html
40      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/julia/syntaxes
64      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/julia
32      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/powershell/syntaxes
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/powershell/snippets
64      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/powershell
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/markdown-math/syntaxes
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/markdown-math/preview-styles
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/markdown-math/notebook
64      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/markdown-math
56      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/r/syntaxes
80      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/r
24      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/terraform/syntaxes
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/terraform/snippets
100     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/terraform
448     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/typescript-basics/syntaxes
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/typescript-basics/snippets
488     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/typescript-basics
444     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/javascript/syntaxes
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/javascript/snippets
484     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/javascript
36      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/shellscript/syntaxes
60      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/shellscript
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/shaderlab/syntaxes
36      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/shaderlab
36      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/razor/syntaxes
60      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/razor
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/make/syntaxes
44      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/make
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/clojure/syntaxes
40      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/clojure
112     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/swift/syntaxes
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/swift/snippets
148     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/swift
32      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/sql/syntaxes
56      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/sql
68      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/viml/grammars
80      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/viml
32      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/rust/syntaxes
56      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/rust
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/python/.vscode
116     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/python/syntaxes
152     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/python
68      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/ruby/syntaxes
92      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/ruby
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/php/.vscode
144     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/php/syntaxes
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/php/snippets
192     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/php
40      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/coffeescript/syntaxes
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/coffeescript/snippets
72      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/coffeescript
24      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/handlebars/syntaxes
48      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/handlebars
24      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/lua/syntaxes
48      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/lua
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/xml/syntaxes
44      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/xml
60      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/jsp/syntaxes
80      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles/jsp
8128    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib/bundles
8916    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate/lib
8920    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/textmate
472     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/xml-refactoring/lib
476     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/xml-refactoring
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-cpp-injection/lib
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-cpp-injection
30532   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/github-codespaces-ide/lib
30536   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/github-codespaces-ide
3568    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-plugins-appender/lib
3572    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-plugins-appender
188     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dpa/lib
1540    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dpa/DotFiles
1732    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/dpa
11356   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/vcs-git/lib
11360   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/vcs-git
796     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-diagram/lib
800     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/rider-diagram
3036    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/editorconfig/lib
3040    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/editorconfig
3268    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/performanceTesting/lib
3272    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/performanceTesting
7108    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/settingsRepository/lib
7112    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/settingsRepository
1412    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/platform-langInjection/lib
1416    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/platform-langInjection
1756    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remoteRun/lib
1760    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/remoteRun
440     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/postcss/lib
444     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/postcss
604     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-intentions/lib
608     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-intentions
340     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/xaml-preview/lib
344     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/xaml-preview
8724    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-debugger/lib
8728    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-debugger
112     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/tasks-timeTracking/lib
116     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/tasks-timeTracking
1016    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/microservices-ui/lib
1020    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/microservices-ui
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/karma/js_reporter/karma-intellij/lib/kjhtml
112     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/karma/js_reporter/karma-intellij/lib
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/karma/js_reporter/karma-intellij/static
136     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/karma/js_reporter/karma-intellij
140     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/karma/js_reporter
588     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/karma/lib
732     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/karma
20348   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/clouds-docker-impl/lib
20352   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/clouds-docker-impl
6184    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/webDeployment/lib
6188    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/webDeployment
336     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/handlebars/lib
340     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/handlebars
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/helpers/nodejs/library/yarn
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/helpers/nodejs/library
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/helpers/nodejs
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/helpers/buildTools/grunt/lib
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/helpers/buildTools/grunt/tasks
20      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/helpers/buildTools/grunt
24      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/helpers/buildTools
32      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/helpers/base-test-reporter
16      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/helpers/package-version-range-matcher/test
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/helpers/package-version-range-matcher/bin
12      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/helpers/package-version-range-matcher/node_modules/semver/bin
96      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/helpers/package-version-range-matcher/node_modules/semver
100     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/helpers/package-version-range-matcher/node_modules
140     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/helpers/package-version-range-matcher
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/helpers/node-core-modules
40      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/helpers/jest-intellij/lib
44      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/helpers/jest-intellij
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/helpers/vitest-intellij/node_modules
28      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/helpers/vitest-intellij
56      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/helpers/protractor-intellij/lib
60      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/helpers/protractor-intellij
360     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/helpers
48524   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/lib
172     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/jsLanguageServicesImpl/flow
100     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/jsLanguageServicesImpl/typescript/session/old
108     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/jsLanguageServicesImpl/typescript/session
200     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/jsLanguageServicesImpl/typescript
13116   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/jsLanguageServicesImpl/external
13500   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/jsLanguageServicesImpl
52      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/languageService/eslint/bin
8       ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/languageService/eslint/src/typings
52      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/languageService/eslint/src
152     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/languageService/eslint
156     ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/languageService
3576    ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl/js
66120   ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/javascript-impl
64      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/keymap-vscode/lib
68      ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins/keymap-vscode
1283156 ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1/plugins
3551420 ./.codespaces/shared/editors/jetbrains/JetBrainsRider-2023.1
11792788        ./.codespaces/shared/editors/jetbrains
11792792        ./.codespaces/shared/editors
11793160        ./.codespaces/shared
12      ./.codespaces/.persistedshare/devcontainers-cli/cache
16      ./.codespaces/.persistedshare/devcontainers-cli
8       ./.codespaces/.persistedshare/.docker
788     ./.codespaces/.persistedshare
11793952        ./.codespaces
12      ./.oryx
11798724     
```
5. Run the command **ls** . ***(1 mark)*** 
```ls
@zikry997 ➜ /workspaces $ ls
\NatSysProject
```
6. Run the command **ls -asl** . ***(1 mark)*** __Fill answer here__.
7. Run the command **free -h** . ***(1 mark)*** __Fill answer here__.
8. Run the command **cat /proc/cpuinfo** . ***(1 mark)*** __Fill answer here__.
9. Run the command **top** and type **q** to quit. ***(1 mark)*** __Fill answer here__.
10. Run the command **uname -a**. ***(1 mark)*** __Fill answer here__.
11. What is the available free memory in the system. ***(1 mark)*** __Fill answer here__.
12. What is the available disk space mounted on /workspace. ***(1 mark)*** __Fill answer here__.
13. Name the version and hardware architecture of the linux Virtual environment. ***(1 mark)*** __Fill answer here__.
14. What is the difference between **ls** vs **ls -asl**. ***(1 mark)*** __Fill answer here__.
15. What is the TLB size of the Virtual CPU. ***(1 mark)*** __Fill answer here__.
16. What is the CPU speed of the Virtual CPU. ***(1 mark)*** __Fill answer here__.
17. What is the top running process that consumes the most CPU cycles. ***(1 mark)*** __Fill answer here__.

## Running your own container instance.

1. At the terminal, run a linux instance. By typing the following command. 
```
docker pull debian
docker run --detach -it debian
```
2. This will run the debian container. To check if the debian container is running, type
```bash
@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS         PORTS     NAMES
f65be1987f84   debian    "bash"    4 minutes ago   Up 4 minutes             romantic_jackson
```

3. Keep note of the name used by your container, this is usually given random names unless you specify your own name. Now run a bash command on the container. Make sure you use the name of your container instead of the one shown here. 
```bash
docker exec -i -t romantic_jackson /bin/bash
```

4. Create a file on the container. First you must make sure you are in the bash command prompt of the container. The container is new, and does not have any software other than the debian OS. To create a new file, you will need an editor installed. In the bash shell of the container, run the package manager apt-get to install nano text editor. 

```bash
root@f65be1987f84:~# apt-get update      

root@f65be1987f84:~# apt-get install nano

root@f65be1987f84:~# cd /root

root@f65be1987f84:~# nano helloworld.txt
```

5. Edit your helloworld.txt, create your messsage and save by typing ctrl-X. Once saved, explore using the container to see where the file is located. Then exit the shell, by typing **exit**.

6. Stop the container and run **docker ps -a**, and restart the container again. Is your file in the container still available?
```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker restart romantic_jackson
```

7. Stop the container and delete the container. What happened to your helloworld.txt?

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker rm romantic_jackson
```

***Questions:***

1. Are files in the container persistent. Why not?. ***(1 mark)*** __Fill answer here__.
2. Can we run two, or three instances of debian linux? . ***(1 mark)*** __Fill answer here__.

## Running your own container with persistent storage

1. In the previous experiment, you might have notice that containers are not persistent. To make storage persistent, you will need to mount them. 
At the terminal, create a new directory called **myroot**, and run a instance of debian linux and mount myroot to the container. Find out the exact path of my root, and mount it as the root folder in the debian container. 
2. Create a file in /root on the container, the files should also appear in myroot of your host VM.

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ mkdir myroot
@joeynor ➜ /workspaces/OSProject (main) $ cd myroot/
@joeynor ➜ /workspaces/OSProject/myroot (main) $ pwd
/workspaces/OSProject/myroot

@joeynor ➜ /workspaces/OSProject/myroot (main) $ docker run --detach -it -v /workspaces/OSProject/myroot:/root debian
```

***Questions:***

1. Check the permission of the files created in myroot, what user and group is the files created in docker container on the host virtual machine? . ***(2 mark)*** __Fill answer here__.
2. Can you change the permission of the files to user codespace.  You will need this to be able to commit and get points for this question. ***(2 mark)***
```bash
//use sudo and chown
sudo chown -R codespace:codespace myroot

```
*** __Fill answer here__.***

## You are on your own, create your own static webpage

1. Create a directory called webpage in your host machine
2. Inside the directory, create a page index.html, with any content you would like
3. Then, run the apache webserver and mount the webpage directory to it. Hint:
```bash
## the -p 8080:80 flag points the host port 8080 to the container port 80

docker run --detach -v /workspaces/OSProject/webpage:/usr/local/apache2/htdocs/ -p 8080:80 httpd
```

4. If it works, codespace will trigger a port assignment and provide a URL for you to access your webpage like the one below.

 <img src="./images/websitelink.png" width="70%">


5. You can also see the Port in the **PORTS** tab, next to the terminal tab.

6. You can then access your website by adding an index.html towards the end of your url link, like the one below. 

 <img src="./images/helloworldweb.png" width="70%">

***Questions:***

1. What is the permission of folder /usr/local/apache/htdocs and what user and group owns the folder? . ***(2 mark)*** __Fill answer here__.
2. What port is the apache web server running. ***(1 mark)***
3. What port is open for http protocol on the host machine? ***(1 mark)***

## Create SUB Networks

1. In docker, you can create your own private networks where you can run multiple services, in this part, we will create two networks, one called bluenet and the other is rednet
2. Run the docker create network to create you networks like the ones below
```bash
## STEP 1:
## Create Networks ##
docker network create bluenet
docker network create rednet`

## STEP 2: (automatically running)
## Create (1) Container in background called "c1" running busybox image ##
docker run -itd --net bluenet --name c1 busybox sh
docker run -itd --net rednet --name c2 busybox sh
```
***Questions:***

1. Describe what is busybox and what is command switch **--name** is for? . ***(2 mark)*** __Fill answer here__.
2. Explore the network using the command ```docker network ls```, show the output of your terminal. ***(1 mark)***
3. Using ```docker inspect c1``` and ```docker inspect c2``` inscpect the two network. What is the gateway of bluenet and rednet.? ***(1 mark)***
4. What is the network address for the running container c1 and c2.
5. Using the command ```docker exec c1 ping c2```, which basically issue a ping from container c1 to c2. Are you able to ping? Show your output . ***(1 mark)***

## Bridging two SUB Networks
1. Let's try this again by creating a network to bridge the two containers in the two subnetworks
```
docker network create bridgenet
docker network connect bridgenet c1
docker network connect bridgenet c2
docker exec c1 ping c2
```

## What to submit

1. Make sure to commit all changes on your source control, and make sure your source control is sync to the repository. 
2. Check your repository link, to see if all the files and answers are included in the repository. 
3. Submit through italeem, by providing the link to your repository.
4. Due by ***30 May, 2024***

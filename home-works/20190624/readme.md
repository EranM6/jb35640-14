# HOME WORK #2
## Introduction & details
- given on: Mon, June 24, 2019
- delivery date: Thu, June 24th, 2019
- delivery method: written on paper (printed), 
- item(s) to deliver: 
  - please note, deliver (or print) only tasks that are marked as **to-deliver**
  - script code analysis by component, Please use the word document attached
  - printed script(s) file (code)
  - pseudo code, describing the what the script is performing, and why you choose that way to implement.
  - short diagram, describes the infrastructure created by you. use draw.io to generate an image of that (https://draw.io) 
- *DONOT FORGET*: please write your full name, and your ID 
- some guide lines:
  - scripting:
    - keep proper code indentation(s)
    - keep proper code styling 
    - more info you may find here: https://google.github.io/styleguide/shell.xml
     
### Homework subjects:
- Linux Administration:
  - package installation (apt\apt-get\yum)
  - Linux FS hierarchy ( 3rd party tool configuration) ()
  - linux service management (service\systemctl)
  - custom service creation
  - linux user administration
  - text\stream manipulations (sed) 
- Linux Scripting:
  - read bash\shell scripts
  - writing bash\shell code
  - using conditioning (if\elif\fi) 
  - using exit code(s)
  - function using
  - variable usage
  - reading 
- vagrant:
  - vagrant commands: (validate, up, ssh, status, port, destroy, halt, resume )
  
### Homework utilities to be used:
- vagrant - for proper development environments and easy use 
- tomcat  - a 3rd party web server, that we will meet and work on that intensively.

## Homework: user story\client story
### introduction:
Hello **student**,
Welcome to _**Bilbi128-DevOps inc.**_, the leading DevOps consultancy firm in Israel. 
The #1 company in customer care and professionalism.
You have sent to one of our most valuable clients, to take care of all their DevOps needs.

When you approached to the client, one of their developers approaches you and shares with you an issue they are facing with.
the developer is using a web application, hosted upon _**apache tomcat**_ web server (version 8). he needs some SLN to run a complete tomcat server from his laptop. he familiar with vagrant, and prefer to use it, since by using it, he able to build a new development server in seconds. The issue, as he sees, is that he doesn't familiar with tomcat well enough, and the info sec guys are driving him crazy with their demands.

#### Infosec demands:
- The tomcat server will be installed from closed & proven package.
- The tomcat server will be harden (security wise)
- The server will have a custom script, that will enable the users to manual change the TCP port, tomcat is listening to (by default, 8080)
- The port modifier script, will be available to all current users, and future ones. 
- The server will have a _WETTY_ server, to enable the remote SSH user via the web browser.
#### Expected Artifact:
- The expected Artifact (what is need to send to the client), will be a folder that contains the following:
  - vagrant file (**to-deliver&print**) 
  - the **user-data.sh** script (**to-deliver&print**)
  - the **port-modifier.sh** script (**to-deliver&print**)
  - the **wetty-installer.sh** script (**to-deliver&print**)

  
 

 ```bash
.
├── final-artifact
│   ├── Vagrantfile
│   ├── machine-content
│   │   └── port-modifier.sh
│   ├── readme.md
│   ├── sln-diagram.png
│   └── user-data-scripts
│       ├── user-data.sh
│       └── wetty-installer.sh
└── readme.md

3 directories, 7 files



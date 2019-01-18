## Table of Contents

  - [The Challenge](#the-challenge)
  - [Getting Started](#getting-started)
      - [1. Choose your Virtual Machine](#1-choose-your-virtual-machine)
      - [2. Set up your Virtual Machine](#2-set-up-your-virtual-machine)
      - [3. Install Useful Applications](#3-install-useful-applications)
        - [Version Control](#version-control)
        - [Text Editors / IDEs](#text-editors--ides)
        - [Linux on Windows](#linux-on-windows)
        - [Other Applications](#other-applications)
      - [4. Install Avast Secure Browser](#4-install-avast-secure-browser)
      - [5. Install CCleaner](#5-install-ccleaner)
  - [Challenge Code Repositories](#challenge-code-repositories)
  - [Submit Your Hack](#submit-your-hack)

### The Challenge

Integrate the Avast Secure Browser (ASB) and CCleaner products to improve user privacy, prevent website tracking, and reduce the user’s online footprint. Specifically:

-   Create an integration between CCleaner and Avast Secure Browser to clean user browsing data and report the results within CCleaner
-   Build a CCleaner browser extension to clean Avast Secure Browser in real time, making use of custom browser APIs
-   Explore new and innovative ways to improve user privacy online through cleaning, including making of use of other available browser features

Just remember: reaching simple, elegant solutions can often help solve the most technical and complex challenges. We’ll judge competing teams based on teamwork, quality of code, and creativity. We can’t wait to see what you come up with!

More info and background on the challenge can be found on our [blog](https://blog.avast.com/avast-sponsors-hack-cambridge-challenge).

### Getting Started

##### 1. Choose your Virtual Machine

For Mac & Linux users you will need to set up a virtual machine for this challenge. For Windows users, we also recommend using a virtual machine to create a sandboxed environment.

You can use one of the following Virtual Machine platforms:

-   [Parallels](https://www.parallels.com/products/desktop/download/) _(recommended)_
-   [VMWare (Windows/Linux)](https://www.vmware.com/uk/products/workstation-pro/workstation-pro-evaluation.html)
-   [VMWare (Mac)](https://www.vmware.com/uk/products/fusion/fusion-evaluation.html)
-   [VirtualBox](https://www.virtualbox.org/wiki/Downloads)

_Important Note:_ While VirtualBox is free it often performance less well, so a trial of Parallels or VMWare may be a better choice. If you are unfamiliar with Virtual Machines, you can learn more from the wiki page located [here](https://en.wikipedia.org/wiki/Virtual_machine).

##### 2. Set up your Virtual Machine

Once you have chosen your preferred Virtual Machine provider, you will need to setup a Windows Virtual Image. Microsoft make pre-prepped packages available for download within their [Dev Center](https://developer.microsoft.com/en-us/windows/downloads/virtual-machines). Alternatively, you can download free evaulation copies of Windows for 90 days from [here](https://www.microsoft.com/en-us/evalcenter/evaluate-windows-10-enterprise).

_Important Note:_ Virtual machines are great for sandboxed environments, snapshotting and jumping between saved states, but be careful not to lose your work!

##### 3. Install Useful Applications

With a virtual machine, you are starting from scratch so you'll need to install some useful applications to start developing.

###### Version Control

Version control software allows you to manage code (especially in a team) and keep track of your development work:

-   [Git](https://git-scm.com/) _(strongly recommended)_
-   [TortoiseSVN](https://tortoisesvn.net/)
-   [Mercurial SCM](https://www.mercurial-scm.org/)

Assuming you chose Git for version control, you may wish to check out [this great list](https://git-scm.com/downloads/guis) of GUI clients.

_Important Note:_ if you do not chose to work with Git that's fine, however you may require more time to submit your work at the end of the challenge (see _[Finishing Up](#finishing-up)_)

###### Text Editors / IDEs

You'll need a reliable and feature rich text editor / IDE to write your code:

-   [Visual Studio Code](https://code.visualstudio.com/) (recommended)
-   [Atom](https://atom.io/)
-   [Sublime Text](https://www.sublimetext.com/)
-   [Vim](https://www.vim.org/)

###### Linux on Windows

The latest Windows 10 versions supports an Ubuntu Linux subsystem. If you are more comfortable with a Unix-like shell, this may help speed up your development within Windows:

-   [Ubuntu subsystem](https://tutorials.ubuntu.com/tutorial/tutorial-ubuntu-on-windows#0) (recommended)
-   [Git for Windows](https://gitforwindows.org/)

###### Other Applications

We have not categorised these applications as they are not strictly required, however you may find them useful at different stages of the challenge:

-   [Resource Hacker](http://www.angusj.com/resourcehacker/)
-   [Avast Free Antivirus](https://www.avast.com/en-us/free-antivirus-download)

##### 4. Install Avast Secure Browser

We have created a custom build of Avast Secure Browser for the challenge which you can download [here](https://dev-download.avastbrowser.com/ccleaner/avast_secure_browser_setup.exe).

The custom build enables special browser APIs for cleaning browsing data (see the [extension repository](https://github.com/avast/hackcambridge-ccleaner-extension) for more details)

**_Warning:_** If you already have ASB installed on your machine, you'll need to uninstall your existing copy first. Rest assured, you can preserve your user data during this process by leaving it during uninstall and/or making a backup.

##### 5. Install CCleaner

We have created a custom build of CCleaner for the challenge which you can download [here](https://github.com/avast/hackcambridge-ccleaner-app). This build is portable and can be run from any path on the system.

The custom build enables support for an Avast Secure Browser integration and also strips out features that are not necessary for the challenge.

If you wish to install the full version of CCleaner alongside the portable version, you can download [CCleaner Free](https://www.ccleaner.com/ccleaner) from our website.

_Important Note:_ please make sure to keep all listed files of the repository together, as they are needed for the build and integration to work correctly.

### Challenge Code Repositories

Below are links to our other challenge repositories. Each has its own documentation so be sure to read through everything before you begin coding!

-   [Hack Cambridge Challenge](https://github.com/avast/hackcambridge-challenge) - contains general information regarding the challenge (this repository)
-   [Hack Cambridge CCleaner Application](https://github.com/avast/hackcambridge-ccleaner-app) - contains a portable build of CCleaner for the challenge
-   [Hack Cambridge CCleaner Extension](https://github.com/avast/hackcambridge-ccleaner-extension) - contains a CCleaner browser extension stub the challenge

When working with Git, don't forget to:

-   Create a new branch for your work (branched from `master`).
-   Implement your changes (including commenting your code!)
-   Write or adapt tests as needed
-   Add or change the documentation as needed

_Important Note:_ we recommend you clone or download the repositories and create a private origin for the duration of the challenge, so there is no risk of your code being plagiarised (!).

### Submit Your Hack

In order to help us judge your work more effectively, we'd like to get a good view of the code you have written as a team. We use [Devpost](https://ternary.devpost.com/) for hack submissions - you can sign up [here](https://secure.devpost.com/users/register?ref_content=signup_avast&ref_feature=signup&ref_medium=github).

Before submitting, make sure you have completed the following:

- Every member of your team needs to have a Devpost account.
- Only one person needs to submit the hack: to do this click ‘Enter a Submission’.
- Provide a good overview of what you’ve developed in the description field. This will be used as criteria to assess your hack. You can use screenshots if you wish.
- Enter your team members’ Devpost accounts.
- Choose the challenge or challenges you have entered.

***Warning:*** You must submit your hack before hacking ends at **Sunday 20th January 2019 @ 12:01:00 GMT/UTC**, including all relevant source code.

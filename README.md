



[![Docs](https://img.shields.io/badge/docs-latest-brightgreen.svg)](http://doc.servertribe.com)
[![Discord](https://img.shields.io/discord/844971127703994369)](http://discord.servertribe.com)
[![Docs](https://img.shields.io/badge/videos-watch-brightgreen.svg)](https://www.youtube.com/@servertribe)
[![Generic badge](https://img.shields.io/badge/download-latest-brightgreen.svg)](https://www.servertribe.com/community-edition/)

# macOS Parallels APIs






# Attune

[Attune](https://www.servertribe.com/)
automates and orchestrates processes to streamline deployments, scaling,
migrations, and management of your systems. The Attune platform is building a
community of sharable automated and orchestrated processes.

You can leverage the publicly available orchestrated blueprints to increase
your productivity, and accelerate the delivery of your projects. You can
open-source your own work and improve existing community orchestrated projects.

## Get Started with Attune, Download NOW!

The **Attune Community Edition** can be
[downloaded](https://www.servertribe.com/comunity-edition/)
for free from our
[ServerTribe website](https://www.servertribe.com/comunity-edition/).
You can learn more about Attune through
[ServerTribe's YouTube Channel](https://www.youtube.com/@servertribe).







# Clone this Project

To clone this project into your own instance of Attune, follow the
[Clone a GIT Project How To Instructions](https://servertribe-attune.readthedocs.io/en/latest/howto/design_workspace/clone_project.html).




## Blueprints

This Project contains the following Blueprints.



### Configure Parallels VPN VM Settings


### Install Parallels Tools


### KS Check macOS for ISO Building


### KS Clean Build Files


### KS Create Drivers and Answer File ISO


### KS Deploy Parallels Drivers


### KS Deploy Win10 Unattended Config


### KS Deploy Win2019 Unattended Config


### KS Parallels Recreate Virtual Machine


### KS Rename ISO


### KS Setup macOS for ISO Building


### Remove CD ROM Drives and Restart


### KS Create Win2016 Answer File ISO





## Parameters


| Name | Type | Script Reference | Comment |
| ---- | ---- | ---------------- | ------- |
| Kickstarted Node | Basic Node | `kickstartednode` |  |
| Kickstarted Windows Node | Windows Node | `kickstartedwindowsnode` |  |
| Kickstart Organisation Name | Text | `kickstartorganisationname` |  |
| KS Parallels: Attune Base Dir | Text | `ksparallelsattunebasedir` | This will be a subfolder of the user's home directory. Don't start with a / or a ~ |
| KS Parallels: Homebrew Installation Dir | Text | `ksparallelshomebrewinstallationdir` | Use a subfolder of the user's home directory. Don't start with a / or a ~ |
| KS Parallels OS Type | Text | `ksparallelsostype` |  |
| KS: VM CPU Count | Text | `ksvmcpucount` |  |
| KS: VM Ram Size GB | Text | `ksvmramsizegb` |  |
| KS: Windows Interface Alias | Text | `kswindowsinterfacealias` | oVirt = "Ethernet"<br>ESXi = "Ethernet0"<br>Parallels = "Ethernet"<br><br>This is the "InternetAlias" of the interface shown when you run "get-netipaddress" from powershell on the machine. |
| macOS Host | Linux/Unix Node | `macoshost` |  |
| macOS Host User | Linux/Unix Credential | `macoshostuser` |  |
| Parallels Host | Linux/Unix Node | `parallelshost` |  |
| Parallels Host User | Linux/Unix Credential | `parallelshostuser` |  |
| Target Server | Basic Node | `targetserver` |  |
| Target Server: Windows TimeZone | Text | `targetserverwindowstimezone` |  |
| Target Subnet | Network IPv4 Subnet | `targetsubnet` |  |
| Windows: Administrator | Windows Credential | `windowsadministrator` | The windows administrator user |




## Files

| Name | Type | Comment |
| ---- | ---- | ------- |
| Parallels Tools | Large Archives | Get from "/Applications/Parallels Desktop.app/Contents/Resources/Tools/prl-tools-win.iso". |
| Win10 Parallels Unattended Config | Version Controlled Files |  |
| Win2019 Parallels Unattended Config | Version Controlled Files |  |
| WIN Win10 Parallels Drivers | Version Controlled Files | From C:\Program Files (x86)\Parallels\Parallels Tools |
| WIN 10 Parallels Drivers 14-Aug-2023 | Version Controlled Files | This is from "C:\Program Files\Parallels\Parallels Tools\Drivers" after installing Parallels Tools on Win10. |






# Contribute to this Project

**The collective power of a community of talented individuals working in
concert delivers not only more ideas, but quicker development and
troubleshooting when issues arise.**

If you’d like to contribute and help improve these projects, please fork our
repository, commit your changes in Attune, push you changes, and create a
pull request.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-pull-request-01.png" alt="pull request"/>

---

Please feel free to raise any issues or questions you have.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-get-help-02.png" alt="create an issue"/>


---

**Thank you**

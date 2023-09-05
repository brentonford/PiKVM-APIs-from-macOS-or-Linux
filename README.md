



[![Docs](https://img.shields.io/badge/docs-latest-brightgreen.svg)](http://doc.servertribe.com)
[![Discord](https://img.shields.io/discord/844971127703994369)](http://discord.servertribe.com)
[![Docs](https://img.shields.io/badge/videos-watch-brightgreen.svg)](https://www.youtube.com/@servertribe)
[![Generic badge](https://img.shields.io/badge/download-latest-brightgreen.svg)](https://www.servertribe.com/community-edition/)

# PiKVM-APIs






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



### PiKVM Set Boot Order


### Build Linux Machine with PiKVM


### Build Windows Machine with PiKVM





## Parameters


| Name | Type | Script Reference | Comment |
| ---- | ---- | ---------------- | ------- |
| Kickstart Worker Linux User | Linux/Unix Credential | `kickstartworkerlinuxuser` | The user on a linux device used to connect to another device or perform tasks. This could be the device that Attune is running on. |
| PiKVM User: Admin | Linux/Unix Credential | `pikvmuseradmin` | The PiKVM Admin user. |
| Kickstarted Node | Basic Node | `kickstartednode` | The node being kickstarted. |
| PiKVM IP Address | Text | `pikvmipaddress` | The IP Address of the PiKVM. |
| Kickstarted Windows Node | Windows Node | `kickstartedwindowsnode` | The node being kickstarted. This parameter is for Windows specific Steps. |
| Kickstart Worker Linux Node | Linux/Unix Node | `kickstartworkerlinuxnode` | A linux device used to connect to another device or perform tasks. This could be the device that Attune is running on. |
| Kickstarted Windows User | Windows Credential | `kickstartedwindowsuser` | The user for the node being kickstarted. This parameter is for Windows specific Steps. |
| Kickstart Worker Base Dir | Text | `kickstartworkerbasedir` | Directory for storing kickstart files, eg: "/home/attune/kickstart". |




## Files

| Name | Type | Comment |
| ---- | ---- | ------- |






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

<img src="https://raw.githubusercontent.com/Athena-OS/assets/main/banners/athena-banner-discord-bottom-transparent.png" width="auto">

<p align="center">
  <img src="https://img.shields.io/badge/Built with Nix-grey?style=for-the-badge&logo=nixos&color=%23282828">
  <a target="_blank" href="https://github.com/Athena-OS/athena-nix/releases/tag/v23.11">
    <img src="https://img.shields.io/github/v/release/Athena-OS/athena-nix?style=for-the-badge&color=%23DAA632&labelColor=%23282828">
  </a>
  <a target="_blank" href="#downloads">
    <img alt="Download Athena OS" src="https://img.shields.io/sourceforge/dt/athena-iso?style=for-the-badge&labelColor=%23282828&color=%23DAA632&link=https%3A%2F%2Fsourceforge.net%2Fprojects%2Fathena-iso%2Ffiles%2Flatest%2Fdownload">
  </a>
  <a target="_blank" href="https://discord.com/invite/AHXqyJHhGc">
    <img src="https://img.shields.io/discord/977645785170714644?style=for-the-badge&logo=discord&label=Discord&labelColor=282828&color=DAA632">
  </a>
  <img src="https://img.shields.io/github/license/Athena-OS/athena-nix?style=for-the-badge&color=%23DAA632&labelColor=%23282828">
</p>

<br>

<div align="left">
    <img align="left" src="https://media.discordapp.net/attachments/1116690629733400696/1202353321822912582/Athenaos-Squared-black.png?ex=65d6604a&is=65c3eb4a&hm=422dd6a129ace86d06e89b743d6ca63f4226c7df18c6123b38107d655414335d&=&format=webp&quality=lossless&width=200&height=200">
    &nbsp;
    <h1>Athena OS</h1>
    <p>
        ⚡ Dive into a new pentesting experience.
        <br>
        🔥 Born for infosec professionals, passionate students and spicy hackers.
        <br>
        🏆 Get ready to start hacking, elevate your skills!
    </p>
</div>

<br clear="left">

<h2 id="downloads">Downloads</h2>

Athena OS is available under the following architectures:

### x86_64

- ISO Image
- Docker Image
- WSL (Windows Subsystems For Linux)

> [!WARNING]
> We have merged from Arch Linux to a Nix/NixOS-based distribution, currently in pre-release (beta).
> <br>
> The docker image and WSL version are still on the old Arch Linux distribution, this will be updated in the future.

<div align="left">
  <a target="_blank" href="https://github.com/Athena-OS/athena-nix/releases">
      <img src="https://img.shields.io/badge/download-grey?style=for-the-badge&logo=make&label=ISO Image&labelColor=%23282828&color=%23DAA632">
  </a>
  <a target="_blank" href="https://hub.docker.com/u/athenaos">
      <img src="https://img.shields.io/badge/download-grey?style=for-the-badge&logo=docker&label=Docker&labelColor=%23282828&color=%23DAA632">
  </a>
  <a target="_blank" href="https://apps.microsoft.com/store/detail/athena-os/9N1M7Q4F1KQF?hl=en-us&gl=us">
      <img src="https://img.shields.io/badge/download-grey?style=for-the-badge&logo=windows&label=WSL&labelColor=%23282828&color=%23DAA632">
  </a>
</div>

## Overview

Athena OS is an open-source, NixOS-based distribution intended to build a new concept of pentesting operating system. Its purpose is to offer a different experience than the most used pentesting distributions by providing reproducibility, flexibility, isolation, default packages that fit with the user needs, diverse hacking resources and learning materials.

The project is designed from scratch, in development phase, useless modules and services have been excluded in order to improve performance and resource consumption. This design approach allows to review in a detailed manner each single package and component that will be included in the distribution. Despite being based on NixOS, that at first impact could seem to be hard to use, Athena OS offers a user-friendly environment to facilitate the usage.

![athena-themes](https://user-images.githubusercontent.com/83867734/211237687-e238ad4c-8793-45df-9eb7-944b6cc98520.gif)

### Motivations

We seek to take a different compared to other "classical" cybersecurity distributions. Striving for a more community-driven operating system, where the user has better possibilities for configurations, more resources to learn, custom integrated tooling, and a really stable operating system. 
Fostering innovation, continually enhancing the user experience and features over time, to achieve something awesome!

## Features

### Quirks

- **Organized Pentesting Tools**: Classified by [Cyber Roles](https://athenaos.org/en/resources/pentesting-tools/#cyber-security-roles) for efficiency.
- **Hacking Resources**: Various hacking resources are available, including CVE Labs, custom tools and more!
- **Secure Software**: Only secure packages are retrieved, with continuous checks for vulnerabilities.
- **Declarative Configuration**: Declarative approach to system configuration.
- **Flexibility**: Allows deep customization of system configurations, with various presets and modules.
- **Immutable System State**: Configuration changes result in a new system state for consistency.
- **Conflict Prevention**: Isolated packages with explicitly declared dependencies prevent conflicts.
- **Atomic Upgrades and Rollbacks**: Supports seamless transitions between system states.
- **Reproducibility**: Easy to replicate environments and maintain consistency across systems.
- **Lazy Evaluation**: Packages built on demand, reducing unnecessary builds.
- **Isolation and Sandboxing**: Enhanced security through package isolation and sandboxed builds.
- **Cross-Platform Support**: Designed for flexibility across different platforms.
- **FOSS**: Forever fully open-source and accessible to everyone.

### Cyber Resources

- [**Pentesting Tools**](https://athenaos.org/en/resources/pentesting-tools/)
- **HTB Toolkit**: Users can play Hack The Box directly on Athena OS using the [Hack The Box Toolkit](https://athenaos.org/en/resources/htb-toolkit/).
- **PWNage Menu**: The [PWNage Menu](https://athenaos.org/en/resources/pwnage-menu/) allows users to access instantly the main hacking platforms for learning purposes and to join the main Discord cybersecurity communities.
- **Blue Team Menu**: [Blue Team Menu](https://athenaos.org/en/resources/blueteam-menu/) is born for organizing in a pretty manner the main security defensive tools that users need to start their Blue Team activity. 
- **Red Team Menu**: [Red Team Menu](https://athenaos.org/en/resources/redteam-menu/) is born for organizing in a pretty manner the main pentesting tools that users need to start their hacking activity. It is deployed in different ways depending to the installed environment.
- **Payload to Dock**: [Payload to Dock](https://athenaos.org/en/resources/payload-dock/) keeps access to the most famous payload repositories and retrieves the latest version of payloads.
- **Payload Environments Vars**: For accessing resources in a quick manner, several [environment variables](https://athenaos.org/en/resources/payload-variables/) have been defined.
- **Browser Pentesting Addons**: Integrated browsers [have been modified](https://athenaos.org/en/resources/browser-pentesting/) in order to integrate hardening and various extensions. 
- **NIST Feed**: [NIST Feed](https://athenaos.org/en/resources/nist-feed/) is a special tool able to retrieve information about existing CVEs (Common Vulnerabilities and Exposures) and inform you about new published or updated CVEs by connecting to the [NIST National Vulnerability Database](https://nvd.nist.gov/).


> [!NOTE]
> This is a non-exhaustive list of features, if you want to know more about the <br> 
advantages of using Athena OS, please take a look at [our documentation](https://athenaos.org/).


## Contributing

The project is being developed actively, but the more we are, the more Athena will grow and shine. <br>
If you want to help us create something awesome, you can contribute in several manners. 
Please see the [Contribution Guide](https://athenaos.org/en/community/contribute/) on our [wiki](https://athenaos.org/en/getting-started/athenaos/). <br>
You can also join our [Discord Server](https://discord.com/invite/AHXqyJHhGc) to discuss about contributions aspects, and other topics!

## Sponsors
Dedicating our spare time to Athena OS in order to keep the project stable, updated, and continuing to integrate new stuff is not easy, but providing your support will make it possible for us to invest more time, pushing the project as far as possible.

<br>

<table>
    <tr>
        <th>🥇 Gold sponsors</th>
        <th>🥈 Silver sponsors</th>
        <th>🥉 Bronze sponsors</th>
        <th>☕ Coffee sponsors</th>
    </tr>
    <tr>
        <td><a href='https://github.com/Apok01'>@Apok01</a><br></td>
        <td><a href='https://github.com/Hannes1909'>@Hannes1909</a><br></td>
        <td><a href='https://github.com/Martian1337'>@Martian1337</a><br></td>
        <td>@IlMioAmicoAle<br></td>
    </tr>
    <tr>
        <td><a href='https://github.com/orion715'>@orion715</a><br></td>
        <td></td>
        <td></td>
        <td><a href='https://github.com/mcfly76'>@mcfly76</a><br></td>
    </tr>
    <tr>
        <td></td>
        <td></td>
        <td></td>
        <td><a href='https://github.com/SinSiXX'>@SinSiXX</a><br></td>
    </tr>
    <tr>
        <td></td>
        <td></td>
        <td></td>
        <td><a href='https://github.com/CriminalShrimp'>@CriminalShrimp</a><br></td>
    </tr>
</table>

<br>

Do you like the project? You may <a href="https://github.com/sponsors/Athena-OS">become a sponsor by offering us one coffee ☕ / month</a>!

## Credits

* [NixOS/Nix/Nixpkgs Contributors](https://github.com/NixOS/): Reviewing, packaging and maitaining tools
* [Simon Schneegans](https://github.com/Schneegans): Fly-Pie menu extension
* [Hack The Box](https://www.hackthebox.com): Bash and PowerShell icons; Hack The Box icon
* [Offensive Security](https://www.offensive-security.com): Kali Linux security tools icons; Offensive Security icon
* [Kitsunekun](https://www.furaffinity.net/view/23914148): Athena Chibi Logo

## Publications

[PenTest Magazine](https://pentestmag.com/product/pentest-open-source-pentesting-toolkit) (Click **Download** for getting the complete Magazine!)


## Statistics

<a href="https://next.ossinsight.io/widgets/official/compose-activity-trends?repo_id=503528235" target="_blank" style="display: block" align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://next.ossinsight.io/widgets/official/compose-activity-trends/thumbnail.png?repo_id=503528235&image_size=auto&color_scheme=dark" width="400" height="auto">
    <img alt="Activity Trends of pingcap/tidb - Last 28 days" src="https://next.ossinsight.io/widgets/official/compose-activity-trends/thumbnail.png?repo_id=503528235&image_size=auto&color_scheme=light" width="400" height="auto">
  </picture>
</a>
<a href="https://next.ossinsight.io/widgets/official/compose-last-28-days-stats?repo_id=503528235" target="_blank" style="display: block" align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://next.ossinsight.io/widgets/official/compose-last-28-days-stats/thumbnail.png?repo_id=503528235&image_size=auto&color_scheme=dark" width="350" height="auto">
    <img alt="Performance Stats of Athena-OS/athena-nix - Last 28 days" src="https://next.ossinsight.io/widgets/official/compose-last-28-days-stats/thumbnail.png?repo_id=503528235&image_size=auto&color_scheme=light" width="350" height="auto">
  </picture>
</a>

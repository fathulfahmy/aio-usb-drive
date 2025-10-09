<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->

<a id="readme-top"></a>

<!-- PROJECT SHIELDS -->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <!-- <a href="https://github.com/fathulfahmy/aio-usb-drive">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a> -->

<h3 align="center">All In One USB Drive</h3>

  <p align="center">
    A curated collection of useful to have programs on a multiboot USB drive
    <br />
    <a href="https://github.com/fathulfahmy/aio-usb-drive"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <!-- <a href="https://github.com/fathulfahmy/aio-usb-drive">View Demo</a>
    &middot; -->
    <a href="https://github.com/fathulfahmy/aio-usb-drive/issues/new?template=bug-report.yml">Report Bug</a>
    &middot;
    <a href="https://github.com/fathulfahmy/aio-usb-drive/issues/new?template=feature-request.yml">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about">About</a>
    </li>
    <li><a href="#programs">Programs</a></li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#setup-usb-drive">Setup USB Drive</a></li>
        <li><a href="#add-programs">Add Programs</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#faq">FAQ</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About

![All In One USB Drive Screen Shot][product-screenshot]

All In One USB Drive is a curated collection of diagnostic and rescue tools, operating system, and application installers, along with a step‑by‑step guide for preparing and using the USB drive. The repository serves as a reference for building a "Swiss‑army knife" USB drive that bundles essential utilities into a single, updatable, portable toolkit.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- PROGRAMS -->

## Programs

### Open-source

| Name         | Description                                               | Download                               |
| ------------ | --------------------------------------------------------- | -------------------------------------- |
| SystemRescue | Linux-based rescue toolkit                                | [Download SystemRescue][system-rescue] |
| Rescuezilla  | Disk imaging/cloning                                      | [Download Rescuezilla][rescuezilla]    |
| Netboot.xyz  | Network required rescue toolkit and OS installer          | [Download Netboot.xyz][netbootxyz]     |
| Debian       | LTS Linux distro live environment and installer           | [Download Debian][debian]              |
| Ubuntu       | LTS Linux distro live environment and installer           | [Download Ubuntu][ubuntu]              |
| Fedora Linux | Bleeding-edge Linux distro live environment and installer | [Download Fedora Linux][fedora-linux]  |
| Arch Linux   | Bleeding-edge Linux distro installer                      | [Download Arch Linux][arch-linux]      |

### Closed-source

| Name              | Description                             | Download                                       |
| ----------------- | --------------------------------------- | ---------------------------------------------- |
| Hiren's BootCD PE | Windows 11-based rescue toolkit         | [Download Hiren's BootCD PE][hirens-bootcd-pe] |
| Windows 11        | Microsoft Windows 11 installer          | [Download Windows 11][windows11]               |
| OfficeSetup       | Microsoft Office 365 Pro Plus installer | [Download Office365][office365]                |

> [!TIP]  
> See [Community Pick](#community-pick) for recommended tools and alternatives by the community.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting started

### Prerequisites

- USB drive

> [!IMPORTANT]  
> Minimum 32 GB  
> Recommended 64 GB  
> (To install all programs listed above)

### Setup USB Drive

1. Format USB drive
2. [Download Ventoy][ventoy]
3. Extract Ventoy
4. Run `Ventoy2Disk.exe` on Windows or `VentoyGUI` on Linux
5. Select USB drive
6. Click install or update

### Add Programs

1. Download ISO
2. Copy and paste ISO to multiboot USB drive

> [!TIP]  
> Ventoy USB drive works as a regular USB drive. You may add or remove any type of files. You may format Ventoy USB drive to remove Ventoy.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE -->

## Usage

1. Power OFF PC
2. Insert multiboot USB drive
3. Power ON PC
4. Enter BIOS
5. Set multiboot USB drive as first boot option
6. Save and exit

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FAQ -->

## FAQ

**Q: How to launch Netboot.xyz?**  
A: Connect PC to ethernet before turning on PC

<br />

**Q: Where is GParted and Memtest86+?**  
A: It is included in SystemRescue

<br />

**Q: How to activate Microsoft?**  
A: Run [Microsoft Activation Script][massgrave]

1. Install Microsoft Windows or Microsoft Office 365
2. Launch Windows
3. Open Powershell
4. Copy and paste the code below

```sh
irm https://get.activated.win | iex
```

4. Press Enter

- HWID - Permanently Activate Windows
- Ohook - Permanently Activate Office
- TSforge - Permanently Activate Windows/ESU/Office

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- COMMUNITY PICK -->

## Community Pick

<!-- | Tool Name | Descriptive noun | [Download Tool Name][tool-name] | -->

| Name | Description | Download |
| ---- | ----------- | -------- |
| Grml | Linux live-system for rescue and generic purposes | [Download Grml][grml] |
|      |             |          |

<!-- ROADMAP -->

## Roadmap

See [open issues](https://github.com/fathulfahmy/aio-usb-drive/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

Don't forget to give the project a star! Thanks again!

1. Fork the project
2. Create your feature branch (`git checkout -b feat/amazing-feature`)
3. Commit your changes (`git commit -m 'feat: add some amazing feature'`)
4. Push to the branch (`git push origin feat/amazing-feature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Top contributors

<a href="https://github.com/fathulfahmy/aio-usb-drive/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=fathulfahmy/aio-usb-drive" alt="contrib.rocks image" />
</a>

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

Fathul Fahmy - [@fathulfahmy](https://linkedin.com/in/fathulfahmy) - fathulfahmy@protonmail.com

Project Link: https://github.com/fathulfahmy/aio-usb-drive

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

- [SystemRescue](https://www.system-rescue.org/)
- [Rescuezilla](https://rescuezilla.com/)
- [Netboot.xyz](http://netboot.xyz/)
- [Debian Project](https://www.debian.org/)
- [Ubuntu Project](http://ubuntu.com/)
- [Fedora Project](https://fedoraproject.org/)
- [Arch Linux Project](https://archlinux.org/)
- [Hiren's BootCD PE](https://www.hirensbootcd.org/)
- [MASSGRAVE](https://massgrave.dev/)
- [Best README Template](https://github.com/othneildrew/Best-README-Template)
- [Grml](https://grml.org/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/fathulfahmy/aio-usb-drive.svg?style=for-the-badge
[contributors-url]: https://github.com/fathulfahmy/aio-usb-drive/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/fathulfahmy/aio-usb-drive.svg?style=for-the-badge
[forks-url]: https://github.com/fathulfahmy/aio-usb-drive/network/members
[stars-shield]: https://img.shields.io/github/stars/fathulfahmy/aio-usb-drive.svg?style=for-the-badge
[stars-url]: https://github.com/fathulfahmy/aio-usb-drive/stargazers
[issues-shield]: https://img.shields.io/github/issues/fathulfahmy/aio-usb-drive.svg?style=for-the-badge
[issues-url]: https://github.com/fathulfahmy/aio-usb-drive/issues
[license-shield]: https://img.shields.io/github/license/fathulfahmy/aio-usb-drive.svg?style=for-the-badge
[license-url]: https://github.com/fathulfahmy/aio-usb-drive/blob/master/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/fathulfahmy
[product-screenshot]: image.png
[ventoy]: https://www.ventoy.net/en/download.html
[system-rescue]: https://www.system-rescue.org/Download/
[rescuezilla]: https://rescuezilla.com/download
[netbootxyz]: https://netboot.xyz/downloads/
[debian]: https://cdimage.debian.org/debian-cd/
[ubuntu]: https://ubuntu.com/download/desktop
[fedora-linux]: https://fedoraproject.org/workstation/download
[arch-linux]: https://archlinux.org/download/#http-downloads
[hirens-bootcd-pe]: https://www.hirensbootcd.org/download/
[windows11]: https://www.microsoft.com/en-us/software-download/windows11
[office365]: https://gravesoft.dev/office_c2r_links
[massgrave]: https://massgrave.dev/
[grml]: https://grml.org/download/

<!-- COMMUNITY PICK DOWNLOAD URL -->

<!-- [tool-name]: https://website.com/download -->

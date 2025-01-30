> [!CAUTION]
> ~~Dev Home will be going away in May 2025 and a subset of its features will be moved to new places. Stay tuned for more information in the following months.~~
> 
> Dev Home is **not**, like you might think it is, going into the signature Microsoft Graveyard™ - instead, it is being brought back from the dead in this repository, in an awesome collaboration with the [Windows App Community](https://dsc.gg/uwpc).
> Stay tuned for more information!

![Dev Home banner](https://github.com/user-attachments/assets/0413bc83-8764-4050-ae2e-e92bd821e041)

Dev Home is a new experience from Microsoft aiming to give developers more power on Windows.
It contains multiple powerful tools to give developers on Windows the best experience.

Microsoft [officially announced](https://github.com/microsoft/devhome/pull/4028) they would be deprecating Dev Home on the 27th of January 2025.
Just a couple days later, this repo was made and work continuing Dev Home began immediately.
Any contribution is welcome, and please provide feedback!

## Installing Dev Home

> [!NOTE]
> Dev Home requires Windows 11 version 21H2 (build 22000) or Windows 10 version 22H2 (build 19045) or newer.
> ~~If you are running Windows 11 23H2 (build 22621.2361) or later, you can install and run Dev Home just by finding it in the Start menu.~~

You can install [Dev Home from the Microsoft Store](https://aka.ms/devhome).
For users who are unable to install Dev Home from the Microsoft Store, released builds can be manually downloaded from this repository's [Releases page](https://github.com/microsoft/devhome/releases).

> The "new" Dev Home - included in this repo, is not yet available on the Microsoft Store.
> You can download the more modern version of Dev Home from GitHub Releases.

You can also install Dev Home via [`winget`](https://github.com/microsoft/winget-cli) by installing the `Microsoft.DevHome` package:

```powershell
winget install --id Microsoft.DevHome -e
```

<!--
## Dev Home overview

Please take a few minutes to review the overview below before diving into the code:

### Dashboard

The Dev Home dashboard displays Windows widgets. These widgets are built using the Windows widget platform, which relies on Adaptive Cards.

### Machine configuration

The machine configuration tool utilizes the Dev Home GitHub Extension, but isn't required to clone and install apps. The app installation tool is powered by winget.

#### Popular apps

The machine configuration tool provides a list of popular apps when selecting applications to install. This is currently a hard-coded list of applications that have been popular with developers on Windows. Popularity was determined by high levels of installation and usage. As this is a moment in time, we are not accepting submissions for this list. We're looking to improve the experience with [Suggested Apps](https://github.com/microsoft/devhome/issues/375) so the list can be optimized for developers.
-->

## Contributing to Dev Home

Want to contribute to this project? Let us know with an [issue](https://github.com/Lamparter/Dev-Home/issues) that communicates your intent to create a [pull request](https://github.com/Lamparter/Dev-Home/pulls). Also, view our [contributing guidelines](https://github.com/Lamparter/Dev-Home/blob/main/CONTRIBUTING.md) to make sure you're up to date on the coding conventions.

Looking for a place to start? Check out the [task board](https://github.com/users/Lamparter/projects/5/views/3), where you can sort tasks by size and priority.

<!--
## Code of conduct

We welcome contributions and suggestions. Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft trademarks or logos is subject to and must follow [Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general). Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship. Any use of third-party trademarks or logos is subject to those third-parties' policies.
-->

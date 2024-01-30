# ![Triceratops Icon](/triceratops.png) [Chartreuse](https://encycolorpedia.com/7fff00) Triceratops

[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0) [![Tests Badge](https://github.com/coborski/chartreuse-triceratops/actions/workflows/ci.yml/badge.svg)](https://github.com/coborski/chartreuse-triceratops/actions/workflows/ci.yml) [![Excavator Badge](https://github.com/coborski/chartreuse-triceratops/actions/workflows/excavator.yml/badge.svg)](https://github.com/coborski/chartreuse-triceratops/actions/workflows/excavator.yml) [![Toy Badge](https://img.shields.io/badge/project%20type-toy-blue)](https://project-types.github.io/#toy)

## Y'all found my personal scoop bucket!

I prefer to use software that is both [free and open source](https://www.gnu.org/licenses/license-list.html) but there will be some software included in this bucket that does not meet this criteria. I've included licenses in the table below for reference.

| **Manifest Name** | **Description**                                            | **License**       | **Autoupdate** |
| :----------- | :-------------------------------------------------------------- | :---------------- | :------------- |
| droppoint    | Drag content without having to open side-by-side windows.       | GPL-3.0-or-later  | ✅            |
| chatpad-ai   | Free and open source, privacy focused, ChatGPT user-interface.  | AGPL-3.0-or-later | ❌            |
| deepgit      | Git Archaeology Tool.                                           | [NonFree ULA](https://www.syntevo.com/documents/deepgit-license.html) | ✅            |
| hoppscotch   | Open Source API Development Ecosystem.                          | AGPL-3.0-or-later | ✅            |

## How do I install these manifests?

First you'll have to have [scoop](https://scoop.sh/) installed, then you can open your [prefered command shell](https://github.com/ScoopInstaller/Scoop/wiki/Why-PowerShell) and use the following command to add this bucket:

```pwsh
scoop bucket add chartreuse-triceratops https://github.com/coborski/chartreuse-triceratops
```

To install a program using the manifest contained in this bucket use the following:

```pwsh
scoop install chartreuse-triceratops/<manifestname>
```

## Wait what's scoop?

[Scoop](https://scoop.sh/) is a command-line installer for Windows.
- [Readme](https://github.com/ScoopInstaller/Scoop?tab=readme-ov-file)
- [Guide](https://scoop.netlify.app/guide/)


## Known issues / TODOs

- [] Most of the manifests do not include hashes
- [] The chatpad-ai manifest does not have the autoupdate property defined
- [] The chatpad-ai manifest does not delete the program's default uninstaller post install


## View source

[![cOborski - generic-project-template](https://img.shields.io/static/v1?label=cOborski&message=chartreuse-triceratops&color=green&logo=github)](https://github.com/coborski/chartreuse-triceratops/)


## Credits and references

- [Scoop](https://scoop.sh/)
- [CFPB Open Source Project Template](https://github.com/cfpb/open-source-project-template)
- [scoop-aoks](https://github.com/AntonOks/scoop-aoks)
- [Shields.io](https://shields.io/)
- https://www.flaticon.com/packs/dinosaur

[🔝](#chartreuse-triceratops)

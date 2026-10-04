<img src="icon.png" alt="YHDE logo" width="96">

# YHDE for Godot

Real-time collaboration for the Godot editor. Your whole team works in the same project at the same time: scene edits, properties, scripts and files show up for everyone as they happen, with live cursors and no merge conflicts.

This repository holds only the add-on, ready to install. The source code of the add-on, its native core and the server is in [YhdeDevelopmentOrganization/yhde](https://github.com/YhdeDevelopmentOrganization/yhde), and every release is also on its [releases page](https://github.com/YhdeDevelopmentOrganization/yhde/releases).

Website and docs: https://yhde.frostinteractive.fi

## Features

- Live sync of scenes, node properties, scripts, shaders, TileSets and project files
- Everyone's cursors, selections and drags in the 2D and 3D views
- Shared script editing with other people's carets
- Comments pinned to nodes in the 2D and 3D views
- Chat, direct messages and @mentions inside the editor
- Follow a teammate's view, or bring everyone to yours
- Files from teammates that can run code on your computer wait until you accept them

## Requirements

- Godot 4.7 or newer
- Windows, macOS or Linux (x86_64; macOS also Apple silicon)
- A YHDE account on YHDE's server, or on a server you or your team run yourselves

## Install

1. In Godot, open the **AssetLib** tab and search for YHDE, or download this repository's zip and copy the `addons/yhde` folder into your project's `addons` folder.
2. Open **Project > Project Settings > Plugins** and enable **YHDE**.
3. Open the YHDE dock, sign in, and pick or create a project.

Teammates install the add-on the same way and join with their own account.

## Getting help

- Getting started guide: https://yhde.frostinteractive.fi/docs
- Running your own server: https://github.com/YhdeDevelopmentOrganization/yhde/blob/main/docs/setup_your_server.md
- Contact: https://yhde.frostinteractive.fi/contact

## License

See [LICENSE.md](LICENSE.md): the add-on's scripts are MIT, its native libraries are GNU AGPL v3.

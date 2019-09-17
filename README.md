# Virtual Exhibitions

Virtual Reality Exhibitions with HTC Vive and Unity3d.
This is the front-end repository. For the back-end see https://github.com/dbisUnibas/virtual-exhibition-manager

Please see the [wiki](https://github.com/dbisUnibas/virtual-exhibition-presenter/wiki) for further information or consider reading the [Getting Started](https://github.com/VIRTUE-DBIS/virtual-exhibition-presenter/wiki/Setup-Guide) guide, if you want to setup your own virtual exhibition

## Vision

The goal is to create a customisable
virtual exhibition space.

### Core Features

 * Virtual 3D world with positioned art objects
 * freely movable character / player
 * Generic: Support for multiple / interchangeable exhibitions
 * Interface / communication between back-end (exhibition provider) and front-end (3D world)

## Unity

**GIT & Unity**:
In Unity set meta files to be visible and textual via:

 * `Edit > Project Settings > Editor`
 1. Set `Version Control Mode` to `Visible Meta Files`
 2. Set `Asset Serialization Mode`to `Force Text`
 
These steps are taken from https://stackoverflow.com/a/18225479

 
## Getting Started

These

To start working on the project

 0. Have a HTC Vive / SteamVR setup. For the installation process, see the [manual](https://support.steampowered.com/steamvr/HTC_Vive/)
 1. Start Unity3d
 2. On the start screen click the `Open` button
 3. Select this repository
 4. Get yourself the [backend](https://github.com/dbisUnibas/virtual-exhibition-manager)
 5. Start the backend
 6. Feed the backend with an exhibition
 7. Adopt the exhibition id within unity. Click on the `VirtualExhibitionManager` game object in the hierarchy window and set the `Exhitibion Id` to your id.
 8. Start the incredible immersive experience of having an exhibition at your place
 
## Contributors

 * Ralph Gasser
 * Ivan Giangreco
 * Silvan Heller
 * Mahnaz Parian
 * Loris Sauter
 * Florian Spiess

---

This piece of software originates from the [4th Swiss Open Cultural Data Hackathon](http://make.opendata.ch/wiki/event:2018-10). Read more about our project on the [Opendata Wiki](http://make.opendata.ch/wiki/project:virtual_3d_exhibition).

<h1><img height="24" src="https://cdn.technicpack.net/platform2/pack-icons/1721721.png"/> EV.INFINITY</h1>

[![](https://img.shields.io/badge/ON-TECHNICPACK.NET-cyan?style=for-the-badge)](https://www.technicpack.net/modpack/evinfinity)

## General Information

Evolved Infinity is a Minecraft modpack based on Minecraft 1.12.2. It contains a wide spreaded selection of mods, but with a certain style of gameplay in mind. It is heavily focused around industrialization and world manipulation, enhanced by magic-tech mods like Botania. A selection of performance increasing mods ensure a smooth and stable playthrough, while handling this huge chunk of mods in one pack.

## What is this Repository for?

This repository has two main purposes:

First of all, this repository holds all binary files, configurations and assets of the modpack. This makes it way easier to maintain the modpack, pushing new versions and backuping old versions of the modpack.

Also, we are using [GitHub Actions](https://github.com/evolvedpacks/pack-client-evolved-infinity/actions) to build and deploy releases of the modpack. Everytime a new version is created by setting a new [tag](https://github.com/evolvedpacks/pack-client-evolved-infinity/tags), a CD *([Continous Deployment](https://en.wikipedia.org/wiki/Continuous_deployment))* process is started which creates a release zip bundle of the modpack, creates a [Release](https://github.com/evolvedpacks/pack-client-evolved-infinity/releases) in this repository where the zip bundle can then be downloaded from, and pushes the latest bundle to a CDN file server which then is utilized by technicpack.net to download the modpack bundle via the technic launcher. And all of this happens fully automatically without having to lift a finger.

If you are interested in how all of this is configured, take a look in the [workflow configuration file](https://github.com/evolvedpacks/pack-client-evolved-infinity/blob/master/.github/workflows/cd-tags.yml) where all job steps are specified in.


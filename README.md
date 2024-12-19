# Collaborative Stream Control

- [Collaborative Stream Control](#collaborative-stream-control)
  - [Remote access to Blackmagic devices](#remote-access-to-blackmagic-devices)
    - [Zerotier](#zerotier)
    - [Nomachine](#nomachine)
    - [Other](#other)

## Remote access to Blackmagic devices

All required software installs and configurations for a full remote access to the machine with Blackmagic
devices connected.

### Zerotier

This is a software that'll mainly be used for a Local Network imitation in a form of a VPN.

Both of us will have this software installed and both of us will be in the same network - `6ab565387abb013e`.

We'll have a bidirectional connection for any needs of this project.

**Installation:**

Downloads are available [here](https://www.zerotier.com/download/). 

It supports almost any devices possible.

**Configuration:**

You can join the network either with a GUI, if the app for your platform provides it,
or with a CLI

GUI manuals: [MacOS](https://docs.zerotier.com/start#join-your-first-zerotier-network)

CLI command: `zerotier-cli join 6ab565387abb013e` run as root most likely.

### Nomachine

This is a software that grants remote control of the whole machine.

It allows for control over mouse, keyboard, any any other connected device. Screen sharing is the main feature we'll be using it.

Zerotier installed previously is needed for an easier connection to a Nomachine node.

**Installation and configuration:**

MacOS has a lot of Privacy features that limit the access Nomachine (and subsequently me) has over your machine.
To disable them there's a guide with all required Accessability and Privacy features. Some of them are not needed (like microphone access),
but I'm not sure how it will act when only some of the featrues are not enabled, so if it's okay with, I'd ask you to enable everything.

Downloads are available [here](https://downloads.nomachine.com/)

[MacOS configuration manual](https://kb.nomachine.com/AR11Q01061)

### Other

With all previous software installed, even if I'd need anything else, I believe I'll be able to do it without disturbing you.
Of course I'll notify you in case such a need would occur.

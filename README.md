![Wide but short logo for Morpheus](https://github.com/MorpheusAIs/Morpheus/assets/1563345/be0c5a0f-0766-4e31-8e4a-ab18cd211961)

# Morpheus
## A Network For Powering Smart Agents
### Authored by Morpheus, Trinity, & Neo
Published - September 2nd 2023

---------
**Morpheus Version 0.0.5 for Mac**
- Download from Google Drive: https://drive.google.com/file/d/1x-wR4HWjKqT_g6VRjrWPXu3rVm9ukOc9/view?usp=sharing
- SHA 256 hash for validation: 9092d543023fb95086cf4a7039d42cbcbbdf5283d670c4de6396b3d89e57b064
- Version: Morpheus-0.0.5-x64.dmg

---------
**Morpheus Version 0.0.5 for Linux Debian**
- Download: https://drive.google.com/file/d/1PQ3n7LXeJHe_jmkYLDUQ9fWjZQTWbHCB/view?usp=sharing
- Instructions: To install, run this command: `sudo dpkg -i /path/to/your/morpheus.deb`

**NOTE:** In the above command, replace "/path/to/your/morpheus.deb" with your path to the morpheus_0.0.5_amd64.deb file.
- SHA Hash for Verifiction:
b227e7bcb21ec9e8e2b4bf9510a2e1f224953fe5
- Version: morpheus_0.0.5_amd64.deb

Morpheus Linux Debian Guide:
https://docs.google.com/document/d/1PLRxWIKppNHIy461ZeHHP1Lz6ZC7rcbSRyD7SJCkyKg/edit#heading=h.85k2a53a2as

---------
**Installing Morpheus Version 0.0.5 on Windows**

- First, install WSL2, you can do that by running `wsl  --install` on an admin command prompt. Then open WSL2 with `wsl` and follow the setup process.
- Then run `curl https://ollama.ai/install.sh | sh` to install ollama.
- Then install python by doing `sudo apt-get update` and `sudo apt-get install python3`.
- Then run `pip3 install gdown`.
- Now download the morpheus dpkg by running `gdown https://drive.google.com/uc?id=1PQ3n7LXeJHe_jmkYLDUQ9fWjZQTWbHCB`.
- Verify the integrity of the Morpheus download by `sha1sum morpheus_0.0.5_amd64.deb`. make sure it matches the hash `b227e7bcb21ec9e8e2b4bf9510a2e1f224953fe5`, otherwise abort the installation process.
- Then run `sudo dpkg -i morpheus_0.0.5_amd64.deb`, if the installation fails at first, install the dependencies, and try again.
- Now once you have morpheus installed without any dependency errors, open 2 WSL2 windows by opening 2 commandline windows and typing wsl on both of them, then on one of them run `ollama serve` and on the other run `morpheus`.

---------
## Introduction 
Introducing **Morpheus**, your personal AI companion, designed to be more intimately acquainted with you than anyone else, operating directly from your computer with unparalleled security and dedication. This is no ordinary tool; it's an extension of your intellect, a trusted advisor capable of engaging in deep, meaningful dialogues, understanding your needs, aspirations, and preferences with a precision beyond human capability. Morpheus stands as a beacon of privacy and autonomy, ensuring your interactions are free from external agendas and solely focused on your benefit.

This groundbreaking innovation marks the dawn of a new era in decentralized, peer-to-peer technology, seamlessly integrating Large Language Models and AI into your digital life with a level of personalization never seen before. Morpheus not only responds to your queries and tasks but also anticipates your needs, all the while championing the principle that your data is yours alone.

Envision a future where each individual is empowered by a personal AI agent - a powerful ally that amplifies your abilities, offers advice, and makes decisions, all while knowing you better than you know yourself. In this future, AI agents, like Morpheus, are not tools of surveillance for the government or corporations but are instead dedicated to serving the people, ensuring AI remains decentralized and in the hands of those it serves.

Morpheus bridges the gap between advanced AI and your digital ecosystem, including wallets, decentralized applications, and smart contracts, making sophisticated technology accessible and personal. This transformation is as significant as the advent of search engines, making technology effortlessly intuitive and universally accessible.

To realize this vision of a personalized, trust-centric AI, we propose a decentralized network backed by a fairly launched token, rewarding every key contributor: users, developers, financial backers, and those providing computing resources. Inspired by the successes of Bitcoin and Ethereum, we advocate for a competitive yet collaborative ecosystem where digital tokens fuel a sustainable, robust blockchain infrastructure, empowering users with a truly personal AI companion that champions their autonomy and privacy. **Welcome to the era of Morpheus, where technology serves humanity like never before.**

## Key documents list:
- [White Paper](https://github.com/MorpheusAIs/Docs/blob/main/!KEYDOCS%20README%20FIRST!/WhitePaper.md)
- [Yellow Paper](https://github.com/MorpheusAIs/Docs/blob/main/!KEYDOCS%20README%20FIRST!/YellowPaper.md)
- [Yellowstone Compute Model](https://github.com/MorpheusAIs/Docs/blob/main/!KEYDOCS%20README%20FIRST!/Yellowstone%20Compute%20Model.md)
- [Techno Capital Machine](https://github.com/MorpheusAIs/Docs/blob/main/!KEYDOCS%20README%20FIRST!/TechnoCapitalMachineTCM.md)
- [Fair Launch](https://github.com/MorpheusAIs/Docs/blob/main/!KEYDOCS%20README%20FIRST!/Fair%20Launch.md)
- [Fair Price Discovery](https://github.com/MorpheusAIs/Docs/blob/main/!KEYDOCS%20README%20FIRST!/Fair%20Price%20Discovery.md)
- [TestingPlan](https://github.com/MorpheusAIs/Docs/blob/main/!KEYDOCS%20README%20FIRST!/TestingPlan.md)
- [Mastery of Tokenomics](https://github.com/MorpheusAIs/Docs/blob/main/!KEYDOCS%20README%20FIRST!/Mastery%20of%20Tokenomics.md)
- [Morpheus Meetup Guide](https://github.com/MorpheusAIs/Docs/blob/main/!KEYDOCS%20README%20FIRST!/Morpheus%20Meetup%20Guide.md)
- [FAQs](https://github.com/MorpheusAIs/Docs/blob/main/!KEYDOCS%20README%20FIRST!/FAQs.md)

## Code:
-	Morpheus Local Install: https://github.com/MorpheusAIs/Node
-	Smart Contracts: https://github.com/morlabs/SmartContracts
-	Frontend Dashboard: https://github.com/morlabs/DashBoard
- Technical Documentation https://github.com/morlabs/Docs

## Morpheus Network Diagram
![DiagramupdatedwithstETH](https://github.com/MorpheusAIs/Morpheus/assets/1563345/31711e49-0b57-4b41-b231-ee673dbf6664)

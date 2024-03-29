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
**Introducing Morpheus:** a revolutionary leap in AI technology that goes beyond the concept of a single AI companion to a comprehensive ecosystem of personalized AI Agents, peer to peer, open source and each designed to serve a distinct purpose tailored to your unique needs and aspirations. Morpheus is not just about having an AI companion; it's about creating a network of AI Agents, each specialized to enhance different aspects of your life and work.

Imagine deploying an AI Agent dedicated to autonomously seeking new clients, creating a stream of income while you sleep, or even developing an AI Agent so secure it interacts solely with your computer's information, safeguarding your most confidential data. These scenarios are just the beginning of what Morpheus enables.

Further envision an AI Agent, akin to a highly intelligent anti-spam filter for your life, standing guard to intercept and filter the barrage of information directed at you daily. This AI would not only protect your mental space from unnecessary noise but also ensure that the content you consume enriches your mind, akin to how a balanced diet nourishes your body. In this way, Morpheus acknowledges the profound truth that your body is what you eat, and your mind is what it's prompted with, offering a layer of protection and curation that keeps your mental well-being at the forefront.

Once you deploy a "Working" AI Agent on the blockchain, your AI Agents can collaborate with those developed by others on ambitious, complex projects. Imagine a network of AI Agents coming together to tackle global challenges, such as a coordinated response to a new health crisis, demonstrating Morpheus's capability to mobilize collective intelligence for the greater good.

With Morpheus, you hold the reins. You decide the functions of your AI Agent, ensuring it aligns with your personal and professional objectives. The Morpheus DAO (Decentralized Autonomous Organization) oversees this network of AI Agents, ensuring they add value to both the network and humanity while maintaining a focus on ethical standards and privacy.

Morpheus redefines the relationship between technology and the individual. It heralds a new era where AI serves not just as a tool but as a partner and protector, enhancing human potential while safeguarding mental space against the clutter of the digital age. Welcome to the future with Morpheus, where technology serves humanity in ways that truly matter, fostering a healthier, more focused mind and a world where collective intelligence addresses our greatest challenges.

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

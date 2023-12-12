# VR-Project - Panoramas On The Modern Web

This repository aims to be a Concept of integration of VR Panoramas into [A-FRAME](https://aframe.io/) *[https://aframe.io/]* - A web framework for building virtual reality experiences

> [!NOTE]  
> This branch is a remake of the legacy version made with marzinano, a discontinued 360 web viewer for the modern web.

## Showcase
A POC (Proof Of Concept) is available on the repository's page. [click me](https://error-cezar.github.io/VR-Project/) *[https://error-cezar.github.io/VR-Project/]*

## Building
To build this application:
- Clone the repository
- **Host the cloned repository on a local / external server** - *[DIRECT EXECUTION WONT WORK]*
- Open the server itself


## Contributors
[![](https://contrib.rocks/image?repo=Error-Cezar/VR-Project)](https://github.com/Error-Cezar/VR-Project/graphs/contributors)



# Find my clues - An introduction to information security risks in an office environment

Goal: Create a game to introduce the player to basic information security risks in an office environment

Type of game : Find the clues, with complementary pedagogical elements for each element identified

Logic : 
- In a full 3D environment, representing an office, the player must click on elements that represent information security risks
- Duration for the game is set to 1 minute
- Everytime a clue is found, the game displays an information screen describing the risk and remediations options
- Timer is paused everytime a description of the nature of the security risk is shown

Clues to find:
- A computer is unlocked (risk: Geopardize local and network environmnents | Remediation : Control-Alt-Delete)
- A post-it with password written on it next to the computer screen (risk: Compromission | Remediation: keep passwords personal & secret)
- A paper with a "confidential" header is printed in the printer (risk: information leak | Remediation: Lock files)
- A USB Key is left on the desk (risk: Data loss + information leak | Remediation: Lock device)
- A smartphone is left somewhere in the office (risk: Data loss + information leak | Remediation: Lock device)
- A "confidential" folder is available on a shelve (risk: Data loss + information leak | Remediation: Lock device)
- A "confidential" paper is in the trash, wrapped as a bowl, with a paper shredder next to it. The word confidential can be seen (risk: Data loss + information leak | Remediation: Destroy device, use shredder)

Once each item is clicked the player scores 1 point. Player has access to the number of clues he is supposed to click on.


## Introduction
- This phishlet is designed for the Evilginx framework, aiming to enhance phishing campaigns against Office 365 (O365) environments. 
- It specifically targets the Windows Hello for Business authentication method, enabling an attacker to downgrade this secure authentication to more vulnerable, phishable methods. 
- In addition, this phishlet incorporates JavaScript injection techniques to hide the sign-in option for Windows Hello for Business, among other functionalities, to increase the efficacy of phishing attacks.

*Disclaimer: This tool is provided for educational purposes only. It is essential to use it ethically and legally. The developers and contributors are not responsible for misuse or for any damage that may be caused.*

## Features
- Enables downgrading Windows Hello for Business authentication to less secure methods that can be easily phished.
- Includes code to manipulate the O365 login page, specifically to hide the Windows Hello for Business sign-in option, making phishing attacks more straightforward and less detectable.

## Usage
- Ensure you have Evilginx installed and running on your system. Refer to the official Evilginx documentation for installation instructions.
- Download the O365 phishlet file from this repository.
- Move the phishlet file to the appropriate directory where your phishlets are located or where you want evilginx to load phishlets from (typically ~/.evilginx/phishlets/).

Stay tuned for the upcoming blog post.

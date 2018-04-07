# Cybersecurity-Week-7-Project-WordPress-vs.-Kali   

# Codepath Cybersecurity Week 7 Assignment

Time spent: 4.5 hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1. Authenticated Stored Cross-Site Scripting (XSS)
   ID: CVE-2015-5622
  - [ ] Summary: 
    - Vulnerability types: XSS
    - Tested in version: 4.2
    - Fixed in version: 4.2.3
  - [ ] GIF Walkthrough: <img src="https://github.com/vkril/Cybersecurity-Week-7-Project-WordPress-vs.-Kali/blob/master/XSS-1.gif" width="800">
  - [ ] Steps to recreate: The following code demonstrates the vulnerability. It should be entered in a page or posting using the HTML       edit mode (instead of the default WYSIWYG):
    [Link 1](https://klikki.fi/adv/wordpress3.html)

2. Authenticated Cross-Site Scripting (XSS) via Media File Metadata
  ID: CVE-2017-6814
  - [ ] Summary: 
    - Vulnerability types: XSS
    - Tested in version: 4.2
    - Fixed in version: 4.2.13
  - [ ] GIF Walkthrough: <img src="https://github.com/vkril/Cybersecurity-Week-7-Project-WordPress-vs.-Kali/blob/master/XSS-2.gif" width="800">
  - [ ] Steps to recreate: Upload MP3 file to the Media Library (as Editor or Administrator) and Insert an Audio Playlist in a Post         containing this MP3 (Create Audio
    Playlist).
    [Link 1](http://seclists.org/oss-sec/2017/q1/563)
  
3. Large File Upload Error XSS
   ID: CVE-2017-9061
  - [ ] Summary: 
    - Vulnerability types: XSS
    - Tested in version: 4.2
    - Fixed in version: 4.2.15
  - [ ] GIF Walkthrough: <img src="https://github.com/vkril/Cybersecurity-Week-7-Project-WordPress-vs.-Kali/blob/master/XSS-3.gif" width="800">
  - [ ] Steps to recreate: An attacker can inject a malicious script in to the filename which a victim tries to upload leading to XSS       inside the administrators control panel.
    [Link 1](https://hackerone.com/reports/203515)
 


## Assets

No additional files for this lab.

## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

For Attack 1:
  No challenges.
  
For Attack 2:
  No challenges.
  
For Attack 3:
  No challenges
 

## License

    Copyright [2018] [Vitaliy Kril]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

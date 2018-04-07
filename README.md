# Cybersecurity-Week-7-Project-WordPress-vs.-Kali   

# Project 7 - WordPress Pentesting

Time spent: 4.5 hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1. Authenticated Stored Cross-Site Scripting (XSS)
  - [ ] Summary: 
    - Vulnerability types: XSS
    - Tested in version: 4.2
    - Fixed in version: 4.2.3
  - [ ] GIF Walkthrough: <img src="https://github.com/vkril/Cybersecurity-Week-7-Project-WordPress-vs.-Kali/blob/master/XSS-1.gif" width="800">
  - [ ] Steps to recreate: https://klikki.fi/adv/wordpress3.html

2. Authenticated Cross-Site Scripting (XSS) via Media File Metadata
  - [ ] Summary: 
    - Vulnerability types: XSS
    - Tested in version: 4.2
    - Fixed in version: 4.2.13
  - [ ] GIF Walkthrough: <img src="https://github.com/vkril/Cybersecurity-Week-7-Project-WordPress-vs.-Kali/blob/master/XSS-2.gif" width="800">
  - [ ] Steps to recreate: http://seclists.org/oss-sec/2017/q1/563
  
1. Large File Upload Error XSS
  - [ ] Summary: 
    - Vulnerability types: XSS
    - Tested in version: 4.2
    - Fixed in version: 4.2.15
  - [ ] GIF Walkthrough: <img src="https://github.com/vkril/Cybersecurity-Week-7-Project-WordPress-vs.-Kali/blob/master/XSS-3.gif" width="800">
  - [ ] Steps to recreate: https://hackerone.com/reports/203515
 


## Assets

List any additional assets, such as scripts or files

## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while doing the work

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

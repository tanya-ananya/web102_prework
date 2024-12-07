# WEB102 Prework - *SeaMonster Crowdfunding*

Submitted by: **Taaruni Ananya**

**SeaMonster Crowdfunding** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **12~** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] The introduction section explains the background of the company and how many games remain unfunded.
* [x] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [x] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [x] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [x] Changed colors to make page more appealing
* [x] Increased main content's margin, to keep content from sticking to edges of the pages

## Video Walkthrough

Here's a walkthrough of implemented features:

https://github.com/user-attachments/assets/07441720-c7d6-4913-a1ec-262d2022cc0f

## Notes

Challenges: I struggled to get the images to load. After doing research, I implemented a parser for the JSON in games.js but this action led to all interaction being ignored. I tried asking AI but reached the same conclusion. After a few days of debugging, I tried going thorugh index.js and found the issue in the addGamesToPage function. The issue was due to a mismatch between the property name used in the JavaScript code and the JSON data structure. In the GAMES_JSON data, the image path is stored in the property img, but in the addGamesToPage function, I was trying to access it as game.image. I changed the values and was able to make the images visible again.

## License

    Copyright 2024 Taaruni Ananya

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

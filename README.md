# WEB102 Prework - Sea Monster Crowdfunding

Submitted by: Brandon Koeck

Sea Monster Crowdfunding is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: 7 hours spent in total

## Required Features

The following **required** functionality is completed:

* [X] The introduction section explains the background of the company and how many games remain unfunded.
* [X] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [X] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [X] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [X] Adjusted font in styles.css
* [X] Added a "more info" feature when clicking game cards

## Video Walkthrough

Here's a walkthrough of implemented features:

<img src='https://i.imgur.com/sYOnDrJ.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](https://www.cockos.com/licecap/) for Windows

## Notes

Here are some of the challenges I faced:  

Template literal syntax confusion - I struggled with understanding when to use backticks or quotes, specifically when using ${} which only works with template literals.

Event listener scope and targeting - I had difficulty accessing loop variables like games[i] inside event listeners. I tried to add listeners to class names instead of individual elements within the loop.

Destructuring and accessing object properties - I attempted to display entire game objects instead of accessing specific properties like games[i].name. This printed [object Object] being instead of actual info.

## License

    Copyright [2025] [Brandon Koeck]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

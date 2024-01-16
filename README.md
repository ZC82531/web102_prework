# WEB102 Prework - Crowdfund Showcase

Submitted by: Zakaria Chowdhury

Crowdfund Showcase is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: 4 hours spent in total

## Required Features

The following **required** functionality is completed:

* [✓] The introduction section explains the background of the company and how many games remain unfunded.
* [✓] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [✓] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [✓] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [✓] List anything else that you can get done to improve the app functionality!
- I added a feature to first sort by backers in ascending order, then use functinos to filter from sorted ones and append them to the page. I kept the original buttons though I could have merged it to maintain the old work, then created another div to put the alternate buttons below.

## Video Walkthrough

Here's a walkthrough of implemented features:

[![](https://i.imgur.com/ao0IXAM.png)](https://i.imgur.com/ao0IXAM.mp4)
- I used Markdown language in the README file to embed a video through research.

Video created with Mac Screenshot Application
<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

- One challenge I faced was with filtering the cards properly upon each click since some unwanted cards could be left. To resolve this, I removed all the cards then used the appropriate filter function to append cards again to the page.
- Another challenge I faced was displaying the cards properly when inserting HTML, but this required some trial and error to have it display on the page properly with the appropriate data from the JSON file.

## License

    Copyright 2024 Zakaria Chowdhury

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

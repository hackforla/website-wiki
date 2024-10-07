---
title: Using a forked repo's GitHub Pages to view the website
tags:
    - 'decision record'
    - 'not implemented'
    - 'role: dev'
---

#### Issue

[#6219](https://github.com/hackforla/website/issues/6219)

#### Problem Statement

Some developers are unable to use Docker to view code changes.

#### Potential Solution

Provide instructions for how to view code changes to the website through a forked repository (repo) using GitHub Pages so that developers unable to use Docker can have another option.

#### Feasibility Determination

We have made a decision not to do this for the following reasons:

1. We are concerned that old versions of our site will remain out on people's forked repos and could eventually show up in search results, which would lower the quality of results people get when searching for the Hack for LA (HfLA) website.

2. It's quite complicated to follow the instructions and requires the Merge Team to support people who don't understand the instructions, thus increasing the burden on the Merge Team.

3. We had thought we needed it for work on the Wins page's Google Apps Script to test and see the visual changes on the website. However, for testing, a team member can initiate a commit to their own forked repo of the website in their copy of the Google Apps Script, and then pull down the site from their own forked repo and see it using Docker.

#### Sources

[GitHub Pages](https://pages.github.com/)
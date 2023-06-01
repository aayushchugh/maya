<div align="center">
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-0-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
<img alt="logo" height="300" width="300" src="./logos/full.svg" />
</div>
App to manage your pocket money and keep track of your expenses and account between multiple people

## Features

### Current release (v1.0.0) 🏃

- Track expense between multiple people
- Day start and day end cash in hand
- Debit/credit system (if someone asks for some money, than you can put that to your account as well)
- Automatic calculation of total amount of money in hand

- Group:
  - you can remove people of group from a particular entry if they are not involved in that entry
  - Create groups and add people to it
  - when creating a new entry with group, app will automatically add the users in group to that entry
  - when new person is added to the group, he/she will be only added when he accepts the invite
  - on leaving the group, group admin will approve first that he can leave the group
- between 2 people:
  - when a person is creating a entry that he paid to another person than the other person will be notified and he can accept or reject the entry, weather he is paid or not

### Future releases 🚀

- You can set daily budget and app will notify you when you are going to exceed your budget
- show average daily spend
- Manage budget of trips
  (if you are going to a trip with your friends than you can create a new trip and add people to it.
  each person can add their budget for the trip and you will see that. you can plan your trips according to your budget and while spending on the trip you can also keep record of who spent how much and also see how much money is left. and remaining money can be divider among the people who are in the trip).
- Auto adjust money between people (if 2 people are together and one person spent 30rs one time and another spend 20 next time than app will automatically adjust that only 10rs is left to be paid by the person who spend 20rs)

## Docs

All the docs for each project are present in their respective directories in `docs` folder

## UI Design

[Figma URL](https://www.figma.com/file/ojtvKg3GqfcWxfQh8CPBFO/Maya?type=design&t=YiQRFjTrCGUL18Ic-1)

## Color Reference

| Color      | Hex                                                              |
| ---------- | ---------------------------------------------------------------- |
| Primary    | ![#2C6871](https://via.placeholder.com/10/2C6871?text=+) #2C6871 |
| Accent     | ![#8FFFA8](https://via.placeholder.com/10/8FFFA8?text=+) #8FFFA8 |
| Grey       | ![#B0BBC4](https://via.placeholder.com/10/B0BBC4?text=+) #B0BBC4 |
| Grey light | ![#CBD2D8](https://via.placeholder.com/10/CBD2D8?text=+) #CBD2D8 |

## [Database design](https://tinyurl.com/2cz8mf74)

> :warning:
> This database design is will be updated in future based on different needs

![db design](server/docs/db/db-design.svg)

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
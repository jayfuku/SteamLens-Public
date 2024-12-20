![SteamPeek Banner](./resources/1400x560%20Marquee%20Promo%20Tile.png)

# SteamPeek-Public

Repository for public releases of SteamPeek, an extension designed to help streamline the experience of finding out about the games you want to play next.

Powered by: ![](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white) ![](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white) ![](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E) ![](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue) ![](https://img.shields.io/badge/Express%20js-000000?style=for-the-badge&logo=express&logoColor=white)

Made for: ![](https://img.shields.io/badge/Google_chrome-4285F4?style=for-the-badge&logo=Google-chrome&logoColor=white)

# ❓ What is SteamPeek?

<img src="./resources/logo128.png" align="right" width="128" height="128">

SteamPeek is a Chrome extension designed to help streamline the experience of search for information about the next games you want to play. This extension will allow you to quickly view information from various sources in one place.

No new tabs, no hassle.

https://chrome.google.com/webstore/detail/dlkmkiiccmmfjoodngomfndmfilhblhe

# 🌟Features

## Manual Search

Open SteamPeek from the extension bar and type into the search field to get results.

![SteamPeek Screenshot 1](./resources/Screenshot%201_%20Initial%20promo.png)

## SmartSearch

On supported websites and contexts, open SteamPeek from the extension bar to automatically begin a search based on the content of the page.

![SteamPeek Screenshot 2](./resources/Screenshot%202_%20Smart%20Search.png)

Currently available on Youtube with support for more sites to come in the future!

# ℹ Available sources of information

-   IGDB Ratings
    -   Critic ratings
    -   User ratings
    -   Total ratings
-   IGDB Completion Times
    -   Main completion time
    -   Main+Sides completion time
    -   Completionist time
-   ProtonDB
    -   Linux compatibility rating

With more to come in the future!

# ⚙ Installation & Usage

## Install From Chome Web Store
- Head to the [Chrome Web Store listing for SteamPeek](https://chrome.google.com/webstore/detail/dlkmkiiccmmfjoodngomfndmfilhblhe)
- Hit the "Add to Chrome" button

## Install Unpacked
> [!CAUTION]
> **Before Proceeding**: Enabling developer mode to load unpacked extensions can be dangerous since Chrome seems to be more lax on security. SteamPeek will only ever do what it needs to fulfill its sole intended purpose but please be aware of the inherent risks. Install directly from the official [Chrome Web Store listing](https://chrome.google.com/webstore/detail/dlkmkiiccmmfjoodngomfndmfilhblhe) when possible

-   Get the latest version from the [releases](https://github.com/jayfuku/SteamPeek-Public/releases) available in the repo and unzip `dist.zip` or pull `/dist/` directly from a commit.
-   Navigate to `chrome://extensions/` through the address bar or through Chrome's setting menu.
    ![Navigate to Extenstion](./resources/Navigate%20to%20extension.png)
-   Enable developer mode to be able to load unpacked extensions.
    ![Enable developer mode](./resources/Enable%20developer%20mode.png)
-   Select `Load Unpacked` and, when prompted, select the `/dist/` folder you downloaded earlier.
    ![Load Unpacked](./resources/Load%20Unpacked.png)



## Usage Instructions
-   📌 Pin the extension for easy access
-   Click on the <img src="./resources/logo128.png" width="16" height="16"> logo to open the popup
-   Either perform a manual search through the field or open SteamPeek on a supported page to get automatic results.

# 💡 How it Works

## Search function

When you make a request for a search, SteamPeek sends your query to its backend services. The backend services does some magic and makes sure that the response is as accurate as possible. Under proper usage, you are guaranteed get the Steam information about the game but existence of other information (ProtonDB, IGDB) will depend on if those sites carry it.

I can't reveal too much more, sorry!

# SmartSearch

When you open SteamPeek on a supported page, it parses the HTML of that page in order to extract the name of the game that is being shown. SteamPeek will then automatically begin a search for that game for you.

# 📝Notes and Disclaimers
1. Steampeek is intended for use with games currently available on the Steam game marketplace. You may try other games but your mileage will vary.
2. If you experience slowdowns, please try waiting or closing and re-opening the extension. This is caused by the backend being slow due to budgetary issues.
3. SteamPeek is independently owned and operated and is not affiliated with, endorsed by, or associated with Valve Corporation, Steam, ProtonDB, IGDB, any individual games, their publishers, their developers, or any other platforms mentioned. All trademarks, logos, and intellectual property displayed are the property of their respective owners.

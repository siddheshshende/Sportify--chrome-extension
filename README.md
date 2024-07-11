<a name="readme-top"></a>

<div align="center">
<img style="border-radius: 5px;" src="chrome extension/favicon128128.png" alt="Sportify Logo">
</div>

<h1 align="center">Sportify <br/> <span style="font-size:10px;">A Chrome Extension for Live Cricket Scores and Sports News</span></h1>

<div align="center">
  <img src="https://img.shields.io/badge/Extension-Chrome-blue" alt="Badge">
  <img src="https://img.shields.io/badge/Cricket_Live-Updates-green" alt="Badge">
  <img src="https://img.shields.io/badge/News-Latest-orange" alt="Badge">
  <img src="https://img.shields.io/badge/LICENSE-MIT-purple" alt="Badge">
  <img src="https://img.shields.io/badge/Version-1.0-yellow" alt="Badge">
</div>

## Tech Stack and Tools
<span>
  <img src="https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/> 
  <img src="https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/javascript%20-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/chrome%20-%234285F4.svg?&style=for-the-badge&logo=googlechrome&logoColor=white" alt="Chrome"/>
    <img src="https://img.shields.io/badge/git%20-%23121011.svg?&style=for-the-badge&logo=git&logoColor=green"/> 
    <img src="https://img.shields.io/badge/github%20-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/VS%20Code-0078d7.svg?&style=for-the-badge&logo=visual-studio-code&logoColor=white"/>
</span>

- **Frontend:** HTML, CSS, JavaScript
- **Extension Platform:** Chrome
- **Version Control:** Git and GitHub.
<h3 align="center">✨ Welcome to Sportify ✨</h3>
<hr>

# Table of Contents
<details>
  <summary>Click to expand</summary>
  
  - [Overview](#overview)
  - [Screenshots](#screenshots)
  - [Features](#features)
  - [Available on Chrome Web Store](#available-on-chrome-web-store)
  - [File Structure](#file-structure)
  - [API References](#api-references)
  - [Usage](#usage)
  - [Installation](#installation)
  - [Contributing](#contributing)
  - [License](#license)
  - [Acknowledgements](#acknowledgements)
  
</details> 

## Overview
Sportify is a Chrome extension providing live cricket scores and the latest sports news. Stay updated with real-time match details and recommended sports articles.
Sportify solves the problem of continuously switching between websites or apps to stay up to date on sports news and live cricket scores. It saves time and enhances the surfing experience for sports enthusiasts by simplifying access to real-time sports information by integrating it straight into users new tab pages.
## Screenshots📸
<div align="center">
    <img src="1280.5.png" alt="Sports Articles">
  <img src="1280.1.png" alt="Live Cricket Scores thumbnail">
  <img src="1280.2.png" alt="Match Details">

</div>

## Features🌟
- Real-time updates on cricket matches.
- Comprehensive match details including scores and venues.
- Curated sports articles for enthusiasts.
- User-friendly interface for easy navigation.
- Constant updates for improved functionality.

## Available on Chrome Web Store
[Install Sportify](https://chromewebstore.google.com/detail/mgjahdmijkjbecnobbgpkldenchhfcjn)

## File Structure🗂️
- `manifest.json`: Contains the metadata and configuration for the Chrome extension.
- `index.html`: The main HTML file that serves as the new tab page.
- `style.css`: The CSS file for styling the new tab page.
- `script.js`: The JavaScript file for fetching and displaying live scores and news.
- `favicon128128.png`: The icon for the extension.

## API References
- **CricAPI:** Used to fetch live cricket scores.
  - **Endpoint:** `https://api.cricapi.com/v1/currentMatches`
  
- **TheNewsAPI:** Used to fetch the latest sports news.
  - **Endpoint:** `https://api.thenewsapi.com/v1/news/top`

## Usage💡
Once installed, Sportify will replace your new tab page with its dashboard. You can view live cricket scores and the latest sports news directly from the new tab.

- **Live Cricket Updates:** Displays current IPL match scores and details.
- **Sports News:** Shows the latest sports news articles with links to the full stories.

Install Sportify now to improve your sports browsing experience!

<p align="right">(<a href="#readme-top">back to top</a>)</p> 

## Installation
1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/sportify-chrome-extension.git
    cd sportify-chrome-extension
    ```

2. **Load the extension in Chrome**:
    - Open Chrome and navigate to `chrome://extensions/`.
    - Enable "Developer mode" using the toggle switch in the top right.
    - Click "Load unpacked" and select the `sportify-chrome-extension` directory.

## Contributing
We welcome contributions to improve Sportify! Here's how you can contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
    ```bash
    git checkout -b feature/AmazingFeature
    ```
3. Commit your changes and push to the branch:
    ```bash
    git commit -m 'Add some AmazingFeature'
    git push origin feature/AmazingFeature
    ```
4. Open a Pull Request with a detailed description of your changes.

<p align="right">(<a href="#readme-top">back to top</a>)</p> 

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- Thanks to [CricAPI](https://cricapi.com/) and [TheNewsAPI](https://thenewsapi.com/) for providing the APIs used in this extension.

<p align="right">(<a href="#readme-top">back to top</a>)</p> 
<hr>

<div align="center">
Made with ❤️ for cricket and sports enthusiasts
</div>

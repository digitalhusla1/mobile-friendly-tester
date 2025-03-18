# Mobile-Friendly Tester

## Overview
The **Mobile-Friendly Tester** is a free online tool that helps website owners check whether their website is optimized for mobile devices. This tool leverages Google's PageSpeed Insights API to analyze a webpage and determine its mobile compatibility.

## Features
- Instantly checks if a website is mobile-friendly.
- No downloads or installations required.
- Provides reasons for pass/fail results.
- Displays a scanning animation for better user experience.
- Includes a link to improve website mobile performance.

## How to Use
1. Visit the **Mobile-Friendly Tester** webpage.
2. Enter the website URL you want to test.
3. Click the "Test" button.
4. Wait for the scan to complete.
5. View the results:
   - ✅ **Pass:** Your website is mobile-friendly.
   - ❌ **Fail:** Your website is not optimized for mobile, with details on what needs improvement.
6. Click the "Improve Your Website" button to get assistance with mobile optimization.

## Installation & Hosting
You can host this tool on your own server or use GitHub Pages.

### Hosting on GitHub Pages
1. Fork this repository.
2. Go to **Settings > Pages** in your repository.
3. Under "Source," select the `main` branch and save.
4. Your site will be available at `https://yourusername.github.io/mobile-friendly-tester/`.

### Hosting on Free Web Hosting Services
You can also upload the HTML file to free hosting providers like:
- [Netlify](https://www.netlify.com/)
- [Vercel](https://vercel.com/)
- [GitHub Pages](https://pages.github.com/)

## API Integration
This tool utilizes the **Google PageSpeed Insights API** to fetch mobile compatibility data:
```js
fetch(`https://www.googleapis.com/pagespeedonline/v5/runPagespeed?url=${encodeURIComponent(url)}&strategy=mobile&key=YOUR_API_KEY`)
```
Replace `YOUR_API_KEY` with a valid Google API key.

## Issues & Contributions
Feel free to open an issue or submit a pull request if you have any suggestions or improvements.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Live Demo
Check out the live version here: [Smart Business 100 Mobile-Friendly Tester](https://smartbusiness100.com/)


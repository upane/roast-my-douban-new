# Roast My Douban


Roast your style based on interests of a Douban user.


![](./roast-my-douban.png)


---

made with 99% AI, 1% Human

## Features

- **Multiple Categories**: Books, Movies, Music, and Games
- **Two Analysis Modes**: 
  - "Roast Mode" (毒舌心热): Sharp, humorous criticism
  - "Praise Mode" (夸夸模式): Warm, insightful appreciation
- **AI-powered Analysis**: Uses various LLM providers for deep analysis
- **Local API Key Storage**: Your API keys are only stored in your browser

## How to Use

1. Enter your Douban user ID or username
2. Select an analysis mode (Roast or Praise)
3. Select an analysis category (Books, Movies, Music, or Games)
4. Enter your API Key in the settings section
5. Click "Start Analysis" to generate results

## Supported LLM Providers

- Gemini (Google)
- DeepSeek
- Qwen
- ChatGPT (OpenAI)

## Support me

You can support me by Alipay (scan QR code below) or [ko-fi](https://ko-fi.com/aerisz):

![](./support.webp)

## Changelog

### 2026-03-05 Updates

1. **New Features**:
   - **HTML Export Functionality**: Added ability to export Douban data as HTML table
   - **Query Limit Control**: Added input field to customize the maximum number of items to fetch (default: 200)
   - **Export Progress Feedback**: Added export status messages and loading state

2. **Technical Improvements**:
   - Updated `fetch-douban` API to support custom query limits
   - Added batch fetching logic for more efficient data retrieval
   - Improved error handling for export operations
   - Updated .gitignore file

### 2026-02-26 Updates

1. **UI Improvements**:
   - Updated praise mode result card design with golden and crimson color scheme
   - Changed top-left decoration from red flower to golden flower with red "奖" (Award) character
   - Updated "诊断对象 ID" (Diagnosis Object ID) to "荣光记录 ID" (Glory Record ID) for praise mode
   - Changed "确诊率" (Diagnosis Rate) to "契合度" (Compatibility Rate) for praise mode
   - Added upward arrow next to compatibility rate percentage in praise mode
   - Updated praise mode card styles: background, border, shadow, and text colors

2. **Technical Fixes**:
   - Fixed compilation errors related to Svelte template syntax
   - Improved responsive design for better mobile display

### 2026-03-06 Updates

1. **UI Improvements**:
   - Removed "ROAST MY DOUBAN 豆瓣标记精神状态分析" text from the main page
   - Added overlay text "ROAST MY DOUBAN 豆瓣标记精神状态分析" on the douban.webp image with light green color
   - Added blur effect when hovering over the douban.webp image
   - Added hover message box in the center of the image: "谢谢做这张图的豆瓣用户@mui如有侵权，请联系我删除"

### 2026-02-25 Updates

1. **UI Improvements**:
   - Renamed "Praise Mode" (夸夸模式) to "Extravagant Praise Mode" (夸夸奇谈)
   - Updated button colors: "Extravagant Praise Mode" now shows as red when active, while "Roast Mode" shows as green
   - Added viewport meta tag for better mobile device support

2. **AI Analysis Enhancements**:
   - Updated praise mode prompts to be more enthusiastic and hyperbolic
   - Improved the "Extravagant Praise Master" (夸夸奇谈大师) style with more dramatic language

3. **Technical Fixes**:
   - Fixed mobile display issues by adding proper viewport configuration
   - Explained the multiple network address display behavior in development mode

4. **User Experience**:
   - The praise mode now uses more lavish compliments and poetic exaggeration
   - Better responsive design for all screen sizes



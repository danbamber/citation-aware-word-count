# Microsoft Word Add-in for Citation-Aware Word Counting

<a href="https://wordcount.doodan.com/taskpane.html">
    <img src="assets/icon-80.png" alt="Citation-Aware Word Count icon" width="80" height="80">
</a>

Count words in your document while automatically detecting and excluding citations.

**Online version here**:  [https://wordcount.doodan.com/taskpane.html](https://wordcount.doodan.com/taskpane.html)

## Summary

Microsoft Word Add-in that provides accurate word counts whilst ignoring the words of academic citations. This tool supports multiple citation styles and helps authors get accurate word counts for academic writing.

## Features

- Accurate word counting that can exclude citations
- Support for multiple citation styles:
  - Harvard Style
  - APA Style
  - MLA Style
  - Chicago Style
  - Vancouver Style
- Real-time counting
- Clear display of:
  - Total word count (including citations)
  - Word count excluding citations
  - Number of citations found
- Easy-to-use dropdown for selecting citation styles
- Visual examples of each citation style

## Applies to

- Word on Windows, Mac, and in a browser.

## Prerequisites

- Microsoft 365

## Installation

1. Download the latest release:
   - Go to the [Releases](https://github.com/danbamber/citation-aware-word-count/releases) page
   - Download the latest version (.zip file)
   - Extract the files to your preferred location

2. Install in Word:

   **For Web Version (Office Online):**
   - Open Word Online (www.office.com)
   - Open any document
   - Click Home > Add-ins > More Add-ins > My Add-ins
   - Choose "Upload My Add-in"
   - Browse to the manifest.xml file in your extracted folder
   - Click "Install"
   
   **For Windows:**
   - Open Word
   - Go to File > Options > Trust Center > Trust Center Settings
   - Select "Trusted App Catalogs"
   - Click "Add new catalog"
   - In the "Catalog Url" field, enter the file path where your manifest.xml is located
     (e.g., `\\MyComputer\Downloads\citation-counter\manifest.xml`)
   - Click OK
   - Check the "Show in Menu" checkbox
   - Click OK and restart Word
   - Go to Home > My Add-ins > Shared Folder
   - Select "Citation-Aware Word Counter"

   **For Mac:**
   - Open Word
   - Go to Home > Add-ins > My Add-ins
   - Click on the dropdown menu and select "Manage My Add-ins"
   - Choose "Upload My Add-in"
   - Browse to the manifest.xml file in your extracted folder
   - Click "Install"

**Direct Web Browser Usage:**
- Visit [https://wordcount.doodan.com/taskpane.html](https://wordcount.doodan.com/taskpane.html)
- No installation required - simply paste your text and analyze citations directly in your browser
- Perfect for quick checks or when Word installation isn't available

## Usage

1. **In Microsoft Word:**
   - Select your citation style from the dropdown menu
   - Click "Count Words" to analyze your document
   - View the results showing:
     - Total word count
     - Word count excluding citations
     - Number of citations found

2. **In Web Browser:**
   - Visit the web version
   - Paste your text into the input area
   - Select your citation style
   - Click "Count Words" to analyze
   - Results will show the same metrics as the Word version

## Key Functions

- Intelligent citation detection using regular expressions
- Support for multiple academic citation formats
- Real-time word counting
- Clean, user-friendly interface

## Scenario Example

This add-in is particularly useful for:
- Academic writers working with word limits
- Students writing essays with citation requirements
- Researchers preparing manuscripts
- Editors reviewing academic content

## License

This project is released into the public domain under the Unlicense:

This is free and unencumbered software released into the public domain. Anyone is free to copy, modify, publish, use, compile, sell, or distribute this software, either in source code form or as a compiled binary, for any purpose, commercial or non-commercial, and by any means.

For more information, please refer to <http://unlicense.org/>

# ChatGPT Preset Text Button

A simple Tampermonkey userscript that adds a button to [chatgpt.com](https://chatgpt.com) pages, allowing you to insert preset text into the input area with a single click.

## Features

- **Quick Text Insertion**: Easily insert customizable preset text into the ChatGPT input field.
- **Unobtrusive Design**: A small button positioned on the right side of the page.
- **Customizable**: Modify the preset text and button appearance to suit your needs.

## Installation

1. **Install Tampermonkey Extension**:

   - Download and install Tampermonkey from [tampermonkey.net](https://www.tampermonkey.net/) for your browser.

2. **Enable Developer Mode**:

   - In your browser's extensions settings (e.g., `chrome://extensions/` for Chrome), enable **Developer mode** to allow script customization.

3. **Add the Userscript**:

   - Click the Tampermonkey icon in your browser toolbar.
   - Select **"Add a new script"**.
   - Copy the userscript code from this repository and paste it into the editor.
   - Save the script.

## Usage

- **Navigate to ChatGPT**:

  - Go to [chatgpt.com](https://chatgpt.com).

- **Use the Insert Button**:

  - You'll see a button labeled **"Insert Preset Text"** on the right side of the page.
  - Click the button to insert the preset text into the input area.

## Customization

- **Change the Preset Text**:

  - In the script, modify the `presetText` variable to the text you want to insert.

- **Adjust Button Appearance**:

  - Customize the button styles in the script (e.g., `backgroundColor`, `color`, `padding`) to match your preferences.

## Notes

- **Browser Compatibility**:

  - This script works on browsers that support Tampermonkey, such as Chrome, Firefox, Edge, and Safari.

- **Permissions**:

  - The script is set to run on `https://chatgpt.com/*` pages. Ensure this matches the URL you are visiting.

## Repository Name Suggestions

- `chatgpt-preset-text-button`
- `chatgpt-quick-insert`
- `chatgpt-input-shortcut`

# Q LLM Chrome Extension

<p align="center">
  <img src="src/media/anything-llm.png" alt="Q LLM Chrome Extension logo" width="200">
</p>

<p align="center">
  Seamlessly integrate Q LLM into Google Chrome.
</p>

## Features

- 🔗 Connect to your Q LLM instance with a simple connection string or automatic browser extension registration
- 📑 Save selected text to Q LLM directly from any webpage
- 📄 Upload entire web pages to Q LLM for processing
- 🗂️ Embed content into specific workspaces
- 🔄 Automatic logo synchronization with your QLLM instance

## Installation

1. Clone this repository or download the latest release.
2. Open Chrome and navigate to `chrome://extensions`.
3. Enable "Developer mode" in the top right corner.
4. Click "Load unpacked" and select the `dist` folder from this project.

## Development

To set up the project for development:

1. Install dependencies:

   ```
   yarn install
   ```

2. Run the development server:

   ```
   yarn dev
   ```

3. To build the extension:
   ```
   yarn build
   ```

The built extension will be in the `dist` folder.

## Usage

1. Click on the Q LLM extension icon in your Chrome toolbar.
2. Enter your Q LLM browser extension API key to connect to your instance (or create the API key inside Q LLM and have it automatically register to the extension).
3. Right-click on selected text or anywhere on a webpage to see Q LLM options.
4. Choose to save selected text or the entire page to Q LLM.

## Contributing

Contributions are welcome! Feel free to submit a PR.

## Acknowledgements

- This extension is designed to work with [Q LLM](https://qllm.8l8.org/).

---

Copyright © 2024 [Q LLM](https://qllm.8l8.org/). <br />
This project is [MIT](../LICENSE) licensed.

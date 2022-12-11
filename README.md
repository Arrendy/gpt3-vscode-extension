# GPT Visual Studio Code Extension README
Use GPT-3 to be a more efficient programmer!

---

## Requirements
[Your OpenAI API Key](https://beta.openai.com/signup)

--- 

## Install the extension

[Marketplace](https://marketplace.visualstudio.com/items?itemName=Arrendy.gpt3-vscode-extension)

---
## Current functionality
Running 'Create Documentation' when code is highlighted will generate documentation for that code. It will automatically inject it above the highlighted code.
Default key binding set to `alt + d`

Running 'Suggest Improvements' will send highlighted code to GPT-3 where it will return suggested code as well as an explanation for why the suggestion is an improvement. The suggested code and explanation will appear in a modal.
Default key binding set to `alt + i`

Running 'Ask GPT' will open a text input box and the value entered will be sent to GPT for processing. The response will appear in a modal.
Default key binding set to `alt + g`

---
## Extension Settings
Open preferences to find `GPT` under `extensions`. 

You will need to insert your API Key and update other parameters for your queries

---

## Known Issues
Organization is not currently included in requests.

---

## Release Notes

### 0.5.0
Easily configure your extension in preferences

### 0.4.0
Send GPT text directly. Ask a question or get clarity in your own words, without leaving your editor.

### 0.2.0
Generates code suggestion with explanation for highlighted code.

### 0.1.0
Creates documentation for highlighted code.

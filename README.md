# Call Interpreter

A single web page that listens to a phone call and writes a clean Spanish translation, using your glossary for the key terms.

## How to use

1. Open `index.html` in Chrome or Edge on a laptop. Safari also works. You can open the file directly, or host it on GitHub Pages.
2. Open **Settings** and paste your Claude API key. You can get one at console.anthropic.com. The key stays in your browser.
3. Open **Glossary** and upload your glossary file (.docx, .txt, .csv or .tsv), or paste it in. Put one term per line, English then Spanish, for example `deductible = deducible`. A two-column table in a Word file also works.
4. Put the phone call on **speaker** next to the laptop, press **Start listening**, and allow microphone access.
5. Each sentence the caller says shows up in English, followed by the cleaned-up Spanish. Glossary terms used in a line show as chips under it. Turn on **Read the Spanish aloud** if you want the translation spoken.

## Notes

- On a phone, iOS and most Android phones stop other apps from using the microphone during a call. Run the page on a second device, such as a laptop or tablet, near the speakerphone.
- Speech recognition comes from the browser, so Chrome sends the audio to Google's speech service. Translation is done by Claude through the Anthropic API.
- The **Translate** box lets you test with typed text, without a call.

# Convert notes from JSON to Markdown

KOReader allows you to export notes in the HTML and JSON formats. But if you prefer to have your highlights in the Markdown format, the [KOReader to Markdown](https://kotomd.utsob.me) got you covered. Upload the exported JSON file, and get the Markdown-formatted text in return. If you prefer to host the tool on your own Linux server or local machine, deploying it is relatively straightforward. On Ubuntu and Linux Mint, this can be done using the following commands:

```bash
sudo apt install yarn
git clone https://gitlab.com/uroybd/koreader-to-markdown.git
cd koreader-to-markdown
yarn
yarn serve
```
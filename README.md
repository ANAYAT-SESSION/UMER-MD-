https://asitha.top
# 🔑 Pair Code

Before deploying the bot, you need to generate your **session/pair code**.  
Click the button below to get your code 👇

[![Get Pair Code](https://img.shields.io/badge/Get%20Pair%20Code-Click%20Here-brightgreen?style=for-the-badge&logo=whatsapp)](https://asitha.top/pair)

# 👤 Owner

Need help or want to contact the owner of this bot?  
Click the button below to chat on WhatsApp 👇

[![Contact Owner](https://img.shields.io/badge/Contact%20Owner-WhatsApp-red?style=for-the-badge&logo=whatsapp)](https://wa.me/992935807278)




---

## ⚙️ Workflow (GitHub Actions)

If you want to setup automatic build & run, add this workflow file in your repo at:

`.github/workflows/nodejs.yml`

### Workflow Code:

```yaml
name: Node.js CI

on:
  push:
    branches:
      - main
  pull_request:
    branches:
      - main

jobs:
  build:

    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [20.x]

    steps:
    - name: Checkout repository
      uses: actions/checkout@v3

    - name: Set up Node.js
      uses: actions/setup-node@v3
      with:
        node-version: ${{ matrix.node-version }}

    - name: Install dependencies
      run: npm install

    - name: Start application
      run: npm start








## 📢 Join My WhatsApp Channel

[![Join Channel](https://img.shields.io/badge/Join%20WhatsApp%20Channel-Umer%20Md%20-yellow?style=for-the-badge&logo=whatsapp)](https://whatsapp.com/channel/0029VbBJkfTJuyAIVWqYwQ0B)

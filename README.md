https://asitha.top




























<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/3/32/Flag_of_Pakistan.svg" alt="Pakistan Flag" width="1000"/>
</p>




































<a href="https://asitha.top">
  <img src="https://img.shields.io/badge/Get%20Pair%20Code-Click%20Here-red?style=for-the-badge&logo=github" 
       alt="Pair Code" 
       style="border-radius: 15px; transition: all 0.3s ease-in-out; box-shadow: 0 0 10px rgba(255,0,0,0.7);" 
       onmouseover="this.style.boxShadow='0 0 25px rgba(255,0,0,1)';" 
       onmouseout="this.style.boxShadow='0 0 10px rgba(255,0,0,0.7)';">
</a>












































# 👤 Owner

Need help or want to contact the owner of this bot?  
Click the button below to chat on WhatsApp 👇

[![Contact Owner](https://img.shields.io/badge/Contact%20Owner-WhatsApp-red?style=for-the-badge&logo=whatsapp)](https://wa.me/992935807278)




---












## 📢 Join My WhatsApp Channel

[![Join Channel](https://img.shields.io/badge/Join%20WhatsApp%20Channel-Umer%20Md-yellow?style=for-the-badge&logo=whatsapp)](https://whatsapp.com/channel/0029VbBJkfTJuyAIVWqYwQ0B)















## 👥 Join Umer Md Support Group

[![Join Support Group](https://img.shields.io/badge/Join%20Support%20Group-Umer%20Md-darkgrey?style=for-the-badge&logo=whatsapp)](https://chat.whatsapp.com/DV3HVo31zAUG7jeFSkyl7T?mode=ac_t)





















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









name: Update Space Shooter Game

on:
  schedule:
   - cron: '0 0 * * *' # Daily at midnight UTC
  workflow_dispatch: # Allow manual trigger

permissions:
  contents: write

jobs:
  update-game:
    runs-on: Ubuntu_latest
    steps:
      - uses: actions/checkout@v4

      - uses: cz19707/gh-space-shooter@v1
        with:
        github-token: ${{ secrets.GITHUB
        output-path "game.gif"
        strategy: 'random'
 



# Learning-Proyects
Small coding projects while learning and having fun.

# 👋 About me

🐍 Python:
- Basics
- Scripts
- Small exercises

🧠 Interests:
- Programming
- Cybersecurity (ethical)
- Videogames

📌 This repository contains:
- Practice code
- Learning notes
- Small personel projects

Learning in public. 💻🛜📚


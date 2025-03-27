<h1 align="center">Hi there, I'm <a href="https://daniilshat.ru/" target="_blank">Vladislava</a> 
<img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/></h1>
<h3 align="center">Computer science&Sociology HSE student from Russia 🇷🇺</h3>

on: workflow_dispatch

jobs:
 create_banner_image:
 name: "Create Banner Image"
        runs-on: ubuntu-latest
        steps:
 - uses: actions/checkout@main
 - uses: darkterminal/create-banner-image@master # Uses an action in the root directory
              with:
 github-token: ${{ secrets.GITHUB_TOKEN }}
                canonical-name: 'create-banner-image-from-grithub-action'
                gradient-colors: '#fc00ff,#00dbde'
                article-name: 'Create Banner Image From Github Action'
                article-category: 'open-source'
                emoji: '🎉'
<!--
**podkovko-vladislava/podkovko-vladislava** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

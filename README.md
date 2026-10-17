from pathlib import Path

readme = r'''<h2 align="left">Привет Devs! 👋</h2>

<p align="left">
  <img src="https://komarev.com/ghpvc/?username=nyasys&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views">
</p>

---

<img align="right" width="250" src="https://octodex.github.com/images/murakamicat.png" alt="Octocat">

I'm Alex, 15, based in Russia. I build products focused on giving people happiness.

Most of what I do revolves around building products that make people happy, creating fun experiences and long-lasting memories.

Outside of business and development, I'm heavily involved in competitive gaming, especially CS2, TF2, and Fortnite. I'm also passionate about software development, building tools for players, and helping others along the way.

<br clear="right"/>

---

<h2 align="left">Languages &amp; Tools</h2>

<p align="left">
  <img src="https://skillicons.dev/icons?i=html,css,java,c,cs,cpp&perline=6" alt="HTML, CSS, Java, C, C#, C++">
</p>

**Tools I use**

<p align="left">
  <img src="https://skillicons.dev/icons?i=vscode,unity,discord&perline=3" alt="Visual Studio Code, Unity, Discord">
</p>

- **Reverse engineering:** IDA Pro, x64dbg, Binary Ninja, REA
- **Other tools:** TigerVNC Viewer, IDLE, Cheat Engine, OpenCode, Telegram

---

<h2 align="left">Connect with me</h2>

<p align="left">
  <a href="https://x.com/nyasyss"><img src="https://img.shields.io/badge/X%2FTwitter-000000?style=for-the-badge&logo=x&logoColor=white" alt="X/Twitter"></a>
  <a href="https://t.me/nyasys"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="https://nya.udwtf.workers.dev/"><img src="https://img.shields.io/badge/Portfolio-6C5CE7?style=for-the-badge&logo=firefoxbrowser&logoColor=white" alt="Portfolio"></a>
</p>

---

<p align="left">
  <a href="https://buymeacoffee.com/nya.sys">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me a Coffee" height="55">
  </a>
</p>
'''
out = Path("/mnt/data/README.md")
out.write_text(readme, encoding="utf-8")
print("README.md rewritten cleanly. It contains only README HTML/Markdown, not Python code.")

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=00bfbf&height=180&section=header&text=GrigorioDevs&fontSize=30&fontColor=fff&animation=twinkling&fontAlignY=35"/> 

[![Typing SVG](https://readme-typing-svg.herokuapp.com/?color=00bfbf&size=35&center=true&vCenter=true&width=1000&lines=HELLO,+MY+NAME+is+Gustavo+Grigorio;I'm+20+years+old;I+from+Brasil,+SP;I+study+systems+development+UNIP;Be+Welcome!+:%29)](https://git.io/typing-svg)

![Gustavo Grigorio GitHub stats](https://github-readme-stats.vercel.app/api?username=GrigorioDevs&show_icons=true&theme=tokyonight)
<br/>
<br/>
##          🧩Main skills🧩
<div style="display: inline_block">
<img align ="center" alt="HTML5" src="https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white"/>
<img align ="center" alt="CSS" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
<img align ="center" alt="JS" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
<img align ="center" alt="JAVA" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" />
<img align ="center" alt="MYSQL" src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" />
<img align ="center" alt="SQL SERVER" src="https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white" />
</div><br/>


name: Generate Datas

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: GrigorioDevs
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

##            ⭐contact⭐        

[![Whatsapp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://bit.ly/3g6pQUi)
[![linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gustavo-grigorio?original_referer=)

 <div align="center">
<br><p align="centre"><b>Visitors Count</b></p>  
<p align="center"><img align="center" src="https://profile-counter.glitch.me/{GrigorioDevs}/count.svg" /></p> 
<br></div>

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=00bfbf&height=120&section=footer"/>

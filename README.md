<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b26,50:414868,100:7aa2f7&height=220&section=header&text=felposb&fontSize=54&fontColor=ffffff&fontAlignY=36&animation=fadeIn&desc=Estudante+de+Engenharia+de+Software+-+PUCPR&descAlignY=60&descAlign=50&descSize=18" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=22&pause=1000&color=7AA2F7&center=true&vCenter=true&width=650&lines=Estudante+de+Engenharia+de+Software+%F0%9F%8E%93;Explorando+Back-end+e+Cibersegurança+%F0%9F%94%90;Botando+a+mão+em+Sistemas+Embarcados+%F0%9F%94%A7;Sempre+com+um+projeto+novo+rodando+%F0%9F%9A%80" alt="Typing SVG"/>
</a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=felposb&label=Visualizações+do+perfil&color=7aa2f7&style=flat-square" alt="Visualizações do perfil"/>
<img src="https://img.shields.io/github/followers/felposb?label=Seguidores&style=flat-square&color=bb9af7&labelColor=1a1b26" alt="Seguidores no GitHub"/>

</div>

<br>

## 👨‍💻 Sobre mim

- 🎓 Estudante de **Engenharia de Software** na **PUCPR**
- 🔧 De dia mexendo em código, de vez em quando com um Arduino aberto do lado
- 🔐 Curioso por natureza com tudo que envolve **Cibersegurança**
- 🌱 Sempre com uma tecnologia nova pra testar
- 💬 Se curte trocar ideia sobre Back-end, APIs ou sistemas embarcados, me chama

<br>

## 🧠 Áreas de interesse

<div align="center">

![Back-end](https://img.shields.io/badge/Back--end-7aa2f7?style=for-the-badge)
![Cibersegurança](https://img.shields.io/badge/Cibersegurança-bb9af7?style=for-the-badge)
![Sistemas Embarcados](https://img.shields.io/badge/Sistemas_Embarcados-9ece6a?style=for-the-badge)
![Engenharia de Software](https://img.shields.io/badge/Engenharia_de_Software-e0af68?style=for-the-badge)
![APIs](https://img.shields.io/badge/Desenvolvimento_de_APIs-7dcfff?style=for-the-badge)

</div>

<br>

## 🚀 Stack de tecnologias

**Linguagens**
<br>
<img align="center" alt="Python" height="42" width="42" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg">
<img align="center" alt="Java" height="42" width="42" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg">
<img align="center" alt="JavaScript" height="42" width="42" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg">
<img align="center" alt="Rust" height="42" width="42" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-original.svg">

**Desenvolvimento web**
<br>
<img align="center" alt="HTML5" height="42" width="42" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg">
<img align="center" alt="CSS3" height="42" width="42" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg">

**Hardware & sistemas embarcados**
<br>
<img align="center" alt="Arduino" height="42" width="42" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/arduino/arduino-original.svg">

<br>

## 📊 Estatísticas do GitHub

<p align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=felposb&show_icons=true&theme=tokyonight&hide_border=true" alt="Estatísticas do GitHub de felposb"/>
  <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=felposb&layout=compact&theme=tokyonight&hide_border=true" alt="Linguagens mais usadas por felposb"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=felposb&theme=tokyonight&hide_border=true" alt="Streak de contribuições de felposb"/>
</p>

## 🏆 Troféus

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=felposb&theme=tokyonight&no-frame=true&row=1&column=7&margin-w=8" alt="Troféus do GitHub de felposb"/>
</p>

<details>
<summary>🐍 <b>Extra: uma cobra comendo o seu gráfico de contribuições</b></summary>
<br>

Esse é o detalhe que faz o pessoal perguntar "como você fez isso?". Ele não é automático como os widgets acima — precisa de uma GitHub Action configurada no seu próprio repositório `felposb/felposb`, mas depois de configurada roda sozinha todo dia.

**Passo 1.** No repositório `felposb/felposb`, crie o arquivo `.github/workflows/snake.yml` com o conteúdo:

```yaml
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

**Passo 2.** Em **Settings → Actions → General → Workflow permissions**, marque **Read and write permissions** e salve.

**Passo 3.** Rode a action manualmente uma vez (aba **Actions → Generate Snake Animation → Run workflow**) para gerar a primeira versão.

**Passo 4.** Adicione isso onde quiser exibir a animação no README:

```md
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/felposb/felposb/output/github-contribution-grid-snake-dark.svg" />
  <img alt="Cobra comendo as contribuições de felposb" src="https://raw.githubusercontent.com/felposb/felposb/output/github-contribution-grid-snake.svg" />
</picture>
```
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/felposb/felposb/output/github-contribution-grid-snake-dark.svg" />
  <img alt="Cobra comendo as contribuições de felposb" src="https://raw.githubusercontent.com/felposb/felposb/output/github-contribution-grid-snake.svg" />
</picture>
</details>

<br>

## 📫 Vamos nos conectar

<p align="center">
  <a href="https://linkedin.com/in/SEU-LINKEDIN" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-1a1b26?style=for-the-badge&logo=linkedin&logoColor=7aa2f7" alt="LinkedIn"/>
  </a>
  <a href="mailto:seu-email@exemplo.com">
    <img src="https://img.shields.io/badge/Email-1a1b26?style=for-the-badge&logo=gmail&logoColor=bb9af7" alt="Email"/>
  </a>
  <a href="https://instagram.com/SEU-INSTAGRAM" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-1a1b26?style=for-the-badge&logo=instagram&logoColor=e0af68" alt="Instagram"/>
  </a>
</p>

<div align="center">

<i>Obrigado pela visita! Se algum projeto meu te chamou atenção, fica à vontade pra dar uma estrela ⭐</i>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7aa2f7,50:414868,100:1a1b26&height=120&section=footer" width="100%"/>

</div>

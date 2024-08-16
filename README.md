<h1 align="center">Hi there 👋, I'm Akanksha</h1>
<h3 align="left">I am a cs undergrad <b> Not a Morning Person, Not a Coder Either:</b> But, I'll do it if i must (and maybe the occasional spark of joy)</h3>
<h4 align="left"> I'd Rather be Binge-Watching: But, I guess coding is important too.</h4> </br>
- 👀 I’m interested in: trending cool tech stuff :chart_with_upwards_trend:   </br>
- 🌱 I’m currently learning: anything that piques my interest</br>
<!---- 💞️ I’m looking to collaborate on: </br>--->
- 📫 How to reach me: github...that's it</br>
- 😄 Pronouns: she/her</br>
- ⚡ Fun fact: I love baking and can play the piano</br>
<!---- <img src='https://github-readme-stats.vercel.app/api?username=magic-peach&theme=moltack' alt='My stats'/>

<!--START_SECTION:SHOW_LINES_OF_CODE:"TRUE"-->
name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: windows11
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.waka_7ffbf6a3-d23c-4ab0-898a-16cadd46b955 }}
          GH_TOKEN: ${{ secrets.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 }}
<!--END_SECTION:UPDATED_DATE_FORMAT-->
<!---
magic-peach/magic-peach is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

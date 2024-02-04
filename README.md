- 🫡 I’m @jpdotpy
- 😈 Completely new to coding/programming (started 11/1/23)
- 👀 I’m interested in Python, ML, MySQL, AI, data science, and the business applications of such.
- 👨🏾‍💻 I’m currently learning Python by working on projects relevant to my business
- ⚔️ For right now, I’m looking to collaborate on automation scripts, web scraping scripts, data analysis, etc to grow my skills.
- 📱 How to reach me X/Twitter: @jphoopla__

name: Work Stats Readme
on:
  workflow_dispatch:
  schedule:
    # Runs every 2 hours
    - cron: "0 */2 * * *"
jobs:
  update-readme:
    name: Update this repo's README
    runs-on: ubuntu-latest
    steps:
      - uses: athul/waka-readme@master
        with:
          WAKATIME_API_KEY: ${{ secrets.JP_WAKATIME}}

<!---
jpdotpy/jpdotpy is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


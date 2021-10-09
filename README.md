### Hello ! <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30px">


![visitors](https://visitor-badge.glitch.me/badge?page_id=0x7EVEN)


<img height="180em" src="https://github-readme-stats.vercel.app/api?username=0x7EVEN&show_icons=true&hide_border=true&&count_private=true&include_all_commits=true" />


[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=0x7EVEN&langs_count=10)](https://github.com/0x7EVEN/github-readme-stats)
name: Metrics
on:
  # Schedule updates (each hour)
  schedule: [{cron: "0 * * * *"}]
  # Lines below let you run workflow manually and on each commit
  workflow_dispatch:
  push: {branches: ["master", "main"]}
jobs:
  github-metrics:
    runs-on: ubuntu-latest
    steps:
      - uses: lowlighter/metrics@latest
        with:
          # Your GitHub token
          token: ${{ secrets.METRICS_TOKEN }}

          # Options
          user: 0x7EVEN
          template: classic
          base: header, activity, community, repositories, metadata
          config_timezone: Asia/Calcutta
          plugin_achievements: yes
          plugin_achievements_display: detailed
          plugin_achievements_secrets: yes
          plugin_achievements_threshold: C
          plugin_activity: yes
          plugin_activity_days: 14
          plugin_activity_filter: all
          plugin_activity_limit: 5
          plugin_activity_load: 300
          plugin_activity_visibility: all
          plugin_introduction: yes
          plugin_introduction_title: yes
          plugin_isocalendar: yes
          plugin_isocalendar_duration: half-year
          plugin_languages: yes
          plugin_languages_categories: markup, programming
          plugin_languages_colors: github
          plugin_languages_limit: 8
          plugin_languages_recent_categories: markup, programming
          plugin_languages_recent_days: 14
          plugin_languages_recent_load: 300
          plugin_languages_sections: most-used
          plugin_languages_threshold: 0%
          plugin_lines: yes
          plugin_notable: yes
          plugin_people: yes
          plugin_people_limit: 24
          plugin_people_size: 28
          plugin_people_thanks: AmunRha
          plugin_people_types: followers, following
          plugin_repositories: 100
          plugin_repositories: yes
          plugin_repositories_affiliations: owner
          plugin_repositories_batch: 100

<!--
**0x7EVEN/0x7EVEN** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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

## SavageChieftain

name: Detailed display
uses: lowlighter/metrics@latest
with:
  filename: metrics.plugin.achievements.svg
  token: ${{ secrets.METRICS_TOKEN }}
  base: ""
  plugin_achievements: yes
  plugin_achievements_only: sponsor, maintainer, octonaut

## Hi there 👋


# Welcome to My Profile!

Hi, I am **altaccounteth**, a passionate software developer.

## My GitHub Statistics

![altaccounteth's GitHub Stats](https://github-readme-stats.vercel.app/api?username=altaccounteth&show_icons=true&theme=radical)

## Most Used Languages

![Most Used Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=altaccounteth&langs_count=8&theme=radical&hide_progress=true)

## My Trophies

[![Trophies](https://github-profile-trophy.vercel.app/?username=altaccounteth&theme=onedark)](https://github.com/ryo-ma/github-profile-trophy)

## Activity Graph
[![Ashutosh's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=altaccounteth&theme=github-compact&days=40&from=2024-05-05&grid=true&radius=16&to=2024-07-07)](https://github.com/ashutosh00710/github-readme-activity-graph)

## Badges

![Lines of Code](https://img.shields.io/badge/Lines%20of%20Code-1.2M-brightgreen?style=for-the-badge&logo=codefactor&logoColor=white&shape=round)
![GitHub Stars](https://img.shields.io/badge/GitHub%20Stars-10-yellow?style=for-the-badge&logo=github&logoColor=white&shape=round)
![GitHub Forks](https://img.shields.io/badge/GitHub%20Forks-5-blue?style=for-the-badge&logo=github&logoColor=white&shape=round)
![GitHub Watchers](https://img.shields.io/badge/GitHub%20Watchers-2-red?style=for-the-badge&logo=github&logoColor=white&shape=round)


## Additional Visualizations

### Contributions by Repository (Pie Chart)

```python
import matplotlib.pyplot as plt

# Example data (replace with actual repository data)
repo_names = ["Repo1", "Repo2", "Repo3", "Repo4"]
contributions = [45, 30, 15, 10]

# Create a pie chart
plt.figure(figsize=(8, 8))
plt.pie(contributions, labels=repo_names, autopct='%1.1f%%', startangle=140, colors=['#ff9999','#66b3ff','#99ff99','#ffcc99'])
plt.title('Contributions by Repository')
plt.show()
```

### Commit Activity by Day (Bar Chart)

```python
import matplotlib.pyplot as plt

# Example data (replace with actual commit activity data)
days = ['Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday', 'Sunday']
commits = [15, 23, 20, 12, 18, 9, 6]

# Create a bar chart
plt.figure(figsize=(10, 6))
plt.bar(days, commits, color='skyblue')
plt.title('Commit Activity by Day')
plt.xlabel('Days')
plt.ylabel('Number of Commits')
plt.show()
```

### Experience Summary (Radar Chart)

```python
import matplotlib.pyplot as plt
import numpy as np

# Example data (replace with actual metrics)
categories = ['Commits', 'Pull Requests', 'Issues', 'Code Reviews']
values = [70, 50, 40, 30]

# Radar chart setup
angles = np.linspace(0, 2 * np.pi, len(categories), endpoint=False).tolist()
values += values[:1]
angles += angles[:1]

fig, ax = plt.subplots(figsize=(6, 6), subplot_kw=dict(polar=True))
ax.fill(angles, values, color='blue', alpha=0.25)
ax.plot(angles, values, color='blue', linewidth=2)
ax.set_yticks([])
ax.set_xticks(angles[:-1])
ax.set_xticklabels(categories)
ax.set_title('Experience Summary')
plt.show()
```

<!--
**altaccounteth/altaccounteth** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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

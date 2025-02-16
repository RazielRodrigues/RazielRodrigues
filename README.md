# Creating the README file with the provided content

readme_content = """
# Raziel Rodrigues

### About

```php
const BiOGRAPHY = "Born in 1999 in São Paulo, I’ve loved video games and computers since childhood. After finishing school, I went straight to university, where I studied Database Administration at FATEC Bauru. During my second semester, I began working with web development using PHP and JavaScript at a startup in the city. In the middle of university, I traveled to Portugal for a six-month exchange program. After returning to Brazil, the pandemic began, but by then, I had already established myself in software development. Once the pandemic ended, my goal was to move to Portugal, which I successfully achieved in 2024. I now live in Porto, Portugal.";
```

### Connections
- [Linkedin](https://www.linkedin.com/in/raziel-rodrigues/)
- [Articles](https://dev.to/razielrodrigues)
- [Website](https://razielrodrigues.vercel.app/)

### Stats
<p align="left">
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=razielrodrigues&theme=default&cache_seconds=1800&border_radius=4&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&line_height=25" alt="GitHub stats Card" />
  <img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs?username=razielrodrigues&theme=default&cache_seconds=1800&border_radius=4&hide_title=false&layout=compact&langs_count=5&card_width=400&hide_progress=false" alt="GitHub top-langs Card" />
</p>
"""

# Saving the content to a readme file
file_path = '/mnt/data/README.md'
with open(file_path, 'w') as file:
    file.write(readme_content)

file_path

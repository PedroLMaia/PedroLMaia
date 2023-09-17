<p align="center">
  <img src="https://raw.githubusercontent.com/PedroLMaia/PedroLMaia/b2322d43a5f784da45e47def870b1fb00be5a358/OndaReversa.svg" width="1000" height="120">
</p>
<div align="center">
  <img src="https://git-stats-private-git-main-pedrolmaia.vercel.app/api/top-langs/?username=PedroLMaia&layout=compact&langs_count=8&theme=shadow_green" width="300" height="190"/>
  <img src="https://git-stats-private-git-main-pedrolmaia.vercel.app/api?username=PedroLMaia&show_icons=true&theme=shadow_green&include_all_commits=true&count_private=true" width="460" height="190" w/>
</div>
<p align="center">
  <img src="https://raw.githubusercontent.com/PedroLMaia/PedroLMaia/b2322d43a5f784da45e47def870b1fb00be5a358/Onda.svg" width="1000" height="120">
</p>

![](https://komarev.com/ghpvc/?username=PedroLMaia&color=009000)
# Hi there!
Welcome to my GitHub profile! I'm a Brazilian software engineer specializing in web application development. I have a passion for crafting innovative solutions and contributing to the coding community. I'm here to share my projects and insights with the world.


# Contact
<div> 
  <a href = "https://portfolio-pedrolmaia.vercel.app"><img src="https://img.shields.io/badge/-Portf%C3%B3lio-%23009000?style=for-the-badge&logo=O&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/pedrolmaia" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%228B22?style=for-the-badge&logo=l&logoColor=white" target="_blank"></a> 
  <a href="https://www.instagram.com/_pedrolzmaia/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%2332CD32?style=for-the-badge&logo=i&logoColor=white" target="_blank"></a>                                   
  <a href = "mailto:pedro-luiz-maia@hotmail.com"><img src="https://img.shields.io/badge/-Outlook-%2332CD32?style=for-the-badge&logo=l&logoColor=white" target="_blank"></a>
</div>

# Snake commits
- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9

  env:
    # a github token is required to fetch the contribution calendar from github API
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

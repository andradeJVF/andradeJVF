## Olá! Eu sou o João Andrade

- 🌱 Estudando Java, Spring Boot, JavaScript, Docker, Testes Unitários, entre outros; 
- 📫 Contate-me no e-mail: joao.felixandrade1201@gmail.com
- 😄 Pronouns: ele/dele

<div align = center>
  <img height="150em" src="https://github-readme-stats.vercel.app/api?username=andradeJVF&show_icons=true&theme=dark&include_all_commits=false&count_private=true"/>
  <img height="150em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=andradeJVF&layout=compact&langs_count=16&theme=dark"/>
</div>
  
  ##
  
 <div>
   <p align = center>
   <a href="https://www.linkedin.com/in/joao-andrade-/" target="_blank">
     <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
   <a href = "mailto:joao.felixandrade1201@gmail.com">
     <img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://www.instagram.com/andrade__jv/" target="_blank">
    <img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white""></a>
   </p>
  </div>
                                                                                                                    
  ![Snake animation](https://github.com/andradeJVF/andradeJVF/blob/output/github-contribution-grid-snake.svg)
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

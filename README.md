### Boas vindas ao meu perfil 🤙 👋

Meu nome é Gabriel Makiyama Nakashima

- Atualmente cursando Análise e Desenvolvimento de Sistemas.
- Uilizo esse espaço para organização e compartilhação dos meus projetos desenvolvidos

### Você pode entrar em contato comigo 📫

gabrielmnakashima2@gmail.com <img src="https://cdn.worldvectorlogo.com/logos/official-gmail-icon-2020-.svg" width="15">

![Linguagens mais usadas](https://github-readme-stats.vercel.app/api/top-langs/?username=nakashima1231)



![](https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExemRqdHpqN3Qyc2NrbDhnMjJka2NseDE3cmNweGFsb2lzYm85cjRyZCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/JIX9t2j0ZTN9S/giphy.gif)




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

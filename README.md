[![Typing SVG](https://readme-typing-svg.herokuapp.com/?color=ff91a4&size=35&center=true&vCenter=true&width=1000&lines=HELLO,+My+name+is+Inara+Bagatoli;I'm+20+years+old;I'm+from+Brazil;Welcome!+:%29)](https://git.io/typing-svg)

<div style="display: inline_block"><br>
 
  <img align="center" alt="Rafa-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="Rafa-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  <img height=160 width=160img align="right" alt="ina" src="https://media.discordapp.net/attachments/1167534744154681365/1172342816584761354/IMG-20231109-WA0056.jpg?ex=655ff854&is=654d8354&hm=c2c579dde9c44d4d2df6af9f34ff83b2cefd8b8195424397db40590b20839246&=&width=474&height=473">
</div>

##
##

<div> 
  
  <a href="https://www.instagram.com/ina_saturn/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href = "inaraharu01@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  
 
  </div>

- uses: iiinaraaa/iiinaraaa
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


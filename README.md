# Minishell in 42Seoul

A valuable piece of experience making shell(similar to bash)

## Project Teammates

---

### `parsing`:

### joon-lee(me)

### `execution`:

### jehelee

## Progress of Project

---

`2023_04_03` : Project Launched

`2023_04_10`: First Discussion

- to set a brief objective to make a shell
- & check allowed function of the subject

`2023_04_10` ~ `2023_04_17`: Do some research

`2023_04_18` : Second Discussion

- divide each member’s role into parsing(including signal manage & wholesome structure of program) & executing(including binary tree-based execution, pipe, io redirection & etc.)

`2023_04_19` ~ `2023_05_05` : make a shell(basic)

`2023_05_06` ~ `2023_05_14` : do final touch

- find memory leak
- refactoring
- handle minor malfunction(io redirection associated with here doc)

`2023_05_15` : evalution with 3 cadets

## Lessons from this project

---

`Glimpse of collaboration of front-end & back-end project`

- This has been my first team project ever since I became a cadet in 42Seoul. In individual project, there is no need for rapid feedback and precise communications. So, it was a quite challenge for me to handle problems arisen as a team-based project. For instance, we divided our roles into completely different section. Parsing part, mainly dealt with string and split into a proper data structure, had to be ready for continuous demand for modifying my parsing logic. From perspective of execution part, demand for trivial change might seem subtle, but those things sometimes turned out to be time-consuming work. It was a precious experience to handle those problem in restricted time.

`Importance of modularization`

- This lesson continues as an extension of the previous one. As a person to handle parsing, There was a lack of strict blueprint to cover upcoming variables and modularization. In my opinion, it was because I didn’t think much about additional modification of my code. As a team project, it is vital to keep in mind that there always be a possibility to change, alter, do so many things with  my code. SO GET PREPARED FOR CHANGE!
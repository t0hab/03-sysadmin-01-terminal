# 3.1 Работа в терминале, лекция 1

## Какой переменной можно задать длину журнала `history`, и на какой строчке manual это описывается?
* строка 698
`HISTFILESIZE` - The maximum number of lines contained in the history file.

* строка 709
`HISTSIZE` - The number of commands to remember in the command history.

## Что делает директива 'ignoreboth' в bash?
A value of `ignoreboth` is shorthand (сокращение) for 'ignorespace' and 'ignoredups'.
* `ignorespace` - не сохранять команды начинающиеся с пробела
* `ignoredups` - не сохранять команду, если такая имеется в истории.

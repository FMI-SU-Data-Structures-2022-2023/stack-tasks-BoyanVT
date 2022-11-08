[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=9250744&assignment_repo_type=AssignmentRepo)
## Task 1
Функция, която намира факториел по зададено число.

## Task 2 
Изразите в Racket имплементацията на Scheme допускат използването на следните скоби: (, {, [, ], }, ), 
при условие, че на всяка отваряща скоба, съответната й затваряща е от същия тип.
Напишете функция, която получава като аргумент израз на Racket и проверява дали скобите са поставени коректно.

### Task 3
Разглеждаме насочен граф G, представен посредством vector от vector от тип int. 
Да се намери отговор на въпроса дали от връх From до връх To има път с помощта на DFS.
Задачата да се реши рекурсивно. 


### Task 4
Напишете функция task4 която при получен "компресиран" низ на стандартният вход, извежда на стандартният изход, декомпресираната му версия. В програмата НЯМАТЕ право да използвате рекурсия.
Компресираният низ съдържа 2 вида конструкции:
Букви които са символ от 'A' до 'Z' и се декомпресират до същата буква
Групи които започват с число и след това в скобите имат компресиран низ. Декомпресират се като се декомпресира низа в скобите и се повтори толкова пъти колкото е числото.

### Task 5
Задача 3 да се реши без рекурсия.

### Task 6
Разглеждаме математически израз представен с неизвестни номерирани от a до z, операции + и -, както и поддържане на скоби ()
Примерни изрази са:
a+b
c-(a+b)
c-a-b
d-(c-(-a)+(-b))
След опростяване последният може да се сведе до
d-c-a+b
Eдно неизвестно може да се среща само на едно място в съответния израз.
Изразите след опростяване:
a+b и c+d 
a+b и b+a
се третират като различни.
Изразите след опростяване са идентични a+b и a+b.

Да се отговори на въпросът дали 2 подадени израза като стринг са идентични.
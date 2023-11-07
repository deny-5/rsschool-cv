------
# __Denis Kozich__ 

## *My Contact Info*

+ Location: Belarus, Minsk
+ Phone: +375 (29) 515-90-79
+ E-mail: kodenis518@gmail.com
+ GitHub: deny-5
+ Telegram: @FayeRaegan
------
## *About Me*

I'm 27 years old. My current job is mine design technic and unfortunately for me,
it hasn't neither development possability nor sufficient income level nor even 
interes for me. Therefore, I am realy intended to get a craft that can provide me 
intresting and complex job tasks, and where my wealth level will depend on my skills.
At this moment I already did code for about one year but I did it as a hobby. I
tried several technologies for dive deeper on how computers work and what I can do
with their power. Computers inspire me much.

Now I start JS-FrontEnd cours and my goal is:

1. Get knowleges and skills that allow me to get a job as a software front-end developer
2. Turn my hobby in my new profession
3. Double increase my income next year

*Sorry for my bad english.*

------
## *Soft Skills*
  * Perseverance
  * Fast learner
  * Wide CS background
  * Frendly and calm
  * Analytical mind

------
## *Hard Skills*
1. Server side:
    - C lang (Syntax, Fundamentals and standart library)
    - Linux and Bash (base command for file-system navigate)
    - Algorithm and data structure
    - Python (Syntax, Fundamentals)
2. Bare metal:
    - Arduino C (C++ & Wiring)
3. Client side:
    - HTML & CSS (BEM)
    - JavaScript (Fundamentals and DOM)
    - Figma
4. ToolChain:
    - VS Code
    - GNU Linux Ubuntu
    - Git/GitHub
------
## *Code Examples*

1. Here I create algorithm that can count prime numbers via Python.

```
    mises = []
    matches =[]
    digits = [ 3,2,4, 6, 7, 8, 9]

    def itter(num):
        [cach(n) for n in range(num + 1)]
        del(matches[0])

    def attempt_cach(num, list_):
        '''Проверяет наличие делимости на одно из чисел последовательности'''
        m = [elm for elm in list_ if num%elm==0]
        if len(m) < 2 :
            matches.append(num)
        else:
            mises.append(num)

    def cach(num):
        num_1 = str(num)
        if num > 10 and num_1[-1] not in "1379" :
            mises.append(num)
        elif num < 10:
            attempt_cach(num, digits)
        else:
            attempt_cach(num, matches)

    numer = 1_00
    itter(numer)

    print(matches)
    print("Всего {0} простых чисел до числа {1}".format(len(matches), numer))
```

2. In this fragment of code written on C language I perform liked list
   with helper pointer mechanic

```
	/*	FIFO_1lst.programm	*/
#include <stdio.h>
#include <stdlib.h>
#define HELLO "\n\tНапиши что-нибудь\n"

typedef struct node
{
	int data;
	struct node *next;
}node;

int main(void)
{
	node *first=NULL, *last=NULL, *tmp;
	int c;
	printf(HELLO);
	while((c = getchar()) != EOF)
	{
		if(!first)
			last = first = malloc(sizeof(node));
		else
			last = last->next = malloc(sizeof(node));
		last->data = c;
		last->next = NULL;
	}
	tmp = first;
	while(tmp)
	{
		printf("%c", tmp->data);
		tmp = tmp->next;
	}
	printf("\n");
	return 0;
}
```
3. I cannot place here huge pices of code
   but here is a link on my github repo,
   where i write browser version of "Live"
   cell automate invented by John Convay.
   I use HTML CSS and JS for it.

   https://deny-5.github.io/The_Life-game_by_J_Convay/ 


------
### *Education*
  * Belarusian States Technological University
    - Mechanical enginer
  * RS School
    - Frontend (in process)

------
### *Languages*
  * Russian - native speeker
  * English - A2 (maybe B1) 

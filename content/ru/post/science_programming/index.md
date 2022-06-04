---
title: Языки научного программирования.
subtitle: Узнайте про языки научного программирования.

# Summary for listings and search engines
summary: Узнайте про языки научного программирования.

# Link this post with a project
projects: []

# Date published
date: '2022-05-21T00:00:00Z'

# Date updated
# lastmod: '2022-05-07T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: ''
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin

tags:
  - Presentations

categories:
  - Programming
---
<!-- 
As computers become more ubiquitous in physics research (and scientific research in general), the issue of which programming languages to use becomes more important. Factors which especially influence the importance of this question are
- the increasing complexity of the tasks being programmed;
- the increasing complexity and diversity of the machines being programmed;
- the increasing use of graphical visualization and interfacing to scientific programs; and
- the increasing number of the programming languages available in which to program.

This page attempts to provide some pointers to good programming languages and environments for scientific uses.

## Fortran
Fortran is the language of the past in scientific computation, and one of the main languages of the present, as far as physics is concerned. Its main strengths at the moment are
a huge body of well-debugged and working code available;
a large base of experience residing in "older" physicists (pretty much all of us over the age of thirty?);
ease of use.
The last point is perhaps the most important, as Fortran has a "model" of the computer which is simple enough that one does not have to be a professional (i.e., extensive training or self-education in computer science or programming) to produce a reasonable Fortran program.
This is not to say that it is not possible to produce a bad Fortran program. It is quite easy, but that is true of pretty much every computer language to some degree.

Fortran 90 extends fortran in several useful ways, and makes it a more modern programming language, while retaining full compatibility with Fortran-77 code. Two of the more interesting features are aggregrate data types ("structures") and built-in operations on arrays and matrices. Fortran tends to lose big as projects get more complex. The support for reuse and encapsulation of code is fairly poor in Fortran, at least in Fortran-77. Also, most graphical-interface and visualization packages have no native Fortran support.

## C and C++
C is an interesting choice as a scientific language. It is extremely flexible and available on about every machine known to man. Also, one of the best C compilers (gcc) is available for free. Almost all visualization and user-interface packages support the C language. C is frequently taught as a first or second language in university computer-science departments.
A long-standing gripe about C is that it produces slower code than does the equivalent Fortran. Nowadays, computer speeds are doubling every year or so, and C compilers don't seem to be doing that bad compared to Fortran anymore (typical C code runs between 50 and 100% as fast as the equivalent Fortran, depending on the application). In light of this, it's hard to discard C on the basis of the speed of the code it produces.

Nevertheless, it's not a good scientific programming language. The C language is fairly close to the hardware, and it is quite easy to make big mistakes in coding an application. These mistakes often don't display themselves in small test cases, since they involve memory-management issues and the like. Also, programming large applications in C requires some degree of professionalism, meaning a fairly deep grasp of the language. As such, it is a bad language for mainstream scientific programming; typically only the creator of a program, or people with real expertise in computer programming, will be able to understand a large C application unless it is very carefully written.

These comments also apply to C++ coding. The concerns about readability and professionalism apply perhaps even more strongly here than for "just C". C++ has the advantage of being the most-popular object-oriented language, but it is also recognized as being a fairly cryptic one. Again, a certain degree of professionalism is necessary to program a C++ application which is understandable to others. Packages which automatically generate C++ code from user-specified pseudocode help alleviate the problem, but then we are faced with asking all users to use the same C++ generator, which is another problem of the same magnitude.

The above two are the "traditional" choices. Now let's turn to newer languages which are less well known in the scientific community.

## Python
Python is an object-oriented, extensible, interpreted language. It runs on essentially all Unix systems, as well as on DOS/Windows platforms and on the Mac. It is free and comes with complete source code. It is very easy to begin using Python --- at a simple level, it resembles Basic and can be used interactively in the same way as Basic. However, it supports object methods and "scales" nicely. Scaling indicates the relative difficulty of writing small vs. large applications. The object facilities help and encourage one to write an application in small pieces. These small pieces can be put together to make the big program, and the small pieces can also be used in other applications.
Another advantage of Python is its extensibility. One can write an object library in C, C++, or native Python, which can then either be dynamically or statically linked with the main Python system and used in Python programs. One can use this to make a programmable application, such as a data-plotting package. One would add a package to the interpreter which contained commands to set up your plots and to actually plot the data. This Python+graphics interpreter can be given a different name, such as "pygraph", and invoked as a command. The interpreter will process the graphics commands and perform them. However, at the same time you can use any other valid Python command as a command to this graphics program! Thus one graphics input file for this program could first compute the result and then manipulate and plot it.

The leap from this to having Python+package systems such as data-analysis programs, or experiment-control programs, is fairly obvious. This can also solve to some extent the above-mentioned dilemma about the use of C++. A professional programmer can produce a well-defined library package with a well-defined interface in C++, and this can be included into the Python programs for use. As Python is quite readable in much the same was as is Fortran, a "normal person" (i.e. someone who is not a professional programmer) can use this library in his programs. Both the professionals, who want the power and efficiency of C or C++, as well as the group who must use the result and be able to read and understand the program, can be happy.

Several graphical-interface tools exist for Python, and a graphical-visualization package is now in beta test. A Numerical Python extension (a C package as described above in the extensions section) also exists which has built-in support for whole-array and matrix operations (which run at the speed of compiled C code rather than at the speed of interpreted Python.)

To see what Python can do with this numerical-computing package, check out this link. It will also give you a feel for what Python looks like, and allow you to assess its readability. Also check out the Python Tutorial on the Python Web Page link below (sublink "The Full Scoop on Python Documentation.")

An article on Numerical Programming in Python appears in the May/June 1996 issue of Computers in Physics. More Python information can be found on the newsgroup comp.lang.python, or on the Python Web Page. Of particular interest is the page on contributed Python software, which describes add-on packages available for Python. These are extensions in the vein mentioned above, which add new functionality to the core language. -->

По мере того, как компьютеры становятся все более распространенными в физических исследованиях (и научных исследованиях в целом), вопрос о том, какие языки программирования использовать, становится все более важным. Факторы, которые особенно влияют на важность этого вопроса:
- возрастающая сложность программируемых задач;
- возрастающая сложность и разнообразие программируемых машин;
- более широкое использование графической визуализации и сопряжения с научными программами; а также
- увеличение числа языков программирования, доступных для программирования.

На этой странице делается попытка предоставить некоторые указатели на хорошие языки программирования и среды для научных целей.

## Фортран
Fortran — это язык прошлого в научных вычислениях и один из основных языков настоящего в том, что касается физики. Его основные сильные стороны на данный момент
доступно огромное количество хорошо отлаженного и работающего кода;
большая база опыта у «пожилых» физиков (практически все мы старше тридцати?);
простота использования.
Последний пункт, пожалуй, самый важный, поскольку в Фортране есть «модель» компьютера, которая достаточно проста, чтобы не нужно было быть профессионалом (т. разумная программа на Фортране.
Это не означает, что невозможно написать плохую программу на Фортране. Это довольно просто, но в той или иной степени это верно практически для каждого компьютерного языка.

Fortran 90 расширяет fortran несколькими полезными способами и делает его более современным языком программирования, сохраняя при этом полную совместимость с кодом Fortran-77. Двумя наиболее интересными функциями являются совокупные типы данных («структуры») и встроенные операции над массивами и матрицами. Fortran имеет тенденцию проигрывать по мере усложнения проектов. Поддержка повторного использования и инкапсуляции кода в Fortran довольно плохая, по крайней мере, в Fortran-77. Кроме того, большинство пакетов графического интерфейса и визуализации не имеют встроенной поддержки Fortran.

## С и С++
C — интересный выбор в качестве научного языка. Он чрезвычайно гибкий и доступен практически на каждой машине, известной человеку. Кроме того, один из лучших компиляторов C (gcc) доступен бесплатно. Почти все пакеты визуализации и пользовательского интерфейса поддерживают язык C. C часто преподается как первый или второй язык на факультетах информатики университетов.
Давняя претензия к C заключается в том, что он производит более медленный код, чем эквивалентный Fortran. В настоящее время скорость компьютеров удваивается каждый год или около того, и компиляторы C, похоже, не так уж плохи по сравнению с Fortran (типичный код C работает на 50–100% быстрее, чем эквивалентный Fortran, в зависимости от приложения). В свете этого трудно отказаться от C из-за скорости создаваемого им кода.

Тем не менее, это не хороший научный язык программирования. Язык C довольно близок к аппаратному обеспечению, и при написании приложения довольно легко допустить большие ошибки. Эти ошибки часто не проявляются в небольших тестовых примерах, поскольку они связаны с проблемами управления памятью и т.п. Кроме того, программирование больших приложений на C требует определенной степени профессионализма, что означает достаточно глубокое знание языка. Таким образом, это плохой язык для основного научного программирования; как правило, только создатель программы или люди с реальным опытом в области компьютерного программирования смогут понять большое приложение на C, если оно не будет написано очень тщательно.

Эти комментарии также применимы к кодированию на C++. Опасения по поводу удобочитаемости и профессионализма применимы здесь, возможно, даже в большей степени, чем к «просто C». Преимущество C++ состоит в том, что он является самым популярным объектно-ориентированным языком, но он также признан довольно загадочным. Опять же, необходима определенная степень профессионализма, чтобы запрограммировать приложение на C++, понятное другим. Пакеты, которые автоматически генерируют код C++ из заданного пользователем псевдокода, помогают облегчить проблему, но тогда мы сталкиваемся с просьбой ко всем пользователям использовать один и тот же генератор C++, что является еще одной проблемой того же масштаба.

Вышеуказанные два являются «традиционными» вариантами. Теперь обратимся к более новым языкам, менее известным в научном сообществе.

## Питон
Python — это объектно-ориентированный расширяемый интерпретируемый язык. Он работает практически на всех системах Unix, а также на платформах DOS/Windows и на Mac. Это бесплатно и поставляется с полным исходным кодом. Начать использовать Python очень просто — на простом уровне он напоминает Basic и может использоваться в интерактивном режиме так же, как и Basic. Однако он поддерживает объектные методы и хорошо "масштабируется". Масштабирование указывает на относительную сложность написания небольших и больших приложений. Средства объекта помогают и поощряют писать приложение небольшими частями. Эти маленькие части могут быть объединены в большую программу, а маленькие части могут также использоваться в других приложениях.
Еще одним преимуществом Python является его расширение способность. Можно написать библиотеку объектов на C, C++ или родном Python, которую затем можно динамически или статически связать с основной системой Python и использовать в программах Python. Это можно использовать для создания программируемого приложения, такого как пакет для построения графиков данных. Можно добавить в интерпретатор пакет, содержащий команды для настройки ваших графиков и фактического построения данных. Этому интерпретатору Python+графики можно дать другое имя, например "pygraph", и вызвать его как команду. Интерпретатор будет обрабатывать графические команды и выполнять их. Однако в то же время вы можете использовать любую другую допустимую команду Python в качестве команды для этой графической программы! Таким образом, один графический входной файл для этой программы мог сначала вычислить результат, а затем обработать его и построить его.

Переход от этого к системам пакетов Python+, таким как программы анализа данных или программы управления экспериментами, довольно очевиден. Это также может в некоторой степени решить упомянутую выше дилемму об использовании C++. Профессиональный программист может создать четко определенный пакет библиотеки с четко определенным интерфейсом на C++, который может быть включен в программы Python для использования. Поскольку Python почти так же читаем, как и Fortran, «нормальный человек» (то есть тот, кто не является профессиональным программистом) может использовать эту библиотеку в своих программах. И профессионалы, которые хотят мощности и эффективности C или C++, а также группа, которая должна использовать результат и уметь читать и понимать программу, могут быть довольны.

Для Python существует несколько инструментов графического интерфейса, а пакет графической визуализации сейчас находится в стадии бета-тестирования. Также существует числовое расширение Python (пакет C, как описано выше в разделе расширений), которое имеет встроенную поддержку операций с целым массивом и матрицей (которые выполняются со скоростью скомпилированного кода C, а не со скоростью интерпретируемого Python. )

Чтобы узнать, что Python может делать с этим пакетом для числовых вычислений, перейдите по этой ссылке. Это также даст вам представление о том, как выглядит Python, и позволит вам оценить его удобочитаемость. Также ознакомьтесь с учебным пособием по Python на веб-странице Python по ссылке ниже (подссылка «Полная информация о документации по Python»).

Статья о численном программировании на Python появилась в выпуске журнала Computers in Physics за май/июнь 1996 года. Дополнительную информацию о Python можно найти в группе новостей comp.lang.python или на веб-странице Python. Особый интерес представляет страница предоставленного программного обеспечения Python, на которой описываются дополнительные пакеты, доступные для Python. Это расширения в духе, упомянутом выше, которые добавляют новые функциональные возможности к основному языку.
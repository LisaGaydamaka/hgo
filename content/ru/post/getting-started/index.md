---
title: Про Git
subtitle: Узнайте о системе контроля версий Git и о том, как она работает с GitHub.

# Summary for listings and search engines
summary: Узнайте о системе контроля версий Git и о том, как она работает с GitHub.

# Link this post with a project
projects: []

# Date published
date: '2022-05-07T00:00:00Z'

# Date updated
# lastmod: '2022-05-07T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Hostinger**](https://www.hostinger.com.ua/rukovodstva/wp-content/uploads/sites/8/2017/04/osnovnye-git-komandy.png)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin

tags:
  - Git

categories:
  - Programming
---

## Про контроль версиями и Git.

<!-- ## About version control and Git -->
---
<!-- 
A version control system, or VCS, tracks the history of changes as people and teams collaborate on projects together. As developers make changes to the project, any earlier version of the project can be recovered at any time.

Developers can review project history to find out:

- Which changes were made?
- Who made the changes?
- When were the changes made?
- Why were changes needed?

VCSs give each contributor a unified and consistent view of a project, surfacing work that's already in progress. Seeing a transparent history of changes, who made them, and how they contribute to the development of a project helps team members stay aligned while working independently.

In a distributed version control system, every developer has a full copy of the project and project history. Unlike once popular centralized version control systems, DVCSs don't need a constant connection to a central repository. Git is the most popular distributed version control system. Git is commonly used for both open source and commercial software development, with significant benefits for individuals, teams and businesses.

- Git lets developers see the entire timeline of their changes, decisions, and progression of any project in one place. From the moment they access the history of a project, the developer has all the context they need to understand it and start contributing.

- Developers work in every time zone. With a DVCS like Git, collaboration can happen any time while maintaining source code integrity. Using branches, developers can safely propose changes to production code.

- Businesses using Git can break down communication barriers between teams and keep them focused on doing their best work. Plus, Git makes it possible to align experts across a business to collaborate on major projects.

## About repositories
---

A repository, or Git project, encompasses the entire collection of files and folders associated with a project, along with each file's revision history. The file history appears as snapshots in time called commits. The commits can be organized into multiple lines of development called branches. Because Git is a DVCS, repositories are self-contained units and anyone who has a copy of the repository can access the entire codebase and its history. Using the command line or other ease-of-use interfaces, a Git repository also allows for: interaction with the history, cloning the repository, creating branches, committing, merging, comparing changes across versions of code, and more.

Through platforms like GitHub, Git also provides more opportunities for project transparency and collaboration. Public repositories help teams work together to build the best possible final product.

## How GitHub works
---

GitHub hosts Git repositories and provides developers with tools to ship better code through command line features, issues (threaded discussions), pull requests, code review, or the use of a collection of free and for-purchase apps in the GitHub Marketplace. With collaboration layers like the GitHub flow, a community of 15 million developers, and an ecosystem with hundreds of integrations, GitHub changes the way software is built.

GitHub builds collaboration directly into the development process. Work is organized into repositories where developers can outline requirements or direction and set expectations for team members. Then, using the GitHub flow, developers simply create a branch to work on updates, commit changes to save them, open a pull request to propose and discuss changes, and merge pull requests once everyone is on the same page.

## GitHub and the command line
---
#### Basic Git commands

To use Git, developers use specific commands to copy, create, change, and combine code. These commands can be executed directly from the command line or by using an application like GitHub Desktop. Here are some common commands for using Git:

- `git init` initializes a brand new Git repository and begins tracking an existing directory. It adds a hidden subfolder within the existing directory that houses the internal data structure required for version control.

- `git clone` creates a local copy of a project that already exists remotely. The clone includes all the project's files, history, and branches.

- `git add` stages a change. Git tracks changes to a developer's codebase, but it's necessary to stage and take a snapshot of the changes to include them in the project's history. This command performs staging, the first part of that two-step process. Any changes that are staged will become a part of the next snapshot and a part of the project's history. Staging and committing separately gives developers complete control over the history of their project without changing how they code and work.

- `git commit` saves the snapshot to the project history and completes the change-tracking process. In short, a commit functions like taking a photo. Anything that's been staged with git add will become a part of the snapshot with git commit.

- `git status` shows the status of changes as untracked, modified, or staged.

- `git branch` shows the branches being worked on locally.

- `git merge` merges lines of development together. This command is typically used to combine changes made on two distinct branches. For example, a developer would merge when they want to combine changes from a feature branch into the main branch for deployment.

- `git pull` updates the local line of development with updates from its remote counterpart. Developers use this command if a teammate has made commits to a branch on a remote, and they would like to reflect those changes in their local environment.

- `git push` updates the remote repository with any commits made locally to a branch.

## Models for collaborative development
---

There are two primary ways people collaborate on GitHub:

1. Shared repository
1. Fork and pull

With a shared repository, individuals and teams are explicitly designated as contributors with read, write, or administrator access. This simple permission structure, combined with features like protected branches, helps teams progress quickly when they adopt GitHub.

For an open source project, or for projects to which anyone can contribute, managing individual permissions can be challenging, but a fork and pull model allows anyone who can view the project to contribute. A fork is a copy of a project under a developer's personal account. Every developer has full control of their fork and is free to implement a fix or a new feature. Work completed in forks is either kept separate, or is surfaced back to the original project via a pull request. There, maintainers can review the suggested changes before they're merged. -->


Система контроля версий, или VCS, отслеживает историю изменений, когда люди и команды совместно работают над проектами. Когда разработчики вносят изменения в проект, любая более ранняя версия проекта может быть восстановлена ​​в любое время.

Разработчики могут просмотреть историю проекта, чтобы узнать:

- Какие изменения были внесены?
- Кто внес изменения?
- Когда были внесены изменения?
- Зачем нужны были изменения?

VCS дают каждому участнику единое и последовательное представление о проекте, выявляя работу, которая уже выполняется. Просмотр прозрачной истории изменений, сведений о том, кто их внес, и того, какой вклад они вносят в разработку проекта, помогает членам команды сохранять согласованность действий при независимой работе.

В распределенной системе контроля версий каждый разработчик имеет полную копию проекта и историю проекта. В отличие от когда-то популярных централизованных систем управления версиями, DVCS не требуют постоянного подключения к центральному репозиторию. Git — самая популярная распределенная система контроля версий. Git обычно используется как для разработки программного обеспечения с открытым исходным кодом, так и для коммерческого, что дает значительные преимущества для отдельных лиц, команд и предприятий.

- Git позволяет разработчикам видеть всю хронологию своих изменений, решений и прогресса любого проекта в одном месте. С момента доступа к истории проекта у разработчика есть весь контекст, необходимый для того, чтобы понять его и начать вносить свой вклад.

- Разработчики работают во всех часовых поясах. С DVCS, такой как Git, совместная работа может происходить в любое время при сохранении целостности исходного кода. Используя ветки, разработчики могут безопасно предлагать изменения в производственном коде.

— Компании, использующие Git, могут разрушить коммуникационные барьеры между командами и сосредоточить их на выполнении своей работы наилучшим образом. Кроме того, Git позволяет объединять экспертов по всему бизнесу для совместной работы над крупными проектами.

## О репозиториях
---

Репозиторий или проект Git включает в себя всю коллекцию файлов и папок, связанных с проектом, а также историю изменений каждого файла. История файлов отображается в виде моментальных снимков во времени, называемых фиксациями. Коммиты могут быть организованы в несколько линий разработки, называемых ветвями. Поскольку Git — это DVCS, репозитории — это автономные единицы, и любой, у кого есть копия репозитория, может получить доступ ко всей кодовой базе и ее истории. Используя командную строку или другие простые в использовании интерфейсы, репозиторий Git также позволяет: взаимодействовать с историей, клонировать репозиторий, создавать ветки, фиксировать, объединять, сравнивать изменения в разных версиях кода и многое другое.

Благодаря таким платформам, как GitHub, Git также предоставляет больше возможностей для прозрачности проектов и совместной работы. Публичные репозитории помогают командам работать вместе над созданием наилучшего конечного продукта.

## Как работает GitHub
---

GitHub размещает репозитории Git и предоставляет разработчикам инструменты для отправки более качественного кода с помощью функций командной строки, проблем (потоковые обсуждения), запросов на вытягивание, проверки кода или использования набора бесплатных и платных приложений в GitHub Marketplace. Благодаря таким уровням совместной работы, как поток GitHub, сообществу из 15 миллионов разработчиков и экосистеме с сотнями интеграций, GitHub меняет способ создания программного обеспечения.

GitHub встраивает совместную работу непосредственно в процесс разработки. Работа организована в репозитории, где разработчики могут наметить требования или направления и установить ожидания для членов команды. Затем, используя поток GitHub, разработчики просто создают ветку для работы с обновлениями, фиксируют изменения, чтобы сохранить их, открывают запрос на вытягивание, чтобы предлагать и обсуждать изменения, и объединяют запросы на вытягивание, когда все находятся на одной странице.

## GitHub и командная строка
---
#### Основные команды Git

Чтобы использовать Git, разработчики используют специальные команды для копирования, создания, изменения и объединения кода. Эти команды можно выполнять непосредственно из командной строки или с помощью приложения, такого как GitHub Desktop. Вот несколько общих команд для использования Git:

- `git init` инициализирует совершенно новый репозиторий Git и начинает отслеживать существующий каталог. Он добавляет скрытую подпапку в существующий каталог, в которой находится внутренняя структура данных, необходимая для контроля версий.

- `git clone` создает локальную копию проекта, который уже существует удаленно. Клон включает в себя все файлы, историю и ветки проекта.

- `git add` вносит изменения. Git отслеживает изменения в кодовой базе разработчика, но необходимо подготовить и сделать моментальный снимок изменений, чтобы включить их в историю проекта. Эта команда выполняет подготовку, первую часть этого двухэтапного процесса. Любые поэтапные изменения станут частью следующего моментального снимка и частью истории проекта. Отдельное размещение и коммит дает разработчикам полный контроль над историей своего проекта без изменения того, как они кодируют и работают.

- `git commit` сохраняет снимок в историю проекта и завершает процесс отслеживания изменений. Короче говоря, фиксация работает так же, как фотографирование. Все, что было подготовлено с помощью git add, станет частью моментального снимка с коммит git.

- `git status` показывает статус изменений как неотслеживаемые, измененные или подготовленные.

- `git branch` показывает ветки, над которыми работают локально.

- `git merge` объединяет линии разработки вместе. Эта команда обычно используется для объединения изменений, сделанных в двух разных ветвях. Например, разработчик может выполнить слияние, если он хочет объединить изменения из функциональной ветки в основную ветку для развертывания.

- `git pull` обновляет локальную линию разработки обновлениями удаленного аналога. Разработчики используют эту команду, если товарищ по команде сделал коммиты в ветке на удаленном компьютере, и они хотели бы отразить эти изменения в своей локальной среде.

- `git push` обновляет удаленный репозиторий любыми локальными фиксациями в ветке.

## Модели совместной разработки
---

Есть два основных способа совместной работы на GitHub:

1. Общий репозиторий
1. Вилка и тяга

В общем репозитории отдельные лица и группы явно назначаются участниками с правами чтения, записи или администратора. Эта простая структура разрешений в сочетании с такими функциями, как защищенные ветки, помогает командам быстро развиваться при переходе на GitHub.

Для проекта с открытым исходным кодом или для проектов, в которые может внести свой вклад любой желающий, управление отдельными разрешениями может быть сложной задачей, но модель разветвления и извлечения позволяет любому, кто может просматривать проект, внести свой вклад. Форк — это копия проекта под личным кабинетом разработчика. Каждый разработчик имеет полный контроль над своей вилкой и может реализовать исправление или новую функцию. Работа, выполненная в разветвлениях, либо хранится отдельно, либо возвращается в исходный проект через запрос на вытягивание. Там сопровождающие могут просмотреть предложенные изменения перед их слиянием.
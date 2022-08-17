# Personal website V2

## Contents
- [Keywords](#keywords)
- [Introduction](#introduction)
  - [Description](#description)
  - [Context](#context)
  - [V2 Proposal](#proposition)
- [Installation](#installation)
- [Use](#use)
- [Progress](#progress)
- [Helpful links](#links)

## Keywords <a class="anchor" id="keywords"></a>

- Personal website
- BEM
- POO
- API fetch

## Introduction <a class="anchor" id="introduction"></a>

### Description <a class="anchor" id="description"></a>

"Personal website V2" aims to create V2 of my website. 

### Context <a class="anchor" id="context"></a>

The V1 of my website is very simple. When I created it, I had just a basic knowledge
of HTML and CSS, and even if I implemented JS and PHP files, I created them from YT tutorials without 
knowing exactly how they worked.

So, and after acquiring new skills and knowledge thanks to my academic training, I decided to improve
my website and create a V2.

### V2 Proposal <a class="anchor" id="proposition"></a>

This new version contains four main sections:
- Story (About me)
- Portfolio (GitHub repositories)
- Read (what I have read)
- Videos (YT videos)
- Contact form (form)

In addition to, there will be a home page with links to these sections.

Concerning difference between V1 and V2, you can find in table here below some features implemented 
on V1 and what I want to implement on V2 :

|  #  | Technology | Features on V1 | Features for V2 |
|:---:|:----------:|:--------------:|:---------------:|
|  1  |    HTML    |       -        | Improved syntax |
|  2  |    CSS     |     JQuery     |     JQuery      |
|  3  |            |       -        |       BEM       |
|  4  |     JS     |    Arrow up    |    Arrow up     |
|  5  |            |       -        |    Carrousel    |
|  6  |            |       -        |   Pagination    |
|  7  |            |       -        |      Modal      |
|  8  |            |       -        |       POO       |
|  9  |            |       -        |    API fetch    |
| 10  |    PHP     |  Contact form  |  Contact form   |

I decided not use Django Framework because my host does not accepte it. For that, I will need 
to change my current subscription.

Also, I would like to improve my knowledge of CSS. Because of that, I will not implement a 
framework as Bootstrap, but a methodology as BEM.

Finally, I pretend to have an approach Domain Driven Design (DDD) in order to focus on domains 
(sections) of my website. That's why I think implement models (POO) for every section:

| Domains (section) | Models  |
|:-----------------:|:-------:|
|       Story       | Chapter |
|     Portfolio     | Project |
|       Read        |  Book   |
|      Videos       |  Video  |
|   Contact form    |  Form   |

## Installation <a class="anchor" id="installation"></a>

Python version : 3.9.4

To get project, launch :
```
git clone https://github.com/edaucohe/personal_website.git
```

To create virtual environment, go into the folder `../personal_website/` and launch :
```
python -m venv env  
```

To activate virtual environment, launch :

- In windows
```
source env/Scripts/activate
```
- In Linux
```
source env/bin/activate
```

To verify...

## Use <a class="anchor" id="use"></a>

To fill

## Progress <a class="anchor" id="progress"></a>

To fill

## Helpful links <a class="anchor" id="links"></a>

Personal website V1: https://edgarcortes.com/

To see website progress: https://github.com/users/edaucohe/projects/3

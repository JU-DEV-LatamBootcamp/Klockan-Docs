# Klockan-Docs

## Introduction

This project was created using [c4builder](https://adrianvlupu.github.io/C4-Builder/)

#### Requirements

Install npm of computer

Open the terminal and run the following commands to start compiling the documentation

```bash
npm i -g c4builder
```

#### To run 

Open the terminal on Klockan-Docs folder

```bash
c4builder build
c4builder site
```




> Note on using local images inside markdown files
>
> Images should be placed next to the markdown file using them.
>
> All of them will be copied over to the `docs` folder either in `/` (in the case of a single MD/PDF file) or following the same folder structure as in `src`, so make sure they have unique names.  

## Abstractions used

![C4Model](https://c4model.com/img/abstractions.png)

### Person

However you think about your users (as actors, roles, personas, etc), people are the various human users of your software system. 

### Software System

A software system is the highest level of abstraction and describes something that delivers value to its users, whether they are human or not. This includes the software system you are modelling, and the other software systems upon which your software system depends (or vice versa). 

# Movie recommender system

Simple movie recommender website created with streamlit, python using jupyter notebook.

## Table of contents

* [General Info](#general-info)
* [Techs Used](#technologies-used)
* [Setup](#setup)

## General Info

This website will recommend you movies, according to  

* Your Favourite Genres
* Movies you search 
* your like/dislike on popular movies 


## Technologies Used

This Project is created with:

* Streamlit version : 1.9.0
* Numpy version : 1.22.4
* Pandas version : 1.4.2


## Setup

This project includes a file(main database) having size greater than 100MB, therefore Github LFS(Large File System) is used to push it on github.
You need to install LFS in your pc/laptop before cloning this repo, else the file will not be cloned properly.

### Steps to clone this repo:

#### 1. Installation of Github LFS(Large File System):

##### For windows :

* Navigate to [Github LFS](https://git-lfs.github.com/) and click Download.
* When you open this file, Windows will run a setup wizard to install Git LFS.

##### For Mac/Linux :
* You can Navigate to [Github LFS](https://git-lfs.github.com/) and click Download.
* Then locate and unzip the file. On terminal change the current working directory into the folder you downloaded and unzipped.
* To install the file, run this command:
```
$ ./install.sh
 > Git LFS initialized.
 ```
 ##### Alternative For Mac :
* You can install Git LFS using a package manager:
* To use Homebrew, run ```$ brew install git-lfs```
* To use MacPorts, run ```port install git-lfs```


 #### 2. After installing run following commands in your terminal/git bash to clone the repo:

```
$ git lfs install
> Git LFS initialized.

```
#### 4. fork the repo than clone using git clone link
#### 5. To run this project open the files in any IDE(VSCode preferred) and in the terminal run:

```
streamlit run app.py
```


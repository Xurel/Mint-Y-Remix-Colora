# Mint-Y-Colora Theme (Compatible with latest Mint 19 and Mint-Y releases)

## The goal is to make a script that makes it easy to change the colours of the Mint-Y theme of Linux Mint.
 We start from the source files at https://github.com/linuxmint/mint-themes and let loose a few scripts to change the colour accent.

More information can be found here. Including many youtube tutorials.

http://erikdubois.be/category/themes/mint-y-based-themes/
Note: This repository is a fork from Erik Dubois' project, which doesn't work with latest Mint and Mint-Y theme.


# Installation

## Get the latest version of the Linux Mint themes and unzip the folder
https://github.com/linuxmint/mint-themes

## Download and unzip this repository

Copy/paste the 4 scripts inside

	Mint-Y-Remix-Colora
	
to the folder

	mint-themes

Go to properties and mark the 4 scripts as executable.
![Screenshots](http://i.imgur.com/vXsOaFL.gif)


Let us run the scripts.

## 1. Change the colour

Use the script to change the colour. Find yourself a nice colour with gpick or online.
It should be a hexadecimal notation but without the hashtag or #. Change the color in the script.
## Read the script for more info.

	1-change-color.sh


## 2. Delete old assets or png's

Old png's will have to be deleted. They are still the original green ones. 
Read the script for more info.

	2-delete-assets.sh


## 3. Make new assets or png's

This is the most important part. New png's will be created with your colour.

	3-make-assets.sh


## 4. Renaming

We will run the last script nr 4

	- to rename the folders
	- to move the folders to ~/.themes
	- to change the content of the three index.themes

Follow the instructions in the script.


-------------------------------------------------
# That is the fun in Linux.

You can do whatever <b>Y O U</b> want.

Share the knowledge.

Erik shares his knowledge at http://erikdubois.be
------------------------------------------------

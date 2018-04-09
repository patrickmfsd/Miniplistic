![Logo](https://github.com/patrickmfsd/Miniplistic/blob/master/images/site-logo.png "Miniplistic Logo")

# Miniplistic Theme (Version 1.3)

Created by: Patrick Mifsud

## Contents
1. [About](#about)
2. [Screenshots](#screenshots)
	1. [Light/Normal Mode](#light/normal_mode)
	2. [Dark Mode](#dark_mode)
3. [How To Create A Post](#how_create_a_post)
	1. [Post Format](#post_format)
4. [Change Log](#change_log)

## About

Welcome to the repository for the Miniplistic Theme.

This repository contains the files used for generating the website. The theme is designed for Jekyll, a static site generator and uses GitHub Pages for hosting. 

Features of the site:

- Custom Dark Mode
- Responsive Theme
- Easy Navigation
- Uses Bootstrap 
- Uses Font Awesome
- Uses Animate.css

## Screenshots

### Light/Normal Mode
![Light/Normal Mode](https://github.com/patrickmfsd/Miniplistic/blob/master/screenshots/LightMode.png)


### Dark Mode
![alt text](https://github.com/patrickmfsd/Miniplistic/blob/master/screenshots/DarkMode.png)

## How create a post 

1. Create a Markdown file with the following file name format "YYYY-MM-DD-Post-Name.md". 
2. Follow the templates below for each kind of post. 
3. Save Announcements posts in "\_posts" folder.
4. Submit pull request on GitHub.

A useful resource on Markdown can be found [here](https://daringfireball.net/projects/markdown/).


### Post Format

	---
	layout: post
	title: 
	author: 
	categories: [ ]
	---

	Short Description

	<!-- more -->

	Post Content
	

## Change Log

### What's new in v2.0 (9 April 2017)

- Updated and Migrated to Bootstrap 4
	- Updated JS and jQuery scripts
	- Added Popper.js 
- Page Links for nav bar can now be set in _config.yml
- Add support for Jekyll Pagination 
- Added 404 page
- Added Dismissible Alert in Header 
- Changed Dark Mode Background to a nicer grey
- Bug Fixes
- Format Fixes
- Code Tidy Up



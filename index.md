---
layout: default
title: Intro & Setup
nav_order: 1
---

## Data Organization in Spreadsheets for the Health Sciences

Good data organization is the foundation of any research project. Most researchers have data in spreadsheets, so it’s the place that many research projects start.

We organize data in spreadsheets in the ways that we as humans want to work with the data, but computers require that data be organized in particular ways. In order to use tools that make computation more efficient, such as programming languages like R or Python, we need to structure our data the way that computers need the data. Since this is where most research projects start, this is where we want to start too!

## In this lesson, you will learn:

- Good data entry practices - formatting data tables in spreadsheets
- How to avoid common formatting mistakes
- Approaches for handling dates in spreadsheets
- Basic quality control and data manipulation in spreadsheets
- Exporting data from spreadsheets

In this lesson, however, you will not learn about data analysis with spreadsheets. Much of your time as a researcher will be spent in the initial ‘data wrangling’ stage, where you need to organize the data to perform a proper analysis later. It’s not the most fun, but it is necessary. In this lesson you will learn how to think about data organization and some practices for more effective data wrangling. With this approach you can better format current data and plan new data collection so less data wranglin

## Pre-Workshop Setup

Download this data file to your computer: OSF Link

## About the data

The data for this lesson is a part of the Health Sciences Data Carpentry workshop. It is a teaching version of the Alzheimer’s Disease Neuroimaging Initiative (ADNI) data. The data in this lesson is a subset of the teaching version that has been intentionally ‘messed up’ for this lesson.


The original datasets can be found here and used with approval ADNI Access Data and Samples

This data set requires downloading a DUA form and siging off prior to download. 
For more information about the dataset 

### Software

To interact with spreadsheets, we can use LibreOffice, Microsoft Excel, Gnumeric, Onlyoffice, WPS office or other programs. Commands may differ a bit between programs, but the general ideas for thinking about spreadsheets are the same.

**For this lesson, we will mainly use Microsoft Excel.** If you do not have access to Microsoft Excel, you can also use LibreOffice, which is a free, open source spreadsheet program. Many functions will be similar to Excel. 

macOS users who use Apple's Numbers application should note that it does not contain some of the features (particularly data validation) that we will be using. Please use LibreOffice or Microsoft Excel instead.

#### LibreOffice installation (optional)

##### Windows/macOS

- Download the Installer
- Install LibreOffice by going to [the installation page](https://www.libreoffice.org/download/libreoffice-fresh/). The version for Windows/Mac should automatically be selected. Click Download Version X.X.X (whichever is the most recent version).
- Install LibreOffice
- Once the installer is downloaded, double click on it and LibreOffice should install.

##### Linux

- Download the Installer
- Install LibreOffice by going to [the installation page](https://www.libreoffice.org/download/libreoffice-fresh/). The version for Linux should automatically be selected. Click Download Version X.X.X (whichever is the most recent version).
- Install LibreOffice
- Once the installer is downloaded, double click on it and LibreOffice should install.
- package manager option:
   * pacman (Arch): `pacman -S libreoffice`
   * yum (Fedora, CentOS): `yum install libreoffice`
   * apt (Debian, Ubuntu): `apt install libreoffice`

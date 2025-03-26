# **Web Scraping Lab**

Estimated time needed: **30** minutes

## Objectives

After completing this lab you will be:

* Familiar with the basics of the `BeautifulSoup` Python library
* Be able to scrape webpages for data and filter the data

---

## Table of Contents

- [Beautiful Soup Object](#BSO)
  - Tag
  - Children, Parents, and Siblings
  - HTML Attributes
  - Navigable String
- [Filter](#filter)
  - find All
  - find
  - HTML Attributes
  - Navigable String
- [Downloading And Scraping The Contents Of A Web](#DSCW)

---

## Overview

In this lab, we will be using Python and several Python libraries for web scraping. Some libraries might already be installed in your lab environment or in SN Labs. Others will need to be installed by you. Below, we will guide you through installing necessary libraries and using them for web scraping tasks.

---

## Prerequisites

Run the following commands to install the required libraries:

```bash
!pip install bs4
!pip install requests pandas html5lib

---
layout: post
title: "Automated Testing using Selenium and BrowserStack"
date: 2019-07-28 21:25:00
image: '/assets/img/'
description: 'Getting started with automated testing'
tags:  
- selenium 
- browserstack
- automated testing  
categories:
- Automated Testing
twitter_text: 'Automated testing using Selenium and BrowserStack'
---

# Automated Selenium Testing - BrowserStack

This repository contains information about how to do automated testing using Selenium in order to test different desktop browsers with BrowserStack.

## Documentation 

The project has detailed documentation, including a "getting started" guide.

## "Getting Started" Guide

1. #### Selenium with Python 

Before start running Selenium tests with Python, ensure the following library is installed:

If pip is not installed, you can install it using: 

{% highlight bash %}
$ sudo pip install selenium
{% endhighlight %}

To get started, import modules from Selenium to get access to code from another module by importing the file/function:

{% highlight python %}
import os
from selenium import webdriver
from selenium.webdriver.common.keys import Keys
from selenium.webdriver.common.desired_capabilities import DesiredCapabilities
from selenium.webdriver.common.by import By
{% endhighlight %} 

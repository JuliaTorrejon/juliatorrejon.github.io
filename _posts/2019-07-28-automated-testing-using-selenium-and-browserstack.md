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
This repository contains information about how to do automated testing using Selenium to test different desktop browsers with BrowserStack.


The project has detailed documentation on how install, register and how to initiate a GitLab Runner in order to run the script for desktop browsers.

GitLab Runner Installation
Download the binary for you system:
{%highlight bash%}sudo curl --output /usr/local/bin/gitlab-runner https://gitlab-runner-downloads.s3.amazonaws.com/latest/binaries/gitlab-runner-darwin-amd64{% endhighlight %}

Give it permissions to execute:
{%highlight bash%}sudo chmod +x /usr/local/bin/gitlab-runner{%endhighlight%}

GitLab Runner Registration
Run the following command:
{%highlight bash%}gitlab-runner register{%endhighlight%}
Enter your GitLab instance URL:
Please enter the gitlab-ci coordinator URL (e.g. https://gitlab.com )
https://gitlab.com
Enter the token you obtained to register the Runner:
Please enter the gitlab-ci token for this runner
xxx

GitLab Runner Start
This command starts the GitLab Runner service.
{%highlight bash%}gitlab-runner start{%endhighlight%}

Test
Navigate to CI/CD > Pipelines and click on "Run Pipeline" to trigger the pipeline in case it has not run automatically.

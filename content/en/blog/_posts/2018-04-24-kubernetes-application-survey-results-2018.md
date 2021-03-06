---
title: 'Kubernetes Application Survey 2018 Results'
author: mattfarina
slug: kubernetes-application-survey-results-2018
---

Understanding how people use or want to use Kubernetes can help us shape everything from what we build to how we do it. To help us understand how application developers, application operators, and ecosystem tool developers are using and want to use Kubernetes, the Application Definition Working Group recently performed a survey. The survey focused in on these types of user roles and the features and sub-projects owned by the Kubernetes organization. That included kubectl, Dashboard, Minikube, Helm, the Workloads API, etc.

The results are in and the [raw data is now available](https://docs.google.com/spreadsheets/d/12ilRCly2eHKPuicv1P_BD6z__PXAqpiaR-tDYe2eudE/edit?usp=sharing) for everyone.

There is too much data to summarize in a single blog post and we hope people will be able to find useful information by pouring over the data. Here are some of the highlights that caught our attention.

## Participation

First, I would like to thank the 380 people who took the survey and provided feedback. We appreciate the time put into to share so much detail.

## 6.8x Response Increase

In the summer of [2016 we ran a survey on application usage](https://kubernetes.io/blog/2016/08/sig-apps-running-apps-in-kubernetes). Kubernetes was much newer and the number of people talking about operating applications was much smaller.

The number of respondents in the past year and 10 months increased at a rate of 6.8 times.

## Where Are We In Innovation Lifecycle?

![Minikube operating system usage](/images/blog/survey-results/2018-application-survey/minikube-os-usage.png)

Minikube is used primarily be people on MacOS and Linux. Yet, according to the 2018 Stack Overflow survey, [almost half of developers use Windows as their primary operating system](https://insights.stackoverflow.com/survey/2018/#technology-developers-primary-operating-systems). This is where Minikube would run.

Seeing differences from other data sets is worth looking more deeply at to better understand our audience, where Kubernetes is at, and where it is on the journey it's headed.

## Plenty of Custom Tooling

![Custom Tooling](/images/blog/survey-results/2018-application-survey/custom-tooling.png)

Two thirds of respondents work for organizations developing their own tooling to help with application development and operation. We wondered why this might happen so we asked why as a follow-up question. _44% of people who took the survey told us why they do it._

## App Management Tools

![Custom Tooling](/images/blog/survey-results/2018-application-survey/tool-manage-apps.png)

Only 4 tools were in use by more than 10% of those who took the survey with Helm being in use by 64% of them. Many more tools were used by more than 1% of people including those we directly asked about and the space for people to fill in those we didn't ask about. The long tail, captured in the survey, contained more than 80 tools in use.

## Want To See More?

As the [Application Definition Working Group](https://github.com/kubernetes/community/tree/master/wg-app-def) is working through the data we're putting observations into a [Google Slides Document](http://bit.ly/2qTkuhx). This is a living document that will continue to grow while we look over and discuss the data.

There is [a session at KubeCon where the Application Definition Working Group will be meeting](https://kccnceu18.sched.com/event/DxV4) and discussing the survey. This is a session open to anyone in attendance, if you would like to attend.

While this working group is doing analysis and sharing it, we want to encourage others to look at the data and share any insights that might be gained.

_Note, the survey questions were generated by the application definition working group with the help of people working on various sub-projects included in the survey. This is the reason some sub-projects have more and varied questions compared to some others. The survey was shared on social media, on mailing lists, in blog posts, in various meetings, and beyond while collecting information for two weeks._
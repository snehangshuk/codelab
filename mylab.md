---
id: bootcamp-journey-setup
summary: In this codelab, you'll be able understand what Kubernetes is installthe tools required to get started with Kubernetes cluster
status: [published]
authors: Snehangshu Karmakar
categories: Web
tags: devtest,web
feedback link: https://github.com/snehangshuk/codelab/issues
duration: 2

---

# Bootcamp Journey Setup Guide
**Last Updated:** 2022-08-31

[Setup Feedback](https://github.com/snehangshuk/codelab/issues)


## Laptop Setup Validation

If you have completed [go/engdayone](http://go/engdayone) steps (also known as [go/HowToSSH](http://go/HowtoSSH)) you will be able to pass all of the validations. If you run into issues during setup or validation please see the Troubleshooting Setup section or reach out to support at #techlounge or [go/helpin](http://go/helpin).

### **1. Validate That Eng Tools Are Installed**

Before you can create SSH keys you’ll need to have the eng_tools installed. 

To validate `eng_tools` are installed 
From your terminal, run the following command:
```
$ mint -h
```
If you see the help documentation for `mint` go to *step 2* on go/HowToSSH. If not, follow *step 1* on [go/HowToSSH](http://go/howtossh)


### **2. Set Up Your SSH Keys**

If you’ve completed *step 2 - 4* on [go/HowToSSH](go/howtossh) and your keys are working proceed to the next validation step.

In **Gerrit** with the steps in [go/HowToSSH](http://go/howtossh)
(keys propagate at 10 minutes after the hour, i.e. 12:10pm, and in some cases can take up to 2 hours to complete)

In **GitHub** with the steps to [manually copy keys to GitHub](https://docs.google.com/document/d/1zAMPT7TknuP0tparZxR-I7rLtlk2vJxtLORUq22VShs/edit#heading=h.h0uom4qlx37x)

> aside negative
> 
> **Note:** For **GitHub** you might not need to copy the SSH keys as the current authentication uses Certificate Authority.

### **3. Verify Mint And Keys Are Working Together**

From your terminal, run the following command:
```
$ mint -h
```
You should see the help documentation for mint. If this fails, contact #techlounge, you may be missing several things.

Test Gerrit repo
From your terminal, move to a folder you’d like to store code in, run the following command:
```
$ mint clone bootcamp-backend
```
You should see something like this:
```
:heavy_check_mark: bootcamp-backend checked out to /Users/jsmith
```


## Troubleshooting Setup
Duration: 02:00

If you ran into any problems during the laptop setup reach out to support on slack [#techlounge](https://linkedin-randd.slack.com/archives/CV2LB21FG) or go/helpin. If you’d like to troubleshoot yourself here are some common things you can try.

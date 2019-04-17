---
title: "The Total Cost of Running & Maintaining a Mobile App"
description: "After you've designed and built your mobile app, you have to monitor, maintain and support it for the life of the app.  What's involved?"
date: "2018-05-23T14:33:25Z"
draft: false
image: ""
tags:
  - Mobile App Development
---
After you've designed and built your mobile app, you have to monitor, maintain and support it for the life of the app.  What's involved?  There's a lot more effort than you might think.

## Hosting

Mobile apps usually need a server in order to operate, called an API.  The API is responsible for storing and retrieving data.  For example, when you create a new account as a user, the mobile app talks to the API to create that user.

At Foxbox, we host our client's APIs on **high-availability infrastructure**.  This is a server farm that has redundancy built in on every level, so that if any single component fails, your app still runs.  If the API server goes down, there are more just like it that continue to operate.  If the database server goes down, there's a failover server that takes over automatically.  Even if the power goes out, there's a backup generator to keep the servers running!

This type of hosting is called high availability, because your app is available as close to 100% of the time as possible.  Building and configuring this type of high availability infrastructure is not a trivial task, but it's critical to ensure your app always works.

## Monitoring

### API Monitoring

If your app goes down for any reason, the engineering team needs to know about it.  At Foxbox, we have a monitoring system that constantly checks to ensure the servers and the API is running 24x7.  If anything happens, **it immediately notifies our engineering team**.  When this happens, we respond to the problem and take action.

### Error Monitoring

It's common for errors to happen when users interact with your app in a way that you didn't anticipate.  We call these bugs, and usually they are small, but sometimes they are serious.

Both the mobile app and the API needs error monitoring to ensure that when an error happens, an alert is triggered and the tech team is notified.  At Foxbox, **we actively monitor our clients' apps and the API and trigger alerts when an error occurs**.  We respond quickly to fix the bugs in order of urgency.

Here's a view of the error dashboard of one of our apps.  The tool is called Sentry and it notifies the team on Slack, our internal chat tool.  The first one is happening frequently, and the engineering team is working on a fix as we speak.

![](/img/blog/managed-support-api-errors.png)

### Performance Monitoring

You need your API to be fast so that when users interact with your app, the experience is as  fast as possible.  This is why we actively monitor the performance of your API.  We're able to identify performance issues in any part of the app and we use tools to give us detailed insights into what's happening.

For example, if you have a surge of users, we'll scale out your servers to support the added usage.  Or if just one component, like searching, is really slow, we'll dive in and figure out why so we can fix it.

For an app to run smoothly, _everything has to run fast._  **We don't compromise on application performance.**

## Maintenance

### Upgrade App to Support Latest iOS & Android

Every time Apple and Google releases a new operating system, apps need to make changes to support the latest specifications.  If you don't, you risk Apple or Google pulling your app from the App Store or Google Play.  These upgrades can take a lot of time and are sometimes complicated.

### Security Patches

Apps are built by using a set of frameworks, tools, and reusable components.  On occasion a security update is released for one of these components, and the application developer needs to upgrade the app and apply the security fixes.  Without regularly patching your app and API, the security of your app and data are compromised, and that is unacceptable.

At Foxbox we regularly upgrade all of our clients' apps to apply the latest security upgrades and bug fixes.  This keeps our apps running fast, smooth, and secure.  As soon as we patch each app, we release it to the App Store and Google Play.

## Bug Fixes

It's normal for an app to have some bugs - even the most well-tested apps do.  When a bug is identified from our error alerting system, we respond quickly to fix it.

## Premium Support

At Foxbox, you have a direct line to reach out to our support team.  If you need to make changes to your app, or if you just need help with something, we're here for you, when you need us.  Our clients have **unlimited access to premium support.**

## Managed Services @ Foxbox

At [Foxbox](/), we handle the hosting, monitoring, maintenance, bug fixes for you.  You'll also have unlimited access to our premium support.  You'll have the **confidence** of knowing that your app is running smoothly, forever.  And if anything happens, you know that someone is actively monitoring it and working on a fix.

**We're your trusted partner, for the life of your app.**

**[Learn more...](/services/managed-support/)**

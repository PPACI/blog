---
date: 2021-03-11
title: When regulation drive ops innovation
---

## Craving for regulation

In the financial sector, we like regulation. Like we **crave for it**.
Architecture white paper, audit, transparency, and every little detail you can imagine.

In Luxembourg, our surveillance organism is called the [CSSF](https://www.cssf.lu/en/).
If you want to do anything related to finance, you have to pass by them.
It's also true for innovative fintech companies.
I would even say *especially if you are an innovative fintech company*. 

This is actually a very good thing from a tech startup point of view.
It helps you focus on your tech and force you to provide a polished and optimised service to be successful.
If you want to enter any other market, you can come with a new feature that your competitor lack of.
Basically you solve a new problem.
Or you could pick an already solved problem, and innovate on how you solve it.
You have an opportunity to be more cost-efficient, more agile and all the things that startup likes.
In the financial sector, you have to play along an additional set of rules.

The perfect example is bitcoin. Everyone is speaking about cryptos right now.
Yet company like Ripple have a hard time with SEC because they did deviate a bit from the rules...
We start to hear about cryptos ETF and more traditional financial products only now because of regulation.
In the end, you can create new features, but not a whole new range of disrupting products.

On the other hand... Disrupting a market by optimizing to hell what current actors are doing is what startups do every day.
You would be surprised by how many companies were successful by creating and optimizing a REST API for old services...


## Constraints will force you to be creative

As a cloud engineer in a start-up, my job is balanced between design, implementation and maintenance.
Our analysts are speaking to customers, understanding the real needs.
Our devs are implementing the solution.
None of that would be possible without a fast and reliable technical platform.

**The indie hacker movement is the perfect proof that you can start with a simple VPS, and a single Postgresql instance.**
_That's just not possible in our case._
To be even able to accept your first customer, you will have to demonstrate multi region resilience, backup strategy and a lot of other "production ready" grade features.

Usually you think of that when you're BIG.
We have to think of that from the ground start.
That's something very exciting to do.
A mono instance VPS? Simple, flexible, but not resilient enough.
Multi cloud Hybrid Kubernetes? Resilient, but way too expensive and complex for a company starting to have customers.
Also, as a new company, your OPS department won't be 50 peoples.

**So we have to be creative.**
Finding the right size.
Finding your way in the network spaghetti that the security requirements will bring you.
(have you ever saw a bank network architecture? Do you like italian pasta?)
Using the right tools.
Guess what? In 2021, CI/CD, Infrastructure as code, Managed Kubernetes, Helm, blah blah blah, they are a thing.

The key is to do everything as code.
You can prove what is implemented without taking days.
That is **very** useful for audit purpose.
You can then also run automated compliance test, just to be extra safe.
*You want to be extra safe here.*
**Data breach = death of your company.**
Also, by using code, you can CI/CD, so **more automation on top of your automation**.

Packaging system become mandatory. Tools like Helm, Terraform and Ansible become your best friends.
Can you imagine the stress relief of being sure that you won't forget to deploy monitoring, alerting or backup script?
_I surely can._

Once you have all the tools, it's up to you to be creative to create the best automated, scaling, yet resilient, secure and trustable platform.

**If I were without any regulation, I would have gone for the VPS.**
Instead, I'm now a better engineer. Thank you regulation.
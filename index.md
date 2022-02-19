---
layout: default
---

# Building Clouds.

That is what we do, getting you started on Cloud. 

Whether it is about a 'get your toes wet' project or building a full-fledged cloud-native business model, we are the _quartermasters_ getting you up and running.

> Whatever anyone else tells you, **doing cloud right is hard**. 

If you want to build a team that is _agile_ and create _secure_ and _compliant_ websites, applications, systems, platforms or companies, you have to do more than just create an account with Amazon Web Services (AWS), Microsoft Azure or Google Cloud Platform and put some smart girls and boys with Macbooks to work.

> Cloud doesn't change **what** you do, only **how** you do it.

Cloud uniquely allows your team to move faster than ever before. Trying out new things, creating and discarding resources that would take months to aquire and years to pay-off in the physical world.

_Keep your team small_, only hire fast-learners with an inquisitive mindset, and add one or two key women or men with the inside knowledge of your products and processes.

_Don't overengineer_, because everything you think you know (or read) will turn out to be wrong, misinterpreted, marketing speak or obsolete by the time you finally use it.

_Security and Compliance_ has to be the primary quality criteria. Launching an awesome website and getting hacked in the first week makes for bad headlines.

_Don't be afraid!_ Once you have a team up and running with all the tools they need, they will move or change faster then you previously thought possible!

> Cloud, when done right, is a no-brainer for all organizations: small or large teams, small or large budgets, long or short timelines!

Don't forget all current cloud technologies, tools, and companies are developing (and changing) at a breakneck speed, don't expect tomorrow to look the same as today. 

Don't expect to build something today that will look and work the same a half year from now.

Enjoy the cloud experience!


## Get in touch!

Whether it is for a cup of coffee and some free advice, or talking projects, you can find us on [Linkedin](https://linkedin.com/company/qrmr), [GitHub](https://github.com/qrmr), [GitLab](https://gitlab.com/qrmr) and in real-life in Amsterdam, the Netherlands.


***

## Handy resources and snippets

There are those things you know of but always have to google to really remember, this is a (growing) list of my favorites :)

Add a password to an existing SSH key:

```
ssh-keygen -p -f {file_name}
```

Generate a new SSL key (RSA 2048-bit SHA2):

```
openssl req -utf8 -nodes -sha256 -newkey rsa:2048 -keyout private.key -out signing_req.csr
```

Add a password to an existing SSL key (AES256 encryption):

```
openssl rsa -aes256 -in private.key -out private_encrypted.key
```

(Remember to (securely) delete the unencrypted private.key file!)

Remove password from existing SSL key:

```
openssl rsa -in private_encrypted.key -out private.key
```


***

&copy; Copyright 2016 - 2022, all rights reserved by QRMR B.V.

QRMR B.V. is registered in the Netherlands under Chamber of Commerce number: 73327166.

# A short introduction to 5apps

(Quick sketch, only bullet points for now)

## The Problems

### Software

* Computing becomes cheaper and more ubiquitous by the day, bringing an immense variety of platforms and devices.
* Most platforms today use proprietary development and distribution environments, forcing both users to stay on their platform, as well as developers to build apps for either only their platform or multiple platforms in parallel.

### Data

* Apart from software platforms being walled gardens, the situation with user data is even worse. With cloud computing and SaaS on the rise, even for simple personal computing, users are increasingly handing over control over most of their data, effectively outsourcing their whole communication and storage architecture.
* As a result of this, the once decentralized Web is being centralized again in an incredible pace, resulting in very few private enterprises controlling the veins of the developing information society.

## The Outlook

### Software

* Even with successful app-store models in place, most vendors are also preparing for the future by developing and adopting countless new and existing web standards to make cross-platform development and distribution feasible in the long run.
* Everybody is agreeing on the Open Web Platform (meaning HTMl5, JavaScript, and friends) to become at least an equal option for software development.
* Development on those standards is going fast, as is adoption. Not only on desktop and mobile, but even on gaming consoles and TVs, with many more devices being in the offing.

### Data

* The shift to web applications, in particular offline web apps that need to store data on the users computer anyway, brings with it an enormous chance to give back control over that data to the users by letting them sync it to whatever storage backend they wish.
* With Unhosted and their remoteStorage spec, there's a great solution for web app developers to make use of very soon. Giving the user the option to store their data on any compatible storage service will be no more work that developing the offline web app with the localStorage spec itself.
* With proper packaging mechanisms in place, the same applies for users' software, which can be either used from or only backed up on those storage backends, too.


## Vision

### For developers

* Write an app once (i.e. use only one codebase and technology set), distribute it to all possible platforms.
* Don't have any extra work with allowing the user to store the apps data as well as the app itself whereever they choose.

### For users

* Buy an app once, run it on all possible devices, no matter what operating system they run on, both now and in the future.
* Never lose that app again. Store it on any compatible backend, either for running it from there or just for backing it up forever.
* Choose any storage backend for any type of data. Be able to easily migrate to another one.

## Solution

* Developing a service platform that makes it both easy for developers to deploy, distribute and sell their web apps, as well as for users to purchase, access, use, and backup them.
* Providing users with easy discoverabiliy of apps that support open storage solutions and developers with the tools and knowledge to leverage those.

A quick overview of our planned offering can be seen on the working drafts for our teaser pages (that are really rough sketches, using just trackpad-painted concept graphics and quick lists of what we deem important):

### Deployment platform

![Teaser page for deployment platform](http://5apps.github.com/onepager/screenshot_1.png)

### App Store

![Teaser page for app store](http://5apps.github.com/onepager/screenshot_2.png)

## Current status

### Finished

* Prototype for the deployment platform, including Heroku-like git-push deployment with automatic packaging as Chrome App, Open Web App (Mozilla), and Opera Widget (installable on OSes), as well as uploading to a storage provider with optional usage of a CDN.
* Some basics for the whole platform, like e.g. OAuth-enabled user accounts, role-based authorization, etc.

### Unfinished

* Proper user interface for developers to manage their apps
* Update mechanisms
* User-facing app store
* Future-proof licensing for all of this

### In place

* Competent team of currently 2 experienced developers, being able to implement the whole solution
* Proper software development and operations environment, based only on open-source components, including comprehensive unit and integration testing, automated systems configuration, intelligent deployment, backup and failover strategies
* Agile development processes in general, resulting in short iterations, fast feature development, and good code quality

To sum up the status: the foundation is all set, and we're ready to code full steam ahead. With full-time capacity we could launch a beta version in 3-6 months from now, with access for developers to the deployment platform in 1-2 months from now.

# How to Navigate Bluemix - My Starter Guide
Note that this guide is based on my blog http://blog.4loeser.net/2016/02/how-to-navigate-bluemix-my-starter-guide.html

Coming from a product like DB2 with a focus on operational and feature stability, consistency and high availability, and now working with a product or, better, platform like [Bluemix](http://bluemix.net) feels like an entirely different world. At least at first sight. Truth is that I feel at home once I learned to navigate it. Here is the first installment of my "how to bluemix"...

## Bluemix by Region and Organization
Once you have logged into [IBM Bluemix](http://bluemix.net), in most of the cases the dashboard should be show. Its content and also the services offered to you in the Bluemix catalog depend on the selected region and the organization (see screenshot on the right). [Bluemix and its services are hosted in different data centers around the world (regions) and not all services are available in each data center](https://www.ng.bluemix.net/docs/overview/index.html). You can find out which regions are available and which services are supported in a region by checking out the [Bluemix status page](https://developer.ibm.com/bluemix/support/#status) (also see the section below).

Each user can belong to several organizations and each "org" has its own resources. Depending on the selected organization you are going to see different statistics in your dashboard.

To get started with these and other concepts I recommend reading the overview sections of the manual. Which brings up the next section...

## Documentation
The documentation for Bluemix and its services is all available under "/docs" in each of the regions, e.g., https://www.eu-gb.bluemix.net/docs/ for "Europe/Great Britain" or https://www.ng.bluemix.net/docs/ for "North America/US-South". I found it important to understand that the documentation is frequently updated and extended and that those pages have a link section pointing to tutorials, samples, and deeper product documentation like the Cloud Foundry, Docker, and Openstack reference or to Knowledge Centers for individual cloud services. More on this in updates to this blog at a later time.

## Services, Boilerplates, Runtimes, and more...
All the important stuff, namely the 100+ services, can be found in the "catalog". It is organized by starter kits (so-called boilerplates) and service categories. Database systems as a service, Spark and Hadoop for analytics, NoSQL database engines and more can be found under the "Data and Analytics" category.

Services to securely integrate your own data centers (on-premises resources or "systems of record") can be found under the integration category. At the bottom of the catalog is also a link to another catalog which offers experimental services. It is the Bluemix Labs Catalog which provides this glimpse at the future. Given all these services, now what? Either just click on one to provision that service or read a tutorial.

## How to...?
I didn't know that for a long time, but there is a "How to" section for all kinds of Bluemix topics and technologies:

  * A page with guides related to Bluemix and Data Management,
  * a collection on Bluemix and Internet of Things,
  * another one for Bluemix and Watson/Cognitive Computing,
  * tutorials on Bluemix and DevOps, continous delivery and integration,
  * or Bluemix and mobile applications including iOS and Mobile First,
  * and guides for Bluemix and web applications.

There are also GitHub repositories maintained by various teams that offer great tutorials and sample apps. I will link to them in an update to this first blog.

## Bluemix Status and Updates
The status of Bluemix and its core parts as well as of most of its services can be seen on its dedicated Bluemix status page. On that same page you find a link to the RSS/atom feed of Bluemix notifications. Make sure to subscribe for service news.

## Getting Help
There are a couple options to get help or to dig deeper into technical issues. Questions can be directly send to the Bluemix Support or asked at developerWorks Answers or Stack Overflow. The documentation pages for many of the services also link to detailed product manuals for the software products building the foundation for the SaaS offering.

* Bluemix Support: Free support is provided through the Bluemix Community on developerWorks. For standard support click on the circled head icon on the right upper hand on the Bluemix site (from within your Bluemix account) and then click on either "Get help" to open a support ticked or "Submit an Idea" for feature suggestions (as shown in the screenshot above).
* developerWorks Answers (dW Answers) is a question and answer site. Questions are tagged with topics and Bluemix and some of its services have a tag of their own.
* More popular in general, but not necessarily with Bluemix questions is Stack Overflow. Many of the services have their own tag and it is important before asking to remember that Stack Overflow is focussed on programming questions. So hold back with general questions and ask them at dW Answers.

The discussed options are also shown on the Bluemix Support webpage together with known issues and the current Bluemix status.

So much for the first installment. Comments are welcome and I plan to extend and update this guide. 

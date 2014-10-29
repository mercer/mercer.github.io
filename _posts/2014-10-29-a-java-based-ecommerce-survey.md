---
layout: post
title: A Java Based eCommerce Survey
---

It's 2014. The online shop software problem is solved, right? What if I want a java stack, is it solved? What about integration with [Authorized.net](https://www.authorize.net/)? It should be, of course, open source software.

While trying to answer thise questions, I took a look at the java based eCommerce software ecosystem. The old player [Apache OFBiz](https://ofbiz.apache.org/) and the new kid on the block [BroadLeaf](http://www.broadleafcommerce.com/) stood out.

The Apache Open for Business Project
-------------------------------------
OFBiz is an ecosystem on its own. It has been around since 2007 and today if offers anything you'd want from a [business management software](https://en.wikipedia.org/wiki/Apache_OFBiz). It has [authorized.net support](https://cwiki.apache.org/confluence/display/OFBENDUSER/Apache+OFBiz+Business+Setup+Guide). The [code](https://fisheye6.atlassian.com/browse/ofbiz) is available. The [issue tracker](https://issues.apache.org/jira/browse/OFBIZ/?selectedTab=com.atlassian.jira.jira-projects-plugin:summary-panel) says OFBiz is an active project. The [quick start](https://ofbiz.apache.org/download.html) should point you on the right path.

The strong point of OFBiz is how much you can customize it and that it already comes with any feature you can think of. The downsize is that, if you want to extend it, you need to learn it's data model. Not a really downsize really, you do want to learn a tool before using it, right? Don't expect a quick win with OFBiz, unless you're already familiar with it.

BroadLeaf: The Open Source eCommerce Framework
----------------------------------------------
[BroadLeaf](http://www.broadleafcommerce.com/) has modern (but mainstream) java technologies as it's [stack](http://www.broadleafcommerce.com/technology-stack) such as [Spring](http://spring.io/) and [Hibernate](http://hibernate.org/). BroadLeaf has [authorized.net support](http://www.broadleafcommerce.com/docs/authorizenet/current/authorize.net-environment-setup) and the code is availabe on [github](https://github.com/BroadleafCommerce/BroadleafCommerce), so are the [issues](https://github.com/BroadleafCommerce/BroadleafCommerce/issues). Follow the [getting started](http://www.broadleafcommerce.com/docs/core/current/getting-started) guide to learn more.

BroadLeaf's strong point is it's promised minimalism and ease of integration. This is also it's weakness (or not, depending on this is what you want). There are many things BroadLeaf will not do, you'll have to build those things yourself.

The rest
---------
The offer of modern, lively and attractive eCommerce software on the java stack seems to be slim. Is it crazy to expect such software to exist on this stack? Maybe. Other offers I haven't looked at closely are:

* [Shopizer](http://www.shopizer.com/#!/)
* [opentaps](http://www.opentaps.org), an OFBiz fork.

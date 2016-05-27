# Jelastic DjangoCMS Installation Package 

This repository provides [DjangoCMS](http://django-cms.org/) JPS-based installation package for Jelastic Platform.
[![GET IT HOSTED](https://raw.githubusercontent.com/JelasticJPS/DjangoCMS/master/images/getithosted.png)](http://go.jelastic.com/test?hoster-select=1&theme=modern&app=https://raw.githubusercontent.com/JelasticJPS/DjangoCMS/master/DjangoCMS-1.1.1.json)

**DjangoCMS** is an open source content management system.

**Engine**: python2.7

**Environment topology**:

1. 
   - node type: apache2-python
   - count: 1
   - cloudlets: 16
   - external IP: false


### What it can be used for? 
The open source content management system based on the Web framework Django that encourages rapid development and clean, pragmatic design.
  - **Ridiculously fast.**
    Django was designed to help developers take applications from concept to completion as quickly as possible.
  - **Reassuringly secure.**
    Django takes security seriously and helps developers avoid many common security mistakes.
  - **Exceedingly scalable.**
    Some of the busiest sites on the Web leverage Django’s ability to quickly and flexibly scale.

    

### What Jelastic JPS package is?

Jelastic JPS package represents an one-click installation solution, that allows to get the desired project hosted at Jelastic Cloud in a matter of minutes. Being based on [Jelastic Packaging Standard](https://docs.jelastic.com/jps), it automates creation of the necessary environment and subsequent application deployment to it. Herewith, all of the required properties and behaviors are predefined within the package JSON manifest, so you instantly get the ready-to-go solution.
The full list of the available at a platform one-click packages can be seen at the corresponding same-named section of [Jelastic Marketplace](https://docs.jelastic.com/marketplace#apps].

### How to deploy a package?
###### For Developers

In case you can’t find the desired solution within the list of available ones at your dashboard, just copy and save the content of its manifest as a *.json* file and [import](https://docs.jelastic.com/environment-export-import#import) it to the dashboard. Herewith, you can apply any necessary adjustments to template settings through this file (if such are required) and install its customized version in the similar way.

###### For Cluster Admins

In order to add the desired JPS package to your platform and make it available for users, perform the following:
- copy content of its manifest 
- switch to the [Marketplace](http://ops-docs.jelastic.com/marketplace-46) section of your JCA panel and choose **Add > New Installation** menu option
- paste the copied strings into the appeared frame and **Save** the template
- choose your newly added package within the list and click on **Publish** above

Also, you are able to adjust the given package template according to your needs and provide its customized version.
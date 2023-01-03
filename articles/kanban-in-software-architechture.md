# Kanban in Software Architechure

## You have to revise your system architechture

One of the firsts tesps in starting any development project is to design the architechture and select the required tools and technlogies.


Since this is one of the early stages in the development, this means you don't know what would be the number of users, what would be the bottlenecks in the system, or ....
Even if you have a consulting expert which helps you in desiging the architechture, there are many cases that bussiness requirements are going to change drastically, making the intial architechture lose the main assumptions.
I have been part of a development team, which initialy they were instructed to build a web backend for a prototype app. They were assured that they should not think about scaling, they should only think about building the prototype really fast. If they got to point of having a large user base, we are going to recreate the app from scratch. But as you can imagine this didn't go as it was planned. Soon the application gained some users and since they had some users, they wanted don't lose the intial growth so not only they asked us not to start from scratch, we got a list of new features which should be added to the app. and they asked us not to worry we are going to rewrite this in future. the future which never came. So finally we got to the point of having a super messy code with no strategy for scaling

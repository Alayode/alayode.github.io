---
layout: post
title: Life, the web, and everything in between
---



Happy New Year 2014!
明ましておめでとう 2014年！



It has been awhile since I wrote at all on this blog. It has not been the awhile since I wrote at all!
The last time I wrote at all was actually yesterday in my notebook. I like to write in a basic notebook sometimes
I find it easier to talk about my self in front of my own notebook then in front of the screen. I need to work on that though
What brings me today to sit in front of my computer is the fact I have another project that I am working on that I think deserves
to be documented in detail about. I am working on a standard website for a client and I am trying to find a way to get
the website to work in Angular only. The site has some php/mysql back-end for the user authentication that I have just decided
to not go forward with. AngularJS is an amazing Javascript Framework。 I want to use it as much as possible and be able to
work with it with EVERY web application. Looking at just changing the way I am submitting the web forms and making it more
"Angular" I don’t think this is the "Angular Way" but I think it is great to really start thinking this way!
Working with AngularJS to submit forms with AJAX was a great way for me to understand 2-Way Data-Binding. In the Angular
documentation “Data-binding in Angular web apps is the automatic synchronization of data between the model and view.”
No more messy $(‘input[name=name]’).val() is not required. (sorry jQuery…. it is me not you)

We bind data to a variable in Angular, and whenever it changes it either the JavaScript or in the view, it changes in both.
To demonstrate data-binding, we’ll get out form inputs to populate a variable formData automatically. Let’s look back at
our Angular controller that we applied to our page. We passsed in $scope and $http.

What is the $scope?

$Scope: The “glue between the application controller and the view. Basically variable are passed to and
        from our controller and view using the $scope. For a more detailed definition, check out the Angular Documentation.
$http: The Angular service that will help us do our POST request. For more information, check our the Angular Documentation.


I will expand on this as I continue on my project and share my opinions as well.
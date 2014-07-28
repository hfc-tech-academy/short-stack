# So you're joining us?
Great!  We're really exited to have you!  Since you've made it this far, we know you're just like us: lifetime learners who get totally pumped when faced with new things.  

Since we want you to do your best, it's important you go through the things on this list *before* showing up for the first day.  The course is short enough and the material deep enough that if you don't prepare, it's possible to be overwhelmed quickly.  

Here's a list of things to do.  Each assignment is pretty short, but they will help you understand the technologies we'll be using deeply enough to stay afloat.  

### Set up your computer
Ok, so you're bringing your own computer for this class.  It's important, since you're going to be doing so much work outside of class, to make sure you are set up correctly to work efficiently from day 1. (and before, in order to do the appropriate homework!)

**N.B.** Think deeply about implementing a *nice clean start*.  Clearing off your computer and reinstalling the newest operating system is not only cathartic, but a great way to make sure everything works well together.

1. RVM, Ruby, Rails:  
	1. In terminal run (*mind the backslash!*) `$ \curl -sSL https://get.rvm.io | bash -s stable --ruby`.  
		This will install [Ruby Version Manager](https://rvm.io) as well as the current stable version of [Ruby](https://www.ruby-lang.org/en/).  
		Test that things are working by typing `$ irb` and making sure you're inside a ruby command line.  
		It should look like `2.1.2 :001 >`.  Type `puts 3 + 5` and you should get `8 => nil` back.  Good?  Good.  
    2. Now run `$ gem install rails`  
		Test that this is working by typing `$ rails new app`  
		It's working if you get a million lines of `create ...` followed by another million lines of `Using ...`.  
		You can now delete the app by typing `$ rm -rf app`.
2. Javascript: Go to [nodejs](http://nodejs.org/) and install the latest package.  
3. Editor: We'll use [Textmate](http://macromates.com/download) during the course.  It's flexible, free, and terrific.
4. Chat: We'll use [Hipchat](http://hipchat.com) for class purposes.  It's a nice little chat package that you can run on any platform, and it's a great way to get my attention.


### Set up your life
Here's a list of places you'll need to have an account for during the course of the course:

- [github](https://github.com/)
- [tumblr](http://www.tumblr.com/)
- Hipchat, but you'll get an invite for that from us.

We also recommend, especially for the bonus prep-work, signing up for an account with [Code School](http://www.codeschool.com) is not only wise, but a fun way to learn.

### Git
Git is all about version control.  You'll be working on large projects, and some days you'll write hundreds of lines of code.  Sometimes that code will break and you'll need to go back to a working version.

The following three resources are a great introduction to Git:

- Code School's [trygit](https://try.github.io/levels/1/challenges/1)
- [Pro Git](http://git-scm.com/book)
- [Git in Action](http://vimeo.com/16395537)

# And now, the prep-work

For each subject, do no less than the base by showing up.  It should be about **30 hours** of total work, so make sure to pace yourself.  The weekend before class is a terrible time to start.

If you feel underwhelmed by some of the work, please feel free to tack on the bonus work.  It'll solidify your understanding of some of the core concepts before showing up.

## HTML
#### Base
HTML in a bubble (sans styling) is a funny beast.  It'll look terrible, but it's important to know all of the semantic elements.  Go through HTML Dog's beginner [html tutorial](http://www.htmldog.com/guides/html/beginner/) to get an idea of the elements you'll be using.
#### Bonus
Work through [Code School's Front End Formations](https://www.codeschool.com/courses/front-end-formations) for a good overview of HTML and CSS.

## CSS
#### Base
CSS is everything good about page design.  So much magic happens here, and with a fair amount of practice you can clone nearly any design out there.  HTML Dog also has a beginner [css tutorial](http://www.htmldog.com/guides/css/beginner/).  Run through it and enjoy your new life as an artist.
#### Bonus
As usual, [Code School's CSS Cross Country](https://www.codeschool.com/courses/css-cross-country) is a lovely way to learn.


## JavaScript & jQuery 
#### Base
CSS has a few limitations.  There are [pseudo-classes](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes) which allow you to get a lot of interactivity with plain HTML/CSS, but if you want your sites to truly be alive you're going to have to use something else.  jQuery will be your workhorse, but you'll still have to do a little 'straight programming' via JavaScript.  

For both, you should run through the [JavaScript](http://www.codecademy.com/tracks/javascript) and [jQuery](http://www.codecademy.com/tracks/jquery) tracks at Code Academy.  Also check out the [JavaScript Beginner Tutorial](http://www.htmldog.com/guides/javascript/beginner/) on HTML dog.
#### Bonus
Read through and play with [A Reintroduction to JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript) and [Code School's Try Query](https://www.codeschool.com/courses/try-jquery).

## Ruby
#### Base
Since the goal of the course is to create websites using Rails, you're going to have to understand the syntax used by Ruby.  Ruby is a terrific first language, it's very expressive and readable.  Before we start the course, you should work through the [Ruby Primer](https://rubymonk.com/learning/books/1-ruby-primer) on [rubymonk](https://rubymonk.com/).
#### Bonus
Work through the [Ruby Koans](http://rubykoans.com/).  They're neat.

## Rails
#### Base
Many people will suggest many things to get familiar with Rails.  There's no quick and easy answer, since there's so many moving parts.  We're eventually going to do the amazing [Hartl Tutorial](http://www.railstutorial.org/), but I feel the correct 'first tutorial' is found at [Rails Girls](http://guides.railsgirls.com/).  Do 1-11 under "Welcome to Rails Girls" before you show up.
#### Bonus
Work through [Jumpstartlabs Blogger](http://tutorials.jumpstartlab.com/projects/blogger.html), up through and including I3.
[View in Browser](https://vast-harbor-87818.herokuapp.com/)
Things to do:
-Better navigation
-I5 Extras, I6 Extras

### Introduction

In this project, you'll get the opportunity to actually build a real rails application.  It's not a trivially simple one either -- it's got a lot of wrinkles and things that you're not going to understand.

To be honest, you're kind of going into the deep end so don't worry if you don't understand what exactly you're doing in all the steps.  The point here is to get familiar with the process of creating a Rails app, what things generally look like, and what you don't know.  When you get to the end of this project, you can consider yourself remarkably persistent and resilient.

Because you'll be doing so much stuff that we haven't taught you yet, this is a good project to find a partner to work with on even though it's just following a tutorial.

### Assignment

<div class="lesson-content__panel" markdown="1">

  1. Follow the instructions atop the [Google Homepage project](/courses/web-development-101/lessons/html-css) to set up a Github repository for this project (of course you'll need to change the title).
  2. Do the [Jumpstart Lab's Blogger Tutorial](http://tutorials.jumpstartlab.com/projects/blogger.html) sections I0 through I4.  Pay attention to any error messages you get, both planned (because the tutorial walks you through a common error-guided workflow) and unplanned (likely for things like spelling errors).  You'll see all these messages again and again when you're building Rails apps, so it's helpful to start getting familiar with which portions of the message you should pay attention to (and maybe put into Google if you can't figure out what caused it).
  3. After you finish going through the tutorial, you'll notice that if you delete a tag, all related orphaned taggings will remain there. You can solve this by enforcing [Referential Integrity](https://en.wikipedia.org/wiki/Referential_integrity) by applying the `dependent: :destroy` option for the `has_many` method in the right model. You can learn about it in [This Entry of the Rails Guides](http://guides.rubyonrails.org/association_basics.html)
  4. Here's a [helpful gist with common Blogger problems](https://gist.github.com/burtlo/4970471) if you're running into issues with routes, deleting, partials, and `redirect_to`.
  5. If you're feeling ambitious, add in authentication in section I5.
  6. If you're feeling very ambitious, try doing the final Extras section I6.
  7. Don't forget to deploy your app to Heroku!  [Review Heroku deployment here.](https://www.theodinproject.com/courses/web-development-101/lessons/your-first-rails-application?ref=lnav)
</div>

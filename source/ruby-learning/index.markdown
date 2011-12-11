---
layout: page
title: "Ruby Learning"
date: 2011-12-10 12:27
comments: false
sharing: true
footer: true
---

Welcome to my attempt at coming up with a reproducible
outline that will allow any non-programmer to
become a [software developer](http://en.wikipedia.org/wiki/Software_developer)
 in the [Ruby programming language](http://en.wikipedia.org/wiki/Ruby_programming_language)
and get a job writing [web applications](http://en.wikipedia.org/wiki/Web_application) using
the [Ruby on Rails framework](http://en.wikipedia.org/wiki/Ruby_on_Rails).

As we all know, computers have become a large part of
our lives.  Behind all of those computers, lie an army
of people that tell those computers what to do.  Many
people think that what we do as software developers
is magic.  My goal is to show people that it is not
magic and it indeed a skill that can be learned by
anyone who wants to put in the effort to do so.

I am as new to teaching non-programmers how to
become effective software developers as you
are at programming in Ruby. I am looking to get enough
people to participate in this little “experiment” so that
I can refine this outline to make it more effective.  In
order to do that, I am asking that you will share your
feedback with me as you progress.  I have been developing
software for almost 15 years now so I have a different
view on the steps needed to learn to program than say
an unemployed carpenter or a stay at home mom who has never programmed at all.

You may be asking why you would want to learn to become
a software developer in Ruby.  There are many
reasons: it is a fun job, it pays well, you are
constantly learning, etc.  Here is a link that shows what the
average Ruby on Rails developer is paid:
[http://www.simplyhired.com/a/salary/search/q-ruby+on+rails+developer](http://www.simplyhired.com/a/salary/search/q-ruby+on+rails+developer)

If you want to see how many jobs there are out there for
Ruby on Rails developers, just type “ruby on rails job openings” into
Google and you will see.

If you are interested in chatting more about this program, please
reach out to me via [Twitter](http://www.twitter.com).
My user name there is [mikegehard](http://twitter.com/#!/mikegehard).  Please
include the [hashtag](http://support.twitter.com/articles/49309-what-are-hashtags-symbols)
“#rubymentorship” in your
tweet so I can track what people are saying about this program.

Thanks in advance and I look forward to your feedback and questions.

Please check back often as I hope that the outline will continue to evolve
with help from all of you.  To submit changes, please use GitHub to
submit a [pull request](http://help.github.com/fork-a-repo/)
to [the repository](https://github.com/msgehard/mikegehard_blog) or
contact me on Twitter.

Don't worry

## You assignments...if you choose to accept them

### One person's view on what it takes to become a software developer
1. Read this blog post: [http://mattdeboard.net/2011/11/23/how-i-became-a-programmer/](http://mattdeboard.net/2011/11/23/how-i-became-a-programmer/)

### Learn Git and [GitHub](http://www.github.com)
#### Install Git on your system
1.  Watch [Git Video Part 0](http://www.youtube.com/watch?v=vaNGbk6HN9Y&feature=related).
If you are running windows, checkout out this link: [http://nathanj.github.com/gitguide/tour.html](http://nathanj.github.com/gitguide/tour.html)

#### Read up on how Git works
1. Read [Chapter 1 of ProGit book](http://progit.org/book/ch1-0.html)

2. Sign-up for a [GitHub](http://www.github.com) account

3. Create a Hello World repo on Github. When you get this all complete, send me a tweet with a link to your GitHub
 repository. These links will help get you started:
    * [How do I connect my local repositories to GitHub](http://help.github.com/mac-set-up-git/)
    * [How do I create a repository, make local changes and then push those changes to GitHub](http://help.github.com/create-a-repo/)

#### Install Ruby on your computer

##### Mac (NOTE: Ruby is pre-installed but is a very old version. We will not use this version.)
1. Install the GCC compiler from [https://github.com/kennethreitz/osx-gcc-installer](https://github.com/kennethreitz/osx-gcc-installer)
2. [Install RVM](http://beginrescueend.com/rvm/install/). You want the single user install.
    * Don’t worry about reading the script because it will probably be as understandable as Latin at this point.  If you want to read it, please feel free.
3. [Install latest version of ruby](http://beginrescueend.com/rubies/installing/) (currently 1.9.3-p0) using RVM.

##### Windows
1. Install [Pik](https://github.com/vertiginous/pik/)
2. Install ruby 1.9.3-p0

NOTE: If you have any questions, please let me know. I don’t use a PC everyday but I can help point you
in the correct direction.

##### Linux
1. Try to follow the Mac instructions and let me know if you have any questions.

#### Get basic background in Ruby
1.  Fork [this repository](https://github.com/msgehard/LearnRubyTheHardWay) and
clone your fork into a directory on computer.
    * For help check out [http://help.github.com/fork-a-repo/](http://help.github.com/fork-a-repo/)
2. Finish each exercise at [Learn Ruby the Hard Way](http://ruby.learncodethehardway.org/)
    * All files that you write for Learn Ruby the Hard Way should be saved into the directory that was created when
     you cloned your fork of the repository.
    * Each exercise should be in its own file.
3. When you complete an exercise, push the changed exercise file to your fork of the LeanRubyTheHardWay repository.
    * Make some notes in the commit message about your thoughts of the exercise, what was hard, what was easy, include some links to any extra information you found on the internet.

If you have questions about an exercise, follow these steps for submitting your questions via GitHub:

1. [Create a new branch in your local Git repository](http://progit.org/book/ch3-0.html )
2. [Commit the changes to that branch](http://progit.org/book/ch2-2.html) with some comments about what is confusing you
3. [Push those changes to a remote branch on Github](http://progit.org/book/ch2-5.html)
4. [Submit a pull request](http://help.github.com/send-pull-requests/) so I know that you have questions

We will then use comments in that pull request to as the first mechanism to talk about the issue.  If we need to chat either on Skype or face to face we can do that as well.

#### Begin to understand test driven development in Ruby

Testing in important in the Ruby community for many reasons. I could talk your ear off about this so please email me to set up a time to chat about it if you’d like to hear more.

1. Read about [test driven development](http://en.wikipedia.org/wiki/Test-driven_development)
2. Fork [this repository](https://github.com/msgehard/ruby_koans)
3. Clone your fork to your computer
4. Read the README.rdoc to get started
5. Create a branch in your repository called “my_solutions” and switch to that branch.
6. Every time you finish a koan file, create a Git commit in the ‘my_solutions’ branch
and push that commit to your remote ‘my_solutions’ branch on GitHub.
    * The commit message should contain any thoughts you had about that file.
    *  These will be notes to yourself about that file.
    * You can go back later and read these notes you made to yourself.
    * If you get stuck or want to discuss a koan, push the code to a
    branch on GitHub other than master or my_solutions and send me a pull request via Github.

## If you get this far, please contact me on Twitter (using the appropriate hashtag) and I'll add more work to your plate.
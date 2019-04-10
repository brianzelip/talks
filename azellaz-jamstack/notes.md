snip cart
  - how it works
    - admin interface
      - taxes apis
      - shipping apis
      - inventory
    - javascript
      - code
        - file imports (sc and jquery)
        - init and customization
        - item definition in buy button
      - web demo
        - add button functionality
        - product options in cart
        - snip cart docs

netlify
  - https
  - lets encrypt
  - range of static site generators
  - jamstack radio is a function of netlify
    - netlify leadership on
      - jamstack radio (the two good episodes)
        - http://www.heavybit.com/library/podcasts/jamstack-radio/ep-1-introducing-jamstack-radio/
        - http://www.heavybit.com/library/podcasts/jamstack-radio/ep-2-the-jamstack-origin-story/
      - changelog, https://changelog.com/podcast/251
    - snip cart folks on jamstack radio, http://www.heavybit.com/library/podcasts/jamstack-radio/ep-14-pitching-jamstack-to-customers/
  - merge tests via github demo






MISC notes
  - support ie 10 and 11 -- lotsa fun!
  - it was interesting working with a vertical-oriented logo (instead of horizontal-oriented)
  - image optimization workflow
  - git workflow - i'm lucky to develop for a content-creator who doesn't mind using git and updating data in json. However, we also employ a hybrid csv to excel to csv to json and vice versa
  - atomic css is like a built-in style guide, because it enforces consistency, eg for consistent whitespace

  - limitations?

  - what i'd like to do next





site edits before talk:
  - shop grid img re-sizing x3
  - paragraph breaks in descriptionLong




the JR Web Dev show
show notes as the bibliography for references of the talk

I think this venue is perfect for me because I think "jr web dev" is an apt characterization of my skills. I have a lot of css and html skills, but my javascript skills aren't very deep. I still have a lot to learn about asynchronous programming and closures for example. As well as getting more comfortable with node.

I'm not just here to teach, i'm also participating here as a way of asking questions and looking for feedback, because I don't get feedback at all really, and I'm interested in anything anyone has to say.

The Changelog podcast on jamstack is a good way to talk about jamstack
  - it's not really a new technology, but rather is a way of talking about, and of a way of observing some of the smart things that are going on, some of the new capabilities that are becoming more and more available and easier, NETLIFY is a company, but they're doing this outreach work in a very open source way, in a way that spreads the power around instead of just getting power for themselves.

  The name isn't really even a thing to debate or complain about or laugh at or talk about, but rather to understand that it's a learning entry point; it's yet another way for people to learn how to leverage available tools, how to recognize the tools that satisfy the different needs that, when you chain them all together, provides a platform for leveraging the tools of today.

  there needs to be a "shownotes" slide that lists references from this talk

  when you start diving into these resources, you come out the other side with a better understanding of the breadth of what's going on in the front end world; and in a way that makes you feel that what is going on is approachable by you, even if you're a noob.
    - you're learning to grasp the breadth of what's going on, in a way that makes you feel like this breadth is approachable and doable, and fun, and cheap. and that's what my story is about.

    what i'm excited about doing next:
      - leveraging functions as a services, AWS Lambda
        - i'm trying to escape paying for anything, or as little as possible
          - where i cannot escape paying:
            - financial transactions - so i have minimized these costs
            - server functionality - so i have minimized these cotsts
              - email signup forms
              - contact via web form email
      - re-writing out of jekyll, into just javascript, maybe react or vue.









show them my npm scripts workflow
Historically, npm scripts became a popular approach after gulp which came after grunt.

you could just do it all w/ npm scripts, using the CLI tools of a project's dependencies; became more lean than gulp and than grunt.

I've got some skills, but there's a limit to my skills.
My personal growth rate slowed down just after the npm script way became popular, because then it was about react and webpack, which really shook things up, and there's still a bit of change happening within this paradigm, although it has been stabilizing more and more lately.

the react and webpack paradigm incorporates much more javascript than I was used to, and so my growth slowed. And instead of trying a little of lots of new things, like was the path i was taking before react, now I'm going much deeper into a smaller amount of things, namely, I'm going deeper into learning javascript so that I can better understand and write javascript web apps.

i'm not doing as many tryouts of cutting edge tools, but rather diving deeper into javascript, via podcasts, edabit, free code camp, !mdn, Wes Bos, funfunfunction on !yt

So this project, Azellaz, takes a pragmatic approach in order to actually ship a thing. It utilizes the tools that I work most efficiently with, which is this hybrid of jekyll and npm. but ideally, everything would be all javascript.



i listen to a lot of podcasts as a way of learning, of keeping in touch, and of hearing from experts in the community (from both podcast hosts and their guests).


i want to show people who aren't familiar, what it actually looks like to get a jekyll site up and running, and to work npm scripts into the process
  - literally, show them my workflow of CLI commands to get the dev environments up and running





walk through snip cart interface, its api interface, testing vs production, docs, etc. See above for more detailed notes on this.
show stripe
show craftybase (very briefly)
show the zoho email for 1 free custom domain email -- support@azellaz.com

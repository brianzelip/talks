I've spent quite some time getting to fit in the Netlify groove, with regard to serving multiple repos under one common custom domain enabled home page site.

Now that I've got it under control and maintainable, I'm able to rethink the basic assumptions that I just fought so hard for to achieve. Namely:

- instead of talks being the root repo for various talks, each talk should be its own repo. In other words, updating git should only occur when work happened relating to that project, ie: when I update azellaz-jamstack and update the git history, the node-mvc repo should not be impacted at all. Instead, the way it currently is, the way I fought so hard to achieve, _committing work for one project impacts the git history of other projects_. This is not ideal.

- the index page can be its own repo, called talks. This repo gets updated every time there's a new talk url. This implies a proxying condition, which means adding a \_redirects file to the talks repo. This talks repo should have these basic files:

  - index.html
  - \_redirects

- when there are cases like one-offs, as is the case w/ ictr.pdf, loyola...pdf, etc., then these raw files should be added to the talks repo

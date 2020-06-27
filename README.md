# I have a problem with sbt

Bring your own problems at the [sbt in-depth](https://www.47deg.com/academy/2020-07-02-sbt-in-depth-webinar/) webinar of 47 Degrees Academy.

Depending on the level of attendance and the number of submitted problems, we'll use the last hour of the webinar to collectively solve as many as possible of specific problems submitted here.

## How to bring your own problem?

1. [Register to the webinar](https://us02web.zoom.us/webinar/register/6715882000741/WN_AqR_wPB5T361xL03ht2Jdw)
2. Issue a pull request on this repository adding your problematic project under a folder with your name. Try to describe your problem as precisely as possible in the PR's description.

In other words, if I were to submit a problem of my own, my PR would add the following file structure:

```
valentin-kasas/
  - build.sbt
  - project/
  - src/
    - main/
      - scala/

etc...
```

You don't need to minimize your problematic project as it is generally pretty tedious to do (and also because bigger projects and problems are generally more interesting).

## How will it work?

During the "problem solving" session, I will go through the submitted PRs in order. I will ask the person who submitted the PR if they still need help on their problem (hopefully, some may have learned enough during the webinar as to solve their problem on their own). If so, I will merge the PR, pull the code on my machine, and attempt to solve the problem.

As everything will happen on my machine, which will also be running all the streaming stuff in parallel, please avoid submitting problems such as "my computer crashes everytime I load this project", otherwise everybody will have an unpleasant time. 

Also, it should go without saying, but **it is your responsiblity to make sure that nothing confidential is added to this public repository**.

Finally, a disclaimer: I may not be able to solve your problem in a timely manner, mostly because I'm not an almighty sbt wizard but also because I'd prefer to go through as many problems as possible. But in any case, I'll do my best as to give you as many hints as possible toward solving it. After all, the journey matters more than the destination.

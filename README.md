# FRCC-Walkthrough

Hi Friends!

Here are some references for those new to Unity and git.

## Git

Everyone please read and follow these procedures when working on this project.  If not, I can't gaurantee that I will be able to merge any changes you make and might make you fix them.  Yes, I'm that kind of guy.

But, in all seriousness, wou will need to know this anyway.

Our project will follow very basic git-flow.  It's pretty simple.  Fork.  Clone.  Branch.  Edit.  Commit.  Push.  Ok, that is lot more words than I realized.  But really, it's not too bad.  And with 7 people it is the only way we can manage this project and keep our sanity.

### Back to Basics

What is git?

Here ya go: https://www.youtube.com/playlist?list=PLg7s6cbtAD15G8lNyoaYDuKZSKyJrgwB-

### But I hate the command line

And I'd rather click buttons like a windoze loser.

Here ya go: https://www.sourcetreeapp.com/

This is how I learned git.  The gui representation of what is going on didn't actually help me.  But it was easier to look for a button than try to remember that damned command lime parameter.  I swear linux users are masochists.

### Jeez, now what? (Git Flow!!!!11!!!11oneoneone)

Ok, I lied.  First, some documentation (for your reference.  Don't go read it now.  Yeah, seriously.):

* [github docs](https://help.github.com/)
* [Sourcetree docs](https://confluence.atlassian.com/get-started-with-sourcetree?_ga=2.145054900.1438776660.1531958221-1248499365.1531958221)

### Git Flow!!!

I am absolutely not going to write out every step.  That would be ludicrous.  Especially considering the fact that other people have already done that for me.  Here is what they had to say:

**Setup**

1. Fork this repository by clicking the "Fork" button in the top right of the homepage of this repository.
2. Clone your new fork.  [Sourcetree](https://confluence.atlassian.com/get-started-with-sourcetree/clone-a-remote-repository-847359098.html) [Git, step 2](https://help.github.com/articles/fork-a-repo/)
3. Add the original remote repository to your local clone. (often referred to as the origin, this repository, the one you just cloned is the origin).  [Sourcetree, close enough...](https://confluence.atlassian.com/sourcetreekb/changing-remote-repository-path-on-sourcetree-using-git-or-mercurial-785616227.html)  [Git, step 3](https://help.github.com/articles/fork-a-repo/)

**Workflow**

This is where the flow comes in.  It will keep us organized and will help limit how much we step on each others toes.  I know it looks like a lot of steps, but it really isn't that bad.

1. Pull and Merge from the origin. [Sourcetree](https://confluence.atlassian.com/get-started-with-sourcetree/pull-changes-from-a-remote-repository-git-847359111.html)  [Git, 'pull'](https://help.github.com/articles/fetching-a-remote/)
3. Edit.  [Do stuff in Unity](https://www.youtube.com/watch?v=dQw4w9WgXcQ)
4. Commit to your local repo. [Sourcetree](https://confluence.atlassian.com/get-started-with-sourcetree/commit-and-push-a-change-git-847359114.html)  [Git](https://githowto.com/staging_and_committing)
5. Push to your fork. [Sourcetree](https://confluence.atlassian.com/get-started-with-sourcetree/commit-and-push-a-change-git-847359114.html) [git](https://githowto.com/pushing_a_change)
6. Pull Request submitted to the origin. [github](https://help.github.com/articles/creating-a-pull-request/)
7. Rinse and repeat.

I just came across this.  It might be useful for commandline junkies: [Git How To](https://githowto.com/)

## Unity

### Building buildings

[ProBuilder](http://www.procore3d.com/probuilder/) (recently acquired by Unity) is what you should be using to build the buildings and models.  Here are some helpful ProBuilder links;

* [Documentation](https://unity-technologies.github.io/procore-legacy-docs/probuilder/probuilder2-gh-pages/)
* [Building Structures with Interior and Exterior](https://www.youtube.com/watch?time_continue=2&v=CBa_opm3_GM)
* [Simple Texturing](https://www.youtube.com/watch?v=bigj13SU1rs)
* [Advanced Texturing](https://www.youtube.com/watch?v=d3_2h4cN4cY) In case the simple texturing wasn't good enough.


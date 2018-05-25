# Introduction to Version Control

> “The past is never where you think you left it.” — [Katherine Anne Porter](http://en.wikipedia.org/wiki/Katherine_Anne_Porter)

## Problem Statement

Most people have reached a point in life where they had a choice: to do
something risky or to do something safe and have said "YOLO, do the risky
thing!"

![You tried to ford the river, didn't you?](https://curriculum-content.s3.amazonaws.com/web-development/git-version-control-101/choices.gif "You tried to ford the river, didn't you?")

...and regretted it.

![Bad Crossing](https://curriculum-content.s3.amazonaws.com/web-development/git-version-control-101/11-21-10-bad-river-cross.gif "Regret")

Life, sadly, has no undo button.

Wouldn't it be great if you could try things out in "sandbox" and then throw it
away, with no consequence, if it didn't work out? Wouldn't it be great to have
a built-in journal, that you wrote, of your motivations and thought process
around each experience that you could use to help you become smarter?  Wouldn't
it be great to be able to share your experience with others but not require
them into integrate it into their own personal history?

You can't do this with reality, but you can with code!

OK, so maybe you're perfect and have never made a regrettable choice (good for
you!). Have you ever collaborated on a document with a number of friends or
colleagues and rapidly found yourself drowning in a sea of `report-john.docx`,
`report-mary-undo-john.docx`, `report-mary-and-john-FINAL2.docx`? There is a
better way!

This improved type of existence can be achieved, for plaintext files anyway,
by using what programmers call "version control."

## Objectives

1. State what `git` is
2. State what a _commit_ is
3. Recognize how developers use _commits_ to discuss changes
4. Recognize that local commit history can be stored remotely

## State what `git` is

Version Control is the process of storing multiple versions of a single
project, allowing each version to be recalled at a later date. There are many
version control programs: `git`, `hg`, `svn`, `cvs` et al. The most-popular
version control system is `git`.

The Linux operating system was the first project to embrace `git`. Upon seeing
that team's success using `git` for version control, much of the industry chose
to follow.

## State what a _commit_ is

As you work on a document you reach a natural "pause." At this point, much like
when playing a video game and preparing to strike off into the unknown, and potentiall face a big, bad, boss battle you'd like to save a snapshot of your 
work. `git` calls this "snapshot" a **commit**.

![Continue and save, or continue without save? That is the question.](https://curriculum-content.s3.amazonaws.com/web-development/git-version-control-101/savepoint.jpg "Continue and save, or continue without save? That is the question.")

Ultimately, by creating a "journal" or "log" of commits, `git` can present a
history of your changes to your work.

## Recognize How Developers Use _commits_ To Discuss Changes

Additionally, for each commit, `git` assigns a special guaranteed-unique
identifier called a "SHA" (pronounced: "shah"). With each commit, `git` will
ask you to write a short journal entry called a "commit message" that
describes the change you made. The sum total of all `git` commits is the _git
history_ of the project.

As a result of having a series of "commits" developers can talk about choices
that were made and can collaborate.

## Recognize That Local Commit History Can Be Stored Remotely

To make it easy to back up (and, as you'll discover later, share) git
histories, git allows authors to copy (or, in `git`'s vocabulary _push_) git
histories to remote computers for access at another time or from another machine.

## Conclusion

The `git` version control program provides a means for authors to create
multiple "snapshots" of their work and review, annotate, and discuss it.
Effectively, `git` creates a journal of changes to their files. Each "journal
entry" is called a _commit_ and has a unique identifier assigned to it called a
"SHA" (pronounced: "Shah"). With this basic conceptual model in place, we will
proceed to teach you to use `git`.

## Resources

* [Getting Started - About Version Control](http://git-scm.com/book/en/Getting-Started-About-Version-Control)
* [Git Basics - What is Git?](http://git-scm.com/video/what-is-git)

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/git-version-control-101' title='Intro to Version Control'>Intro to Version Control</a> on Learn.co and start learning to code for free.</p>

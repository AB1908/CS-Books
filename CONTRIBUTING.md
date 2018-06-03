# Contributing to CS Resources

First off, thanks for contributing to this book list (it's not as lame as it sounds)! Although suggestions are welcome from everyone and in every form, it needs to follow a little structure unless the end-goal is to descend into a chaotic list of books. Apart from book suggestions, there's a host of other things to keep in mind when contributing to this repository (I know, I know, it's just a list).

## Table of Contents

- [Code of Conduct](#code-of-conduct.md)
- [Why Contribute?](#why-contribute)
- [Ways to Contribute](#ways-to-contribute)
  - [I want to suggest something like grammar or spelling!](#i-want-to-suggest-spelling-formatting-grammar-errors-or-basically-anything-that-isnt-related-to-books-or-material)
  - [I want to suggest a book!](#i-want-to-suggest-a-book)
  - [I want to add an entire topic!](#i-want-to-add-an-entire-topic)
  - [I want to suggest better ways to organise this list!](#i-want-to-suggest-better-ways-to-organise-this-list)
  - [I want to do something else!](#i-want-to-do-something-not-listed-above)
- [Issue Guidelines](#issue-guidelines)
- [Pull Request Guidelines](#pull-request-guidelines)
- [Style Guide](#style-guide)

## Code of Conduct

This repository follows the Contributor Covenant Code of Conduct. By any form of participation, the contributor is expected to uphold the aforementioned code. Any unacceptable behaviour may be reported to `abhishekbhattacherjee@live.com`.

## Why Contribute?

In the [readme](readme.md/#cs-curriculum-textbooks-and-references), I had described that I was unable to find a suitable list of books to learn subject matter from. It is therefore the goal of this repository, not only for me but for anyone interested in any topic of Computer Science, to have a comprehensive list of textbooks to refer to. Such a list would be a great way to point to the sources that people already in the field use(d).

Apart from that, I also found a frustrating problem that has happened more than a few times now. My curriculum constantly recommended some book (obviously in the best interests of the curriculum) only for me to find out halfway through reading it that there's another _way_ better book that blows the current one out of the water, whereupon I no longer have enough time to complete the book that I want to. I hope that stops happening to me and everyone else out there. Hopefully, this is sufficient motivation for YOU to contribute to this repository! Go ahead to the next section!

## Ways to Contribute

It is pretty obvious that the list will not suit everyone's taste, so contribution is strongly encouraged. A diverse opinion would only be better for future readers.

### I want to suggest spelling, formatting, grammar errors, or basically anything that isn't related to books or material!

Come on over to the [relevant Pull Request Guidelines](#submitting-a-grammar-spelling-or-other-correction)! You sure as hell can expect your name in the **Contributors** list.  

### I want to suggest a book!

Thank God you're here! Don't hesitate at all! Although it'd be great if you've read the book yourself and have thoughts to share, it's not necessary. Now there's two ways this could go :

- **The book you're suggesting isn't listed**
  - Money! If it falls under an existing topic, go ahead and add it. But before that, remember that I like order. It makes our lives much easier. So, take a moment and go through the [book suggestion Pull Request Guidelines](#submitting-a-book-suggestion).
  - If it's from a topic not listed, you may have hit the jackpot here! If you're lazy like me and only want to suggest a book, submit a Pull Request following the [relevant guidelines](#submitting-a-book-suggestion-for-a-non-existent-topic). But if you've got more than just a book to offer, [see below](#i-want-to-add-an-entire-topic).


- **The book you're suggesting is listed**
  - Don't worry! Go ahead and tell me why you wanted to suggest the book in mind! You can also suggest relevant resources, courses linked on the web, perhaps your personal notes you made while studying, the possibilities are endless. Go through the [relevant guidelines](#submitting-book-related-info) and submit a Pull Request! Personal experiences have not been categorised as of now. A [relevant issue discussing the matter](https://github.com/AB1908/CS-Books/issues/19) has been opened. Join the discussion if you have ideas!

### I want to add an entire topic!

You. I love you. You can go ahead and add the whole damn thing in a fork, keeping the [Pull Request Template](PULL_REQUEST_TEMPLATE.md) in mind. Have a cookie. But make sure you're careful enough to follow the template properly. With great power comes great responsibility! Also go through [the Pull Request Guidelines](#submitting-an-entire-topic).

### I want to suggest better ways to organise this list!

Come to papa! You might have noticed that this project doesn't have a fancy discussion channel, so come submit your ideas over at Issue #18. Hopefully, it'll be a big help!

### I want to do something not listed above!

Well, er, submit an issue and (hopefully) follow up with a pull request? The kinds of issues I expect to see here are contributions towards the "Community Docs", but I expect surprises.

### Note

It is strongly recommended that the book(s) suggested be suitable to approach the majority of the topic they fall under. Such a responsibility is left to discretion of the contributor.

## Issue guidelines

- Include a relevant title describing the issue in short.
- Write a detailed description of the issue.
- Suggest your ideas to remedy the issue and submit them in a Pull Request if possible. Make sure to abide by [Pull Request Guidlines](CONTRIBUTING.md/#pull-request-guidelines).

## Pull Request Guidelines

A Pull Request can only be created once you have forked the repository and made changes to the fork. So if you haven't already, go ahead and fork it! Then, create a new branch labeled `relevant-topic-name` where you'll make all your commits and make changes according to the guidelines described below. All your commits should (ideally) follow the [Style Guide](#style-guide). You can directly view the template for formatting [here](PULL_REQUEST_TEMPLATE.md).

In case you wish to modify this template, first join the discussion on Issue #18 and propose the changes. This is because the changes (if accepted) need to be made to the entire list.

### Submitting a grammar, spelling or other correction

Make all the necessary changes in a fork and it'll be merged by the maintainer(s) ASAP! Please try to explain the mistake (unless it's a trivial spelling mistake) when submitting and be patient with the maintainer(s).

### Submitting a book suggestion for an existing topic

If the book isn't already in the list, submit a Pull Request with the book(s) added under the appropriate topic in either the "**Standard Textbooks**" or "**Alternative/Supplementary**" section. I shouldn't have missed standard textbooks, but if it does happen (it probably will), I strongly recommended **adding a reference to the source** declaring it as a standard textbook in the "**Notes**" section for the topic. See the [Pull Request Template](PULL_REQUEST_TEMPLATE.md) for the formatting guide to follow.

### Submitting a book suggestion for a non-existent topic

You'll need to make the topic anew while closely adhering to the formatting in the [Pull Request Template](PULL_REQUEST_TEMPLATE.md). It's not necessary that you submit the topic in complete, but make sure to make the proper formatting before any book suggestion, no matter how small.

### Submitting book-related info

Personal experience with a book is extremely valuable here. Submit a pull request having made the following changes in a fork:

- All personal experiences and other info should go in a separate file labeled [`personal-experiences.md`](personal-experiences.md). Simply look for the appropriate topic header, add the relevant `[#]`(be a little careful with this one) and write away! Don't forget to tag yourself at the end with your GitHub handle!

If you have other info like some helpful resources for the book, a guide on what to read, a relevant instructor's course, personal notes, errata or anything else at all that would be helpful to future readers, please add them in the "**Notes**" section under the relevant topic, with an appropriate `[#]`. Make sure you add your link in the correct category (with the page title/appropriate description) under "**References**" too! See the [Pull Request Template](PULL_REQUEST_TEMPLATE.md) for the formatting guide to follow.

### Submitting an entire topic

This isn't as hard is I've built it up to be but it takes a good chunk of time. In your fork, make commits after every stage adhering closely to the [commit style I've described](#style-guide). If you're unsure of a workflow or why I recommend that commit style, take a look at an [old commit of mine](https://github.com/AB1908/CS-Books/commit/83d0dd8ca9ab9a2fa15a4dc459b83e08947767b3) to get an idea. I usually make changes incrementally and then while merging the branch, I squash all the commits so they look like one nice list of steps I took. You **must** go through the [Pull Request Template](PULL_REQUEST_TEMPLATE.md), otherwise I'm going to have one hell of a time merging your Pull Request. Once you're done, you deserve an extra special thanks for your effort.

## Style Guide

The formatting style for pull requests is described in the template linked above. Apart from those, I would also strongly encourage good commit messages in adherence to the following:

- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
- No period/full stop after the commit message
- Limit the first line to 72 characters or less
- Reference issues and pull requests liberally after the first line

Further resources on how to write good commit messages can be found [here](https://chris.beams.io/posts/git-commit/), [here](https://gist.github.com/robertpainsi/b632364184e70900af4ab688decf6f53), and [here](https://hackernoon.com/what-makes-a-good-commit-message-995d23687ad). If you're unfamiliar with Git in general, I'd recommend reading through the [Official Pro Git Book](https://git-scm.com/book).

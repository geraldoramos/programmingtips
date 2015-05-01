# Tips For Doubling Your Programming Speed

## Use the Rubber Duck technique

When you’re trying to figure out how to accomplish a coding task, often times it helps to crystalize your approach by asking the right question.  The reason is by asking a question, it mentally maps your mind around the problem and you often realize your approach may be incorrect, leading to additional questions and new revelations for how the problem should be tackled.  The Rubber Duck technique is to ask an inanimate object (a duck) that question.  This is an inexpensive layman’s substitute for pair programming.  It may be silly, but it works!

## Avoid gold-plating and build the minimum needed for feedback

It’s often tempting to look at each feature of your system and build in as many bells/whistles as possible.  The reality is that most software projects fail and most software is never used.  Once you realize this, you can take an approach of building the minimum needed for user feedback to ensure that the feature is indeed useful.  This is similar to lean startup principles that startup companies use.

## Master your Editor

The only good editor is one you're comfortable with and like using. It's a very personal choice and you shouldn't be afraid to experiment with different ones, nor should you choose one exclusively over all others. Like programming languages, each has its own toolset and is good at different things.

### Vim

Vim can be a very powerful tool. Understanding that 'normal mode' commands are actually a **language** with a grammar including verbs, nouns, and other types of objects means that as you learn more actions, you can begin to speak directly to your editor, conveying the changes to the text you want to make at a human conceptual level, as opposed to a series of mechnical motions to manipulate a page of text that hearken back to the days of typewriters.

### IDEs

An "IDE" is, roughly, a text editor with a set of acessory features designed to make manipulating **code** easier, as opposed to editors which work at the lower level of treating files as essentialy discrete blobs of contextless data. There are no hard rules dictating what an IDE is, and again, the key is to find an editor that you are comfortable with and has features and capabilities that fit the task at hand. Some IDEs are written specifically for certain languages; Eclipse has a massive host of features related to organizing and efficiently modifying Java source code. IDEs often times have many useful keyboard shortcuts.  They can be hard to memorize, so you can always make a cheat-sheet.  You don’t need to use the IDE defaults either -- rebind them to those you’re familiar with.

## Prefer to use the command line over the mouse

It’s always going to be faster to navigate and execute commands using a keyboard instead of a mouse.  Configure your machine so that you can use tab-completion to easily navigate into folders by typing partial names.  Make symbolic links for commonly used folders.

## Do it right, the first time

You may feel pressure to write code fast due to deadlines.  It’s important to manage expectations and be realistic about your commitments when agreeing to complete tasks.  This is because spending the proper time to do it right is always going to be a better long-term time-savings than redoing things due to buggy code or improperly architected systems.

## Work in small batches

Working in small batches reduces the granularity of your code check-ins which reduces potential collisions and integration headaches with other developers.  It is this lack of parallelism which kills productivity in software development.  It also reduces project risk since features are integrated quickly for fast-feedback.

## Use continuous integration and (if possible) continuous deployment

By running automated tests at code-check-in, and even deploying to live multiple times per day, you ensure that your test-suite is properly built-out so that errors are caught quickly, rather than bogging down your time later due to untraceable problems.  This saves significant debugging time.  Note that there is a careful balance between “too many” tests and “not enough” tests -- if your test suite is too large and unwieldy then that becomes a beast to maintain on its own, and the test suite can itself have bugs in it!

## Think first, code second

Most programmers rush into programming as soon as possible rather than thinking about design and architecture.  This can be due to ego (bragging about how fast a system was written) or simply laziness.  The result can be a massive refactoring later of your system, sapping your time.  What most programmers don’t realize is that momentum is a very powerful force in software development.  The first approach you take can often become a permanent fixture of your code, since business forces will pressure you to work on higher-priority tasks than a rewrite of an existing system.

## Avoid temptations for writing bad code for job security

Some developers intentionally write uncommented code, or sloppy code, since they figure that the tougher their code is for someone else to understand and maintain, the more job security they’ll have.  In reality, the best programmers don’t need this type of security.  Aspire to be the best -- by writing clean, commented code, your development speed will increase as a result, and that’s the type of job security you want.

## Use asserts as often as possible in your code

Assertions are a great complement to test cases.  By placing assertions in your code, you can easily find the root cause of issues, especially if you create useful debugging messages to accompany those assertions.  You’ll still have ng This makes sure that, if your code has a bug, it fails fast, with a good diagnostic error message, and close to the root of the problem.

## Tap into an expert marketplace like HackHands

HackHands can more than double your software development productivity by getting you “unstuck” every time you find yourself pulling your hair out on the same programming problems.  The way it works is you “hire’ an expert for a small fee, and he looks at your code through screenshare and video chat.  In a matter of minutes you can be productive again.  These services can be nice since you can access expertise on a specific library, and you don’t need to bother your co-workers.

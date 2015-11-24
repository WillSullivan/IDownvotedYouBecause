#####*Are you a Github Jekyll wizard? I'm not. Can you help? See [this issue](https://github.com/WillSullivan/IDownvotedYouBecause/issues/3) for details!*

IDownvotedYouBecause... is a quick and dirty way to give other users detailed information on why you downvoted their post and what they can do to fix it--politely, and with lots of information.

###How does this work?

Simply put, you paste a URL in a comment on a post you have downvoted.  The URL points to a page of the website that contains detailed information about why you downvoted:

* What the user did
* Why this is something worth a downvote
* What the user can do to fix the problem
* Instructions on how they can gather information and update their post

Simply drop the URL of one of the site's pages that match your downvote reason into a comment/your own post.

###How are these pages created?

The website is hosted on [GitHub.io](http://github.io), backed by a [GitHub repository](https://github.com/WillSullivan/IDownvotedYouBecause).  Through collaborative editing, a nice healthy selection of pages may be accumulated over time.

###How would that work?

In simplest form, someone wishing to add a new downvote reason could create [an issue](https://github.com/WillSullivan/IDownvotedYouBecause/issues/new) in the repository with details about the page they want to add

* Community name
* Community abbreviation, if it doesn't exist (e.g., so => Stack Overflow, r => reddit, i => imgur)
    * URL paths are prefixed with the community 
* Page URL (PascalCased, to the point)
* Answers to the following questions:
    * What did the user do
    * Why is that worthy of a downvote
    * **What can be done to fix this**
    * Any additional relevant details about any of the above

Given as much of this as possible, I'll do my best to create the page and add it to the running list within a reasonable period of time.  

Alternatively, contributors can fork the repository, make all the edits they want themselves, then submit a pull request.  This should be easier once Jekyll integration is fixed.

Realistically (as in, what will probably happen unlike the above two options), I'll be the one adding new stuff as I downvote my way through the internet.

If you like, please use. Got an idea? Please create an Issue, or send me a pull request.  Thanks.


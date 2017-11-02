---

title: Change Management for your Thesis
layout: page

---

Change management is really important when writing your thesis, for a few reasons. For one, a change management platform like BitBucket or Github kind of acts like a remote backup service --- backups are obviously very important to have when it comes to something as important as your thesis!

Change management matters for other reasons too, though. It's an easy way to share your work with others, as well as collaborating on different versions of a document.

If your research involves any programming code, version control can be *vital*, and increasingly researchers are calling for others to share the code that lead to their results. You might as well start now.

Lastly, change management can make working on the same codebase / paper in multiple places far easier, because edits to the code / documents can be merged together, or synced between different devices, very easily.

## Setting up change management

Here's some advice on setting up change management for your thesis from [Tim Storer's advice document to new PhD students](https://github.com/twsswt/glasgow_socs_phd_bootstrap/blob/7809bee64b55ac714a8bee4d8e6de926776513ce/README.md):

1. Create a Github, bitbucket, or similar hosted change management account.  Choose a service that supports
   fully-fledged change management tools like Subversion, Git or Mercurial.  Dropbox or other file synchronisation tools
   don't count.  If you are worried about sharing your thesis publicly then you can use a private repository (Bitbucket
   offers this for free, Github makes you pay)
2. Clone Stephen Strowe's LaTeX [thesis template](https://github.com/sdstrowes/Glasgow-Thesis-Template) for Glasgow
   University and host the clone in your GitHub account.
3. Clone the repository in your account onto as many of your local devices as you like.
4. Edit the meta-data in the thesis (author name, thesis title).  This will make you feel like you own it.  Commit the
   changes back to your hosted repository.
5. Offer to share the repository URL with your supervisor.  This is an effective way of receiving comments (as pull
   requests or issues).
6. Commit *everything* you write about to the thesis document you've created.  Do these commits regularly (at least once
   a day) even if it is just notes.  Don't put your notes into private Word documents, or other text documents that
   don't get included in the repository.

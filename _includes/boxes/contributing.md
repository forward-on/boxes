# Contributing

You are considering a contribution to *boxes*? That's fantastic!

All *boxes* development has moved to the GitHub social coding platform:

  - [Sources](https://github.com/{{ site.github }})
  - [Bug Reports and Feature Requests](https://github.com/{{ site.github }}/issues)
  - [Development Wiki](https://github.com/{{ site.github }}/wiki)
  - [Change Log](https://github.com/{{ site.github }}/commits/master)
  - [History of Releases](https://github.com/{{ site.github }}/wiki/Release-History)

Boxes has been around a long time. It is available for many platforms (in reality for many more than those featured on the [download page]({{ site.baseurl }}/download.html)). Great care has been taken to make the *boxes* source as compatible as possible with all kinds of different platforms.

The planned functionality has long been implemented, and it is very stable. Development has thus slowed down and concentrates on maintenance and contributor-supplied changes.

The author can be contacted by email anytime, but please do not be offended when the response is slow. Even if it takes weeks or months, your email is never lost!

## Contribution Process

Changes must be introduced by creating pull requests on GitHub. Note that you can improve the *boxes* code as well as the website content! Ideas for new box designs should be submitted via GitHub, but since the most beautiful designs sometimes come from non-technical people, emails are acceptable for those.

It is best to discuss the planned change before actually doing work on it by [creating an issue for it](https://github.com/{{ site.github }}/issues). This is really not a big deal, but it helps to ensure that your work will end up on the *boxes* master branch.

In order to create a pull request, you must first [fork the *boxes* repo](https://help.github.com/articles/fork-a-repo/). Then create a new feature branch for your change. Commit the changes to your feature branch. After that, you can [create the pull request](https://help.github.com/articles/using-pull-requests/) against the *boxes* master.

The pull request must meet the criteria mentioned below. If additional changes are identified during the review, you can simply push them to your forked repo, and the pull request will update automatically.


## Pull Request Acceptance Criteria

Since *boxes* is not actively being developed anymore, changes to the code base must be "production ready" from the start. The following check list may help:

  - The [Travis CI build](https://travis-ci.org/{{ site.github }}) must pass for the pull request. This is indicated by a small green check mark next to your pull request.
  - Provide [test cases]({{ site.baseurl}}/testing.html) for any code that you add. This helps make sure that nobody else breaks it later.
  - Cross-platform compatibility is very important for *boxes*. Since *boxes* does not (and cannot really) make use of *autoconf*, the C code itself must work on every platform. In other words, you can use only such C commands that are known on every platform. When in doubt, restrict yourself to commands that you already find in the current sources.

These criteria apply only to code changes. (Although other changes should not break the build, either.)

  
## Contributors

Now that *boxes* is on GitHub, all contributors are automatically [listed on GitHub](https://github.com/{{ site.github }}/graphs/contributors). But in the years before GitHub, *boxes* has received support from additional people:

  - Ron Aaron - win32 port
  - Peter van den Berkmortel - HPUX 10 binaries of v1.0.1
  - Salvatore Bonaccorso - enable compilation on GNU/kFreeBSD and GNU/Hurd; fixes to the man page
  - Christoph Dreyer - tab unexpansion
  - Andreas Heiduk - bug fixes and compatibility improvements; Jed integration
  - Jakub Hrozek - patch to eliminate a compilation warning on Fedora
  - Yosuke Kimura - DEC alpha/OSF binaries of v1.0.1
  - Elmar Loos - 'mend' option
  - Zdenek Sekera - SGI/Irix6 binaries of v1.0.1
  - Jason L. Shiffer - Emacs integration
  - Henry Spencer - kindly permitted the use of his regular expression library for *boxes*
  - Lu Weifeng - OpenWRT port - *boxes* now runs on routers, too
  - Tommy Williams - i386/FreeBSD port
  - Joe Zbiciak - compatibility improvements and Solaris binaries

  - AlpT - the *c-cmt3* design
  - Ted Berg - the *javadoc* design
  - Neil Bird - the *ada-cmt* and *ada-box* designs
  - Bas van Gils - the *cc* design
  - Karl E. Jorgensen - the *ian_jones* design
  - Vijay Lakshminarayanan - the *lisp-cmt* design
  - Elmar Loos - the *ccel* and *underline* designs
  - Christian Molls - the *boxquote* design
  - Fredrik Steen - the *stone* design
  - Michael Tiernan - the *caml* design

Many thanks to these awesome folks!
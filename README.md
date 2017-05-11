[![GPLv3](https://img.shields.io/badge/License-GPLv3-blue.png)](https://www.gnu.org/copyleft/gpl.html)
[![LGPLv3](https://img.shields.io/badge/License-LGPLv3-blue.png)](https://www.gnu.org/copyleft/lgpl.html)
[![GNU Guile](https://img.shields.io/badge/Guile-2.1.3-yellow.png)](https://www.gnu.org/s/guile/)
[![amd64](http://img.shields.io/badge/architecture-amd64-lightgrey.png)](https://en.wikipedia.org/wiki/X86-64)
[![Travis CI](https://travis-ci.org/NalaGinrut/artanis.png)](https://travis-ci.org/NalaGinrut/artanis)

GNU Artanis needs a logo, contribution is welcome!
=========

NOTICE
=========
According to [GNU Ethical Repository Criteria Evaluations](https://www.gnu.org/software/repo-criteria-evaluation.html). GNU Artanis as GNU official project is not proper to be maintained on GitHub.
So I **will not** do maintenance work for GNU Artanis on github to show my position on free software.
That means I **will not** response to issues or pull requests on GitHub. Until GitHub show some respect to freedom of users on these issues:
* No other nonfree software is required to use the site (thus, no Flash). 
* Does not discriminate against classes of users, or against any country.

The maintenance repo will be these two:
* [GNU official repo](http://git.savannah.gnu.org/cgit/artanis.git/)
   Accepts patches and issues on mailing-list artanis@gnu.org

* [GitLab repo](https://gitlab.com/NalaGinrut/artanis)
   Accepts issues and pull requests.

For historical reasons, GNU Artanis will maintain the site with gh-pages on GitHub since the pages service on GitLab is very different so I can't just move it simply.
Before we have a better/modern Savannah, we have to endure this situation.

GNU Artanis
=========

GNU Artanis aims to be a web application framework for Scheme.
The philosophy of Artanis is to be very radical, and to try
cutting-edge things.
So use it at your own risk...however, playing with it may result in
some cool experiences!

## Features:

* GPLv3+ & LGPLv3+
* Very lightweight - easy to hack and learn for newbies.
* Support JSON/CSV/XML/SXML.
* A complete web-server implementation, including an error page handler.
* High concurrent async non-blocking server core based on delimited continuations.
* Has a Sinatra-like style route, hence the name "Artanis" ;-)
* Supported databases (through guile-dbi): MySQL/SQLite/PostgreSQL.
* Nice and easy web cache control.
* Efficient HTML template parsing.
* Efficient static file downloading/uploading.

## Manual:
http://gnu.org/software/artanis/manual

## Research paper:
* ICFP Schemeworkshop 2016
  [Multi-purpose web-framework design based on websockets over HTTP Gateway](https://gitlab.com/NalaGinrut/artanis/raw/gh-pages/research/scheme16/art2016.pdf)

## How to contribute:

* Contributing to the website -

  The source to the manual is in the gh-pages branch.

  Please **do not** modify the HTML pages directly. The pages are generated by a certain static page generator, so please take a look at the concerned directory -

  https://gitlab.com/NalaGinrut/artanis/tree/gh-pages

* Contributing to the manual -

  The source to the manual is in the gh-pages branch.

  Please **do not** modify the manual.texi and manual.html files directly, as they are generated by org-mode. The file to be edited is 'manual.org' -

  https://gitlab.com/NalaGinrut/artanis/blob/gh-pages/docs/manual.org

* Contributing to the Artanis framework -

  Thank you very much for contributing!

  In my opinion, bug reports are the most significant contributions. Please don't hesitate to report in a proper way for me to reproduce.

  Please read the manual carefully, and ask questions to know more about GNU Artanis. The preferred way to discuss internals of Artanis is to send
  mail to artanis@gnu.org because it's good for archive. And you could discuss the bugs in issues for better tracking than mails.

  I'll write articles about GNU Artanis occasionally on my blog: nalaginrut.com

  GNU Artanis is aiming for product quality, since it's going to be used in a real product. So we need the contributions in good quality.
  The tiny or obvious fixes will be more likely to be applied. But bigger contributions will be under strict review and discussion.

  Artwork and document writing is important contributions too and great appreciated in GNU Artanis community. So does advocating on your blogs, wikis,
  and webcasting tutorials. They're good ways to help GNU Artanis to form a community.

  If you're using GNU Artanis in product or own purpose, please share your experiences. GNU Artanis wants to build a friendly community to help
  people know more about free software and help functional programming to be used in industry.

## Thanks for testing!
* Fedora release 20 (Heisenbug)

  Long Li <atommann AT gmail.com>

* Arch

  @42cmonkey

* Debian 7.8

  NalaGinrut

* Debian 8.0 GNU/Hurd 0.5 & GNU-Mach 1.4+git20150208

  NalaGinrut

* Debian strech/sid
  
  NalaGinrut

* OpenSUSE 12.2

  NalaGinrut

* OpenSUSE 13.2
  
  NalaGinrut

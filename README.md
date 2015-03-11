Todo
=======

 This applicatoin was inspired from Mackenziechild 12 in 12 challenge
 I followed his video learning rails.

 Here are some differences between Mackenziechild's version
- use **slim** instead of haml

### Version
none

### Tech
* [slim] - A lightweight templating engine
* [font awesome] - Font Awesome gives you scalable vector icons that can instantly be customized
* [bootstrap] - Bootstrap, a sleek, intuitive, and powerful mobile first front-end framework for faster and easier web development.
* [google font] - Normalize.css makes browsers render all elements consistently and in line with modern standards.

### Installation

I use rvm with ruby 2.2.0 and rails 4.2.0. Because of spring, I need to use bin/bundle to make all extra cmds workable. I also exploit pow to start server. It is very convenient tool.

```sh
$ git clone [git-repo-url] rails-todo
$ cd rails-todo
$ bin/bundle install
$ powder start
$ powder link
```

### Notes
I revised some styles as I mentions. I change on div which class='post' in posts/index.html.slim from float to inline-block, so that we can avoid some trouble while descriptions are too long.


### Dependencies
None
### Todo's
None
###License
None





[slim]:http://slim-lang.com/
[font awesome]:http://fortawesome.github.io/Font-Awesome/
[google font]:http://www.google.com/fonts/
[bootstrap]:http://getbootstrap.com/2.3.2/


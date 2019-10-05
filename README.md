# Goals
- To introduce experienced programmers to working with Clojure in a 2-hr meetup or similar session
# Intended audience
- Programmers experienced with at least one programming language and the command-line
# Outcomes
- Attendees feel confident enough with Clojure and its tooling to explore further on their own
# Scope
- Get a feel of Clojure the language
- Start right away with the tooling i.e. REPL and friends
- Learn by doing, practice rhythm, praxis, we'll switch between theory and practice
- Develop simple programs, Project Euler would be a good fit
# Decisions
- Our choice of editor is vanilla emacs and add-ons for Clojure and navigation
- Choice of editor is governed by what is most feasible to support
- Choice of editor is goverened by the importance of getting everyone started on an even footing
- The advanatges of these 2 will offset difficulties related to learning curve
- To smoothen any learning curve, we'll introduce new knowledge right where they are needed
- The choice of editor and tooling here is only for the session, it's a means to an end at best
# What we won't get into
- Language wars
- Editor wars
- Wars ...
- Superiority of FP

# Setup
Setup Emacs with https://github.com/koljure/beginning-clojure-emacs.d  
* General 
  - A terminal client
  - Java 8 or higher
  - [Clojure](https://clojure.org/)
  - [Leiningen](https://leiningen.org/)
  - [Emacs](https://www.gnu.org/software/emacs/) 

* Sample setup guide (for Mac)
  - [Install JRE on Mac](https://java.com/en/download/help/mac_install.xml)   
    *or*       
    use *Brew* package manager `brew cask install java`   

  - Install **Clojure** using *Brew* package manager- `brew install clojure`  
  - Install **Leiningen** using *Brew* package manager- `brew install leiningen`    
  - Install **Emacs** using *Brew* package manager- `brew cask install emacs`  
      Setup Emacs on Mac-  
      1) `git clone https://github.com/koljure/beginning-clojure-emacs.d.git`
      2) `mkdir -p ~/.emacs.d`
      3) `mv ./beginning.../init.el ~/.emacs.d/init.el`  


# Resources
* [Brave Clojure](https://www.braveclojure.com/foreword/)
* [Living Clojure](https://www.oreilly.com/library/view/living-clojure/9781491909270/)

# Copyright and license
- Copyright © 2019-2020 Koljure.
- Distributed under the EPL license.


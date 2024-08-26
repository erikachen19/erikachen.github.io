---
layout: post
title:  "Create Github pages"
date:   2024-08-26 10:15:00 +0700
categories: [python]
---


### How to do it?

1) Install Ruby (https://www.youtube.com/watch?v=semqYpqoY_k)
  https://rubyinstaller.org/downloads/
  with Devkit
2)CMD
  gem install jekyll
  
  enter(1,2)
  
3)Fork https://github.com/agusmakmun/agusmakmun.github.io/tree/master (erikachen.github.io)
  link: https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo
4)Clone https://github.com/erikachen19/erikachen.github.io
5)Edit site settings inside file of _config.yml
6)
  bundle install --path vendor/bundle
  bundle exec jekyll serve
  ERROR: 
      "undefined method untaint"的解决
      https://james-qin.me/posts/undefined-method-untaint/
      
      rm -f Gemfile.lock
      bundle
  	bundle install --path vendor/bundle
      
      bundle exec jekyll serve
  	
  Then visit the http://127.0.0.1:4000


Link youtube:https://www.youtube.com/watch?v=g6AJ9qPPoyc(How To Build A Website | Github Pages | Jekyll | Template)






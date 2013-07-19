This project demonstrates how to load different Jasmine test suites (desktop, mobile etc) using jasmine, jasmine-headless-webkit

jasmine-headless-webkit's guide

http://johnbintz.github.io/jasmine-headless-webkit/

Run desktop test suites

jasmine-headless-webkit -c -j spec/javascripts/support/jasmine.yml spec/javascripts/desktop/*.js

Run mobile test suites

jasmine-headless-webkit -c -j spec/javascripts/support/jasmine.yml spec/javascripts/desktop/*.js
# heroku-buildpack-qt-webkit
Working QT buildpack for Heroku

This buildpack was created to successfully install capybara-webkit 1.15.1 (depends on QT5.5) on Heroku Cedar-18
Heroku APT buildpack should be installed first, and project should contain Aptfile. 

The command "heroku buildpacks" should look as follows

  1. heroku-community/apt
  2. https://github.com/rootstrap/heroku-buildpack-qt-webkit
  3. heroku/ruby

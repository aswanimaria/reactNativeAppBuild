# Steps for Creating fastlane build
## install fastlane using homebrew
## setup fastlane
## execute the below commands in ios folder
#fastlane init #(select manual setup )
#fastlane init swift
## copy the fastlane folder to root directory or directly create a folder "fastlane" in root directory and create a file named "Fastfile" inside it (both will work)
## set environment variable
#export LC_ALL=en_US.UTF-8
#export LANG=en_US.UTF-8
## create Gemfile in root directory with content 
#source "https://rubygems.org"
#gem "fastlane"
## Execute script gem install bundle
## Execute script bundle install
## Edit Fastline inside fastlane folder as per our requirements (refer fastlane folder inside root directory)
## Execute script for running build lane
#bundle exec fastlane ios build

# TravisCI link
#https://travis-ci.com/github/aswanimaria/reactNativeAppBuild

# Platform
#ios

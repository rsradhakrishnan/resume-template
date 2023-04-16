# Sreenivasa Radha Krishnan Rayaprolu's Resume 

### Setup Instructions for Windows 

To test locally, run the following in your terminal:

1. Clone repo locally
2. Delete or rename the existing `Gemfile` and `Gemfile.lock` files.
3. Install Bundler: `gem install bundler`
4. Initialize Bundler: `bundle init`.
   This will create a new Gemfile.
6. Open the Gemfile in a text editor.
7. Remove the existing contents. Then paste in the following:
   ```
   source "https://rubygems.org"
   gem 'wdm'
   gem 'jekyll'
     ```
8. Save and close the file.
9. Type `bundle install`.

### Testing Website locally

1. Open CMD in Project folder.
2. type `jekyll serve`. This will start the server and provide you IP for localhost.

### Running locally with Docker

To test locally with docker, run the following in your terminal after installing docker into your system:

1. `docker image build -t resume-template .`
2. `docker run --rm --name resume-template -v "$PWD":/home/app --network host resume-template`



#### Credits
This Project is inspired from [@jglovier](https://github.com/jglovier/resume-template)

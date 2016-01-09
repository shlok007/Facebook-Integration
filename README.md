

## Description

An app to automatically reply to all birthday posts on a user's timeline with a custom message. It uses OmniAuth and Koala gem for user authentication using facebook.

## Rails Version
Version of rails used in this project is 4.2.2 .A gem file containing the version numbers of each gem used in this application is present. 

##Installation

To install rails in linux based system follow the following guide: http://railsapps.github.io/installrubyonrails-ubuntu.html
Windows and Mac OS users refer to: http://railsinstaller.org/en 

## Contributing
Follow the following steps to setup development environment and start contibuting to proj_05:

##Setup proj_05 in development environment for linux

1. Clone the repository by running the following command:     
  
         git clone https://github.com/shlok007/proj_05.git proj_05

2. Move inside the directory of proj_05:
         
         cd proj_05

3. Run the following to install all required gems:
         
         bundle install

4. To use database run migration by:
         
         RAILS_ENV=development rake db:migrate

5. The rails server command launches a small web server named WEBrick which comes bundled with Ruby.Just run:
         
         bin/rails server

6. All set now. Visit [http://localhost:3000][localhost] to view the rails app in development environment.

[localhost]: http://localhost:3000

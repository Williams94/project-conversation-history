## Project Conversation History

This is a Ruby on Rails web application that allows users to keep track of conversations and status updates for projects. Users can leave comments and change the status of a project, and the conversation history will list all comments and status changes.

## Installation
To run the application, you will need to have Ruby, Ruby on Rails and Node.js installed on your system.

## Back-end
Once you have Ruby on Rails installed, you can clone the repository and install the dependencies by running:

1. `git clone https://github.com/yourusername/project-conversation-history.git`

1. `cd project-conversation-history`

1. `bundle install`

You will also need to set up the database by running:


1. `rails db:create`

1. `rails db:migrate`

## Front-end

The front-end is built using React and located under the root directory of the project `./front-end-project-conversation-history`

1. `cd ./front-end-project-conversation-history`
1. `npm install`

# Development
## Starting the app locally
To start the application, run:

`rake start`

## Testing the app

To run the main spec testing the message endpoints, run:

`bundle exec rspec ./test/controllers/messages_controller_spec.rb`

To run the React tests, first cd into the front-end directory:

`cd ./front-end-project-conversation-history`

Then run:

`yarn test`

# Usage
The conversation history is rendered with the newest messages at the top.

To add a new message, enter your comment in the text field and click the "Send Message" button.

To change the status of a project, click on the "Project Status" dropdown menu and select the new status from the dropdown menu.

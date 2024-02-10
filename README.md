# README

This todo list app is built with Ruby on Rails and utilizes the Hotwire technology stack. It serves as a practical project to enhance understanding of Hotwire's real-time updates and interactivity features.

<img width="579" alt="image" src="https://github.com/kisiohlova/todo_list/assets/64698588/de7d2ecb-a362-4623-b16c-87e479e806b8">


## Requirements:
* Ruby version: 3.1.2
* Rails 7.0.8
* PostgreSQL
  
## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/kisiohlova/todo_list.git
   ```
2. Install dependencies:
    ```bash
     bundle install
    ```
3. Set up the database:

   Add your db credentials in config/database.yml
    ```bash
     rails db:create
     rails db:migrate
    ```
4. Start the Rails server:

    ```bash
     rails s
    ```
5. Visit http://localhost:3000 in your browser.

## Usage

* Open the app in your browser.
* Create a new task using the input field.
* Edit task by clicking on task name.
* Mark tasks as complete or delete them.
* Experience real-time updates as tasks are added or completed.

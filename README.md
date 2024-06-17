# TrueVote

TrueVote is a simple Django polling application, following the official Django documentation tutorial.

## Overview

TrueVote allows users to view and vote on polls created by administrators. It includes functionality to display recent polls, view poll details, vote on choices, and see poll results.

## Features

- **Polls Listing**: Displays a list of recently published polls.
- **Poll Details**: Shows details of a specific poll including its choices.
- **Vote Submission**: Allows users to vote on choices for a selected poll.
- **Results**: Displays the results of a poll after voting.

## Installation

To run this project locally, ensure you have Python and Django installed.

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd TrueVote
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Apply database migrations:

   ```bash
   python manage.py migrate
   ```

4. Create a superuser to access the admin interface:

   ```bash
   python manage.py createsuperuser
   ```

5. Start the development server:

   ```bash
   python manage.py runserver
   ```

6. Access the application at `http://127.0.0.1:8000/`.

## Usage

### Admin Interface

- Create, modify, or delete polls and choices using the Django admin interface at `http://127.0.0.1:8000/admin/`.

### Viewing Polls

- Visit the home page (`/`) to view a list of available polls.
- Click on a poll to view its details and vote.

### Voting

- On the poll details page, select a choice and submit your vote.
- After voting, you will be redirected to view the poll results.

## Project Structure

- **polls/**: Django app directory containing models, views, and templates.
- **polls/models.py**: Defines `Question` and `Choice` models.
- **polls/views.py**: Contains views for rendering poll-related pages.
- **polls/templates/polls/**: HTML templates for rendering pages.
- **polls/admin.py**: Configures admin interface for `Question` and `Choice` models.

## Screenshots
![admin](https://github.com/MANOJKUMAR0404/Polls_django/assets/159749880/f56490eb-f363-48d5-b675-9d27b339d660)


![index](https://github.com/MANOJKUMAR0404/Polls_django/assets/159749880/a10dd309-b697-4944-b02d-2c80e74af1f8)


![poll_detail](https://github.com/MANOJKUMAR0404/Polls_django/assets/159749880/41f688f8-4fd4-4f58-b8cc-4ce22c62d863)


![poll_result](https://github.com/MANOJKUMAR0404/Polls_django/assets/159749880/8373ba74-1f01-403d-9313-eeb91dc57b73)

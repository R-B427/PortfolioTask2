# PollApp

---

## 📌 Project Description
PollApp is a Django-based web application that allows users to create polls and vote on them.  

It demonstrates the core principles of the Django framework, including models, views, templates, and forms.  
This project is important because it provides a practical foundation for understanding full-stack development with Django and can be extended into larger, more complex applications.

---

## 📑 Table of Contents
1. [Project Description](#-project-description)  
2. [Installation](#-installation)  
3. [Usage](#-usage)  
4. [Credits](#-credits)  

---

## ⚙️ Installation

Follow these steps to set up the project locally:

```bash
# Clone the repository
git clone https://github.com/R-B427/PortfolioTask2.git
cd PortfolioTask2/pollapp

# Create and activate a virtual environment
python -m venv venv
# On Windows
venv\Scripts\activate
# On Mac/Linux
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

##Usage

Start the development server
python manage.py runserver

Open the app in your browser
http://127.0.0.1:8000/

User Registration & Login

Click Sign Up to create a new account.

Fill in your username, email, and password.

After signing up, log in using your credentials.

Creating a Poll (Owner Only)

After logging in, navigate to the Create Poll page.

Enter a poll question and add multiple choices.

Click Submit to publish the poll.

Only the poll creator can edit, update, or delete the poll.

Voting on a Poll

Browse available polls on the homepage or use the search/filter options.

Click a poll to view its choices.

Select your choice and click Vote.

You can only vote once per poll.

Viewing Results

After voting, you are redirected to the poll results page.

For ended polls, the results are visible without voting.

Filtering & Searching Polls

Use the search bar to find polls by name.

Filter polls by publish date or number of votes.

Pagination ensures you can navigate through all polls efficiently.

##Features

-Create new polls with multiple choices

-Vote on polls in real time

-View poll results instantly

Credits

R.Brown - Author
https://github.com/R-B427/

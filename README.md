<<<<<<< HEAD
# Foundit
Introduction to Foundit, a CU CSCI 3308 Team Project.

## Who
Name | Github ID
--- | ---
Eugene Ho |	 hoeugene
Ryan Davis |	 LogicianJones
Kenneth Ford |	 kefo7771
Luke Hao Nguyen | lung9198

## Title
Foundit

## Description
Foundit is a Reddit analytics tool. Users will be able to see topline stats on Reddit subreddits and users. Stats
may include: users with the highest number of karma points, most popular subreddits, most popular threads, subreddit popularity trended over time, most popular memes, etc. We will use data visualization to display the stats on a custom website.

## Vision Statement
Identifying what is popular on Reddit. 

## Motivation
We love data and Reddit. Part of being a good Reddit user is knowing what is trending and what keeps other Reddit users engaged. By identifying which threads and posters are the most popular, when popular posts are posted, and how long a thread or meme maintains interest, we will get insights into the elements that make up popular content on Reddit.

## Risks
Format of the data and its contents are unknown.
We do not know how we will pull the data.
Some team members will be working with new languages.
No one on the team knows HTML.
Team members are working on other projects which might lead to issues with workload.
Time estimates may be way off and we may be committing to too much.

## Mitigation Strategy
If the data appears unusable, we will use another data set.
If we cannot extract the data, we will use another data set.
If a member of the team is struggling with a specific language, they will be switched to another area of the project.
If it is too difficult to build a website from scratch, we may use a web development GUI.
If a team member's workload becomes too much, others on the team will need to pick up the slack or we will scale back the scope.
If time is an issue, we will pull back on the scope of the project (fewer stats or simpler visualizations.)

## Requirements
* As a user I want to see Reddit data so I can analyze Reddit use
  * Story points: 20 ID: 1
* As a user I want a URL so I can access the Foundit website
  * Story points: 3 ID: 2
* As a user I want to know who gets the most karma on a thread so I can learn what Reddit users like
  * Story points: 5 ID: 3
* As a user I want to know what time most popular posts are posted best so I can post during those times as well.
  * Story points: 5 ID: 4
* As a user I want to know what day of the week the most popular posts are posted best so I can post on that day as well.
  * Story points: 5 ID: 5
* As a user I want to know which Reddit boards get the most activity so I know where to post.
  * Story points: 5 ID: 6
* As a marketer I want to know which memes are the most popular so I can send them to my creative agency for inspiration.
  * Story points: 20 ID: 7
  
## Methodology
Agile

## Project Tracking software
Trello
https://trello.com/b/2721YJ2D

## Project plan
![](https://github.com/RobinsonK/CSCI3308_Foundit/blob/master/images/ProjectPlan.png "Project Plan")
=======
# python-getting-started

A barebones Python app, which can easily be deployed to Heroku.

This application supports the [Getting Started with Python on Heroku](https://devcenter.heroku.com/articles/getting-started-with-python) article - check it out.

## Running Locally

Make sure you have Python [installed properly](http://install.python-guide.org).  Also, install the [Heroku Toolbelt](https://toolbelt.heroku.com/) and [Postgres](https://devcenter.heroku.com/articles/heroku-postgresql#local-setup).

```sh
$ git clone git@github.com:heroku/python-getting-started.git
$ cd python-getting-started

$ pip install -r requirements.txt

$ createdb python_getting_started

$ python manage.py migrate
$ python manage.py collectstatic

$ heroku local
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```sh
$ heroku create
$ git push heroku master

$ heroku run python manage.py migrate
$ heroku open
```
or

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Documentation

For more information about using Python on Heroku, see these Dev Center articles:

- [Python on Heroku](https://devcenter.heroku.com/categories/python)
>>>>>>> ufoundit/master

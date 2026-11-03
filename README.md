# Daily Game, by Kevin Patto

## Description

This is a website for a daily game in which players are given a unique start in tetris and 50 pieces to try to get the highest score. The website will have a login system where users can track their scores, view previous days' games, and view a leaderboard.

## Technologies Used

Django, bcrypt

## Prerequisites

Django 6.1.2

## Installation

1. Download .zip from GitHub project.
2. Extract files into directory ```~/daily-tetris-puzzle-game-main```.
3. Open CLI in project directory ```~/daily-tetris-puzzle-game-main/daily-tetris-puzzle-game-main```. (this guide will only include instructions for Windows)
4. Type in ```py manage.py migrate``` to initialize database.
5. You can now visit the website on your browser at http://127.0.0.1:8000.
6. Please refer to the configuration section to create an admin account.

## Configuration

To create an admin user, type ```py manage.py createsuperuser```. Ensure password meets specifications listed if you entered an insufficient one. When successful, ignore the syntax warnings, your account will be completed.

## Running the application

Type ```py manage.py runserver``` while in the project's directory in your CLI.

## Known limitations

Frontend not developed yet, will have to decide what to use next sprint. This sprint only implemented the log in system, models are incomplete. The frontend will most likely not be from Django, and the Django server itself will be converted into an API.
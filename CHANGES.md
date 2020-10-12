# Change Log

## v0.1.2

* Updated actions with the generate_actions.py script and the 4.8.9 API spec

## v0.1.1

* Fixed API authentication not working when username/password contains special characters.
  Now usernames and passwords are passed into `requests` properly so they are URL encoded, escaping
  any special characters. (Bugfix)
  
  Contributed by Nick Maludy (@nmaludy Encore Technologies)

## v0.1.0

* Initial Revision

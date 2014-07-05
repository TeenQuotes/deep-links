Deep links
==========

## The fuck is this?
This is a list of paths used for [mobile deep links](http://en.wikipedia.org/wiki/Mobile_deep_linking) in the Teen Quotes website.

## Documentation
Teen Quotes uses [AppLinks](http://applinks.org/documentation/) for metadata. Take a look at the documentation.

iOS and Android packages are available in order to implement deep linking.

## Quotes
### Homepage
Base URL:

	TeenQuotes://home

Pagination available:
	
	TeenQuotes://home?page=42

### Random
Base URL:

	TeenQuotes://random

Pagination available:
	
	TeenQuotes://random?page=42

### Adding a quote

	TeenQuotes://addquote

## Users' profile
### Published quotes
Quotes published by the user.

Base URL:

	TeenQuotes://users/:login/published

Pagination available:

	TeenQuotes://users/:login/published?page=42

Full example: 

	TeenQuotes://users/antoineaugusti/published?page=42

### Favorites quotes
Quotes in the favorites of the user.

Base URL:

	TeenQuotes://users/:login/favorites

Pagination available:

	TeenQuotes://users/:login/favorites?page=42

Full example: 

	TeenQuotes://users/antoineaugusti/favorites?page=42

### Comments
Comments posted by the user.

Base URL:

	TeenQuotes://users/:login/comments

Pagination available:

	TeenQuotes://users/:login/comments?page=42

Full example: 

	TeenQuotes://users/antoineaugusti/comments?page=42

### Edit the user's profile
Only available for the logged in user.

Base URL:

	TeenQuotes://users/:login/edit

Full example: 

	TeenQuotes://users/antoineaugusti/edit


## Authentication
### Sign in
To connect to the user's account:

	TeenQuotes://signin
	
### Sign up
To create an account:

	TeenQuotes://signup

### Password lost
To reset a password by providing an email address (will send a reset token):

	TeenQuotes://password/remind

### Password reset
Show the form to reset a password using a reset token (previously sent by e-mail):

	TeenQuotes://password/reset?token=:token

Example:
	
	TeenQuotes://password/reset?token=28e356e796bb3b98359d13a01dbeeb423d10d7c0

## Contact

	TeenQuotes://contact

## Legal terms

	TeenQuotes://legal.show

## Apps
Download Teen Quotes applications:

	TeenQuotes://apps

## Support and bug reports
Contact Antoine Augusti at antoine.augusti@teen-quotes.com
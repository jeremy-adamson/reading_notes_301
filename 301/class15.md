# Authentication

## What is OAuth

* What is OAuth?
  * An open-standard authorization framework. It is a form of delegated authorization (3rd party).
* Give an example of what using OAuth would look like.
  * The equiv of going to a website and having it say "sign in using twitch/gmail/github/etc."
* How does OAuth work? What are the steps that it takes to authenticate the user?
  * 
* What is OpenID?
  * Open ID is for authentication instead of authorization.

## Authorization and Authenticaion Flows

* What is the difference between authorization and authentication?
* What is Authorization Code Flow?
  * Client asks site
  * Site asks AuthO
  * AuthO asks Client
  * AuthO tells site 'person is person'
  * Site responds with request for what person has access to
  * AuthO thinks
  * AuthO responds to site with what the person can access to
  * Site contacts API for the Data
  * Data... huzzah!!!
* What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
  * Somewhat similar to above but the site generates a code verifier
* What is Implicit Flow with Form Post?
  * An alternative to the Authorization Code Flow but can be considered outdated.
* What is Client Credentials Flow?
  * It's for machine-to-machine authentication (since no user is involved it's a bit different)
* What is Device Authorization Flow?
  * It's typically used for mobile devices where most of the login/authentication information is stored on the device already.
* What is Resource Owner Flow?
  * 

## Readings

* [What is OAuth](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)
* [Authorization and Authentication Flows](https://auth0.com/docs/flows)
* [AuthO for single page apps](https://auth0.com/docs/libraries/auth0-react)

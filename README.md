# nginx-basic-login-session
Very basic password authentication on nginx with persistent session cookie

### Why?

Sometimes you need a very basic password authentication for a site, but you also don't want users to have to keep entering the password over and over again.

### How?

This aims to solve that problem, giving devices that pass the nginx password authentication a cookie. Once they have the cookie they can get in without the login.

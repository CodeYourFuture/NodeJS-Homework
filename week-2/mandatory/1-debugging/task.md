# Debugging Practice

We've hosted some Servers on Glitch but they're not quite working properly. Could you fix them for us?

- https://glitch.com/~debugging-practice1
  https://glitch.com/~leida-debugging-practice1
  https://leida-debugging-practice1.glitch.me
  The app.get("/quotes/random" was not set up correctly, ie, the pickFromArray was not being called

- https://glitch.com/~debugging-practice2
  https://glitch.com/~leida-debugging-practice2
  https://leida-debugging-practice2.glitch.me
  I am not sure why we have to comment the get id code out when we have another get search. Where should I read about that?

- https://glitch.com/~debugging-practice3
  https://glitch.com/~leida-debugging-practice3
  https://leida-debugging-practice3.glitch.me
  The reason the App displayed "OK" is because sendStatus() sets the response HTTP status code to statusCode and send its string representation as the response body. So,
  res.sendStatus(200) is equivalent to res.status(200).send('OK')

If we want to see the message "Ask me for /quotes" we should use status() which sets a HTTP status for the response (as a Javascript object on the server side).

- https://glitch.com/~debugging-practice4
  https://glitch.com/~leida-debugging-practice4
  https://leida-debugging-practice4.glitch.me
  // The app would not start because lodash dependency was not installed

## Start by remixing our example server

- [ ] Make sure you're logged in to https://glitch.com/
- [ ] Remix each example
- [ ] Name your new server `yourname` + NAME_OF_EXERCISE
- [ ] Check that it is working by making a request to `/`
- [ ] Fix the code on your version of the server

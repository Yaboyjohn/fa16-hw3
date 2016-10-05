## Questions

Go to `localhost:3000/teachers` in your browser; why does this not work?
This fails because we didn't set up a route for /teachers only /teachers/new

What type of request did your browser just perform?
GET

Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?
localhost:3000/teachers

Why does `localhost:3000/teachers` work now?
we are now using POST, which we defined a route for

# Code Review for Desmond Heng

## Project Repo

https://github.com/wdi-sg/wdi-project-2-desmondhengwj

## Review

#### Project Purpose

To create a recruitment website for his own HR business where interested part-timers can apply for job opportunities.

On the operation side, it would be easier to track the applicants.

#### Project Organization

#### Features

* User's authentication
  * Passport was used to authenticate users upon signup and login.
* Application
  * Form was created for easy submission of application.
* Overall look
  * Bootstrap nicely applied.

#### Areas of Success (Code, Organization)

* Application
  * Form was very well formatted, making it clear and easy to use.
* Authentication
  * Authentication was blocked from all except admins, prevents applicants information from being read by anyone.
* Organization
  * Like the last project, organization was very clear and well done!

#### Areas for Improvement (Code, Organization)

* User model

```javascript
var userSchema = mongoose.Schema({
local: {
  email: String,
  password: String
}
})
```
In above user model, it would be nice to add verification to the fields to prevent signing up with email and/or password that are not valid.

* Overall Organization
  * Like what you mentioned during the presentation, putting the different functions into "router" and "controller" folders would be great. Although it might be confusing at times, but I personally think it is a good practice to follow. Try to do it at your free time!

## Additional Notes

I guess I can say that both you and I learnt a lot whist doing this project.
I am rather proud of myself for completing this project. Hope you do too! Cheers!

# Rails Assessment

It's time to put our Rails know-how to the test. Today, we have an basic new application.

## Objectives
+ MVC
+ REST
+ Request/Response Cycle
+ Form/Form Helpers
+ ActiveRecord
+ Validations

## Setup

Before you begin, fork and clone this repo, run `rake db:migrate` and `rake db:seed` to get started.

## The Domain

The app you built on Monday is now functioning great. Stephen just has a few extra requests.

## Instructions / Deliverables

1. Build out a guests show page that lists all of the episodes that guest appeared on. Each episode should link to the correct episode show page. 
2. For each of those episodes, there should an edit to edit the details of that appearence for that episode
3. On the top of the guest index page should be a link to a new route to list all of the guests, ranked by the amount of appearences they have.

### Hints / Tips

+ Remember we want to be RESTful. What URL should we use to display our edit form? What action should be responsible for updating the request?

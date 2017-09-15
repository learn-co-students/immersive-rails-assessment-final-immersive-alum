# Rails Assessment

It's time to put our Rails know-how to the test. Today, we have a basic new application.

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

You've built out an app for displaying guests and episodes on The Late Show with Stephen Colbert. Stephen just has a few extra requests. The basic site is functioning, so take a few moments to familiarize yourself with the existing MVC and relationships structure.

## Instructions / Deliverables

1. Build out a guest show page that lists all of the episodes that a single guest appeared on. Each episode should link to the correct episode show page. 
2. Each episode's show page should have an edit option to alter the details of the guest appearance.
3. On the top of the guest index page should be a link to a route that lists all of the guests, which are ordered descending by the amount of appearences they have.

### Hints / Tips

+ Remember we want to be RESTful. What URL should we use to display our edit form? What action should be responsible for updating the request?

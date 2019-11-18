# shoppingCenterIMS
shopping centre inventory management system

This exercise is intended to allow you to demonstrate your skills in building a small JavaScript-based web API. Your submission
will be assessed on the following criteria:
1. Grasp and understanding of the JavaScript language
2. Writing clearing, concise, maintainable code
3. Ability to verify the correctness of the solution



The requirements are split into
- **MUSTs**: things we expect your solution to include,
- **SHOULDs**: things we’d like to see you include, and
- **COULDs**: are nice-to-haves and you can choose to do any, all, or none of them.

You are encouraged to treat this as a microcosm of a real project, so approach it as you would any other project. JavaScript is
required, but other technologies and libraries are at your discretion and welcomed.
Please include a README with your submission which describes how to run the project and explains the approach you took to
producing the solution.
Submit your solution by either sending a link to a GitHub or Bitbucket repository containing your code, or a link to a zipped copy
of your code in Dropbox or similar.


# Exercise description
oOh!media is designing a shopping centre inventory management system which will help their product management team
maintain records of where physical display panels are installed in shopping centres. You are creating an API to manage inventory
and shopping centres, allowing persisting and modifying data, as well as (optionally) an interface for users to manage the
inventory.

# Domain
A Shopping Centre is a mall like MYER or Westfield, with many stores operating inside; placed at key locations within the Shopping
Centre are Assets, which are oOh!media units for displaying content. Shopping Centres must at a \minimum have the attributes:
Name, address, and have Assets associated with them.
An Asset is a physical screen which receives advertisement and other content throughout the day. It has physical attributes such
as its dimensions, a location within the shopping centre, and a status indicating whether it is active to
receive content or offline for maintenance. Assets must at a minimum have the attributes: Name, physical dimensions, associated
Shopping Centre, location within the centre, and status.

# Your solution
1. **MUST** have an API server written in JavaScript
2. **MUST** have routes for Shopping Centres
3. **MUST** have routes for Assets
4. **MUST** persist data to a database using some flavour of SQL
5. **MUST** be secured against anonymous access
6. **MUST** contain tests using a testing framework
7. **SHOULD** track which user makes changes to the data
8. **SHOULD** allow marking Assets “inactive” for when they’re receiving maintenance, and re-activating them later
9. **COULD** have a UI (but don’t worry about UX)
10. **COULD** support searching for Assets by Name, Shopping Centre, or Status

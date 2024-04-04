# Tech Blog ⚾

## Description

You can never have enough tech blogs on the internet. This is because every person has his approach to different problems, and this creates a wide network of different solutions that help future developers to not re-invent the wheel and push forward faster and easier. We want to have a technical blog built with a simple username/password verification where a single user can write technical blogs. The blog format should contain a cover picture, a title, and text. The blog should list the newest blogs first and the oldest, last. This view can change with different filters by month or by tags. People can also leave a star and anonymous comments on every blog post. A key part of this blog is the notifications. You can leave your e-mail and get a notification when a new blog post is published.

## Deliverable Criteria

### Phase 1

- UI
  - Home Page
    - Navigation
    - List all posts starting from the newest one at the top
      - Scrollable list
      - Load more button for loading more posts
  - Navigation
    - Posts ( Home )
    - Newsletter Page
      - Form with a field for a user to leave an email
      - Coming soon message
    - About
      - About the developer section
    - Log In
      - Form for login ( Only Front End )
  - Post
    - Should have a cover image ( Only Front End )
    - Title
    - Text
    - Tags ( every post must have at least 1 tag )
  - Filters
    - By time ( New to old / Old to new )
    - By month ( Only posts from a certain month )
    - By tag ( Only posts with a certain tag )
  - Star and Comment on each post ( Only Front End )
    - A user can leave a star ( 1 star per user )
    - A user can leave an anonymous comment
      - Name ( Optional. If no name is left, then the comment stays under Annonymous )
      - Text
- Data
  - Posts should be added in a JSON file
  - The JSON file should be pinged for the posts to be loaded on the page

### Phase 2

- Back End
  - Log In
    - A popup is shown
    - User can be hardcoded since one user will be using the blog
    - Username and Password is requested
  - Logged in user features
    - When a user is logged in there should be an admin tab visible
    - In the admin panel a user can add a new blogpost
    - Next to the title of every blog post there should be Modify and Delete option
  - Data
    - Data for posts, comments, stars, and the user should work with requests to an API and be saved in a DataBase ( Not in JSON )
    - User should be hardcoded or a single entry in the database

## Stretch Goals

> Stretch Goals are extra goals and challenges that can be picked up during ANY phase

- Newsletter Page
  - Place for a user to leave an email
  - When a new blog post is published, all emails subscribed are notified
- Create a Register and multiple user logins
  - Under every post, it should say which user published that blog ( The logged in user )
- Unsubscribe option from the newsletter
  - A link on the Newsletter page that lands you on an unsubscribe page
  - When an email is left in the unsubscribe field, that email will not be receiving notifications anymore

## Examples

- [Scott Hanselman - Blog](https://www.hanselman.com/blog/)
- [Joel on Software - Blog](https://www.joelonsoftware.com/)
- [Natasha Lomas - Blog](https://techcrunch.com/author/natasha-lomas/)

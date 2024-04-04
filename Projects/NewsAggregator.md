# News Site 📰

## Summary

News is a popular destination for online traffic. A news site can be done by having a team write news, or by aggregating news from different sources. Aggregation can be done by using RSS feeds from known and well-renowned mediums. We want to have a news site that will aggregate news from certain news sources and list it. The site would have ad space, so it can sell ads. There should also be some social interactions such as liking news, commenting, and leaving overall feedback on the site. To make sure that the news is not altered or removed later, we also need this site to create an Archive where news will be saved from previous days.

## Deliverable Criteria

### Phase 1

- UI
  - Home Page
    - Shows the latest news
      - Title + Some of the starting text of the article
    - News can be clicked and the user can read the full article
  - Navigation
    - Latest news ( Home )
    - Feedback ( Only Front End )
      - Form for leaving feedback
    - Archive
      - Old News is shown here
    - Ad space
      - Ads should be hardcoded in this phase
  - News Article
    - Should be saved from the RSS feed
    - Should have a link to the source ( If possible )
    - Should have a comment section ( Only Front End )
    - Should have a trust meter ( Only Front End )
      - Thumbs up and Thumbs down represent user trust
    - When a news article is clicked from a list, it should open on a new page
- Data
  - News should be directly gathered from an RSS feed
  - The comment section and Trust meter should
  - Archive should load news from a JSON that has some news from an older RSS request

### Phase 2

- Back End
  - RSS should be now loaded in the backend and news articles should be saved in the Database
  - Articles, comments, trust meter, and feedback should be working with an API and Database, not JSON
  - RSS Feed sources should be toggleable in a configuration file

## Stretch Goals

> Stretch Goals are extra goals and challenges that can be picked up during ANY phase

- Ads overlay
  - The ads should be kept in the database and have a toggle
  - There should be value for every ad, on how frequently it should show
  - There should be 2 ad slots
    - Banner: Shows up under every news article and is an image
    - Popup: this ad should be special with the larger picture, and should only show the first time the user opens the site in one day
- Ads toggle
  - There should be an admin panel accessed by /admin URL
  - This panel should have an option to add a new ad
  - This panel should load all ads and toggle if they should show or not
  - Frequency of ad showing is set when the ad is created, and can't be changed

## Examples

- [Time.mk](https://time.mk/n/all)
- [Flipboard](https://flipboard.com/)
- [MSN News](https://www.msn.com/en-us/news)

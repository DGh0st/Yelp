# Project 3 - **Yelp**

**Yelp** is a Yelp search app using the [Yelp API](http://www.yelp.com/developers/documentation/v2/search_api).

Time spent: 7 hours spent in total

## User Stories

The following **required** functionality is completed:

- [x] Table rows for search results should be dynamic height according to the content height.
- [x] Custom cells should have the proper Auto Layout constraints.
- [x] Search bar should be in the navigation bar (doesn't have to expand to show location like the real Yelp app does). (does search when search button is clicked, works when 'filter' is tapped and than 'cancel' or 'search' in filters view)

The following **optional** features are implemented:

- [ ] Search results page
   - [ ] Infinite scroll for restaurant results.
   - [ ] Implement map view of restaurant results.
- [ ] Implement the restaurant detail page.

The following **additional** features are implemented:

- [x] List anything else that you can get done to improve the app functionality!
   - [x] A view to filter categories

Please list two areas of the assignment you'd like to **discuss further with your peers** during the next class (examples include better ways to implement something, how to extend your app in certain ways, etc):

1. A better way of implementing the search functionality.
2. How to programmatically get the search button tap on keyboard?

## Video Walkthrough 

Here's a walkthrough of implemented user stories:

<img src='http://imgur.com/uDGPnmT.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while building the app.

I couldn't find the correct method that is triggered for the search bar when 'Search' button is tapped. The app starts with searches of 'Thai' and displays 'Restaurants' once you have been to filters screen. The search functionality does work but it requires you to go to filters screen and click cancel or search.

## License

    Copyright 2016 Deep Patel (DGh0st)

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

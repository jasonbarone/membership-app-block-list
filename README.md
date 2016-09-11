Membership App Block List
=======
> An experiment that proves how unsecure most membership apps are.



## Project Overview
Quite a few business owners, entrepreneurs, designers, developers and site builders have a need for membership-based functionality on their web projects.

As platforms like [Squarespace](http://squarespace.com) grow, companies are developing solutions that try to add membership login and authentication to these platforms. The problem is most of them are merely a JavaScript pop-up added to the website, while the underlying content is public. My issue with this behavior is that users don't fully understand what's going with their content and they **assume** it's securely protected through their Membership app. They're putting all sorts of private information underneath these simple JavaScript overlays. Content like paid products and exclusive material is common, but private documents and usernames/passwords can be found too.

In my opinion, these Membership apps **should not be promoting their usage** given the very nature of them being security apps. In an effort to demonstrate the state of some of these apps simply subscribe to the list below using AdBlock.



## Subscribing to the List
Copy the subscription link, `https://raw.githubusercontent.com/jasonbarone/membership-app-block-list/master/membership-app-block-list.txt`, into your AdBlock browser plugin options. You're done.


### How It Works
The text file in this project contains a curated list of filters for all of the most popular membership and paywall apps out on the web. When you subscribe to the list, the filters are added to your AdBlock settings. As long as the you're subscribed to the list, you'll be blocking the pop-up overlays from appearing, exposing the content underneath.


### Blocked Apps
* Piano(Tinypass)
* SentryLogin
* MyMemberspace
* MembershipWorks


### Finding Content That Was Previously Blocked
There's a few ways to demonstrate how unsecure your content is when using these apps:

#### Piano(Tinypass) Market
Piano(Tinypass) has a curated marketplace of their customers. You can check it out here: [http://market.tinypass.com](http://market.tinypass.com). Click on any of their customer websites and their content will always be freely available by bypassing Piano's paywall.

#### Search Google using the Domain
When many users use these membership apps, they end up putting their content into various pages on their website. To find them, simply search for the domain name in Google. ie: `site:example.com`. This will return a list of all of the pages on that domain. If the user uses one of this project's blocked apps, the content will freely available.

### Disclaimer
This project isn't aimed at promoting content theft by any means. It's promoting the idea of making the web a more secure place, forcing developers to think of better solutions to protect users, and calling out companies that are misrepresenting products.

### Contribute
Submit new apps and filters as [issues](/issues).
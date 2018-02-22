### TODO

MVP:
- [ ] unauthenticated user sees login page
- [ ] user can login via Github/Twitter
- [ ] user is forced to connect Github & Twitter before being able to use app
- [ ] user sees an input that he can use to create a post
- [ ] a post is automatically posted as a tweet with #100DaysOfCode hashtag and RXDXX
- [ ] user sees a character count under post input which correctly according to twitter rules calculates remaining characters available (https://developer.twitter.com/en/docs/basics/tco.html)
- [ ] user sees a timeline of all his posts - every post cotains: post message, date, day number
- [ ] system checks on 30th minute of every hour if users whose timezone crossed 3am of the next day have missed the previous day (3am is to account for night owls) - adds "missed day" post entry to their timeline 
- [ ] user can see missed days on his timeline as visually marked lines with red X
- [ ] user can set his timezone
- [ ] user can logout by clicking on Logout link


More features:
- [ ] user sees a timeline of all his posts with extra: commits of that day (if exist) with hashes and links, optional screenshot, link to tweet
- [ ] user sees a multiple select where he can select projects to associate with today's work
- [ ] user sees a file input which he can use to attach a screenshot of his work
- [ ] commits for that day are automatically downloaded after posting (if connected to a project, see below)
- [ ] user can create a project with attributes: name, associated repository
- [ ] user can select the project repository from list of his repositories - suggestions using github api
- [ ] anyone can view user's public timeline on /{username} route
- [ ] user who has already started 100DaysOfCode challenge can import his existing progress from twitter - the import script will download all his tweets with #100DaysOfCode hashtag and search for RXDXX pattern - then it will present all tweets that appear to be day logs and let user unselect wrong ones
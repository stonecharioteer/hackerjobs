# Hackernews Who Wants to Be Hired Scraper

Every month, [HN](https://site.ycombinator.com) has 3 threads that are of
importance to companies looking to hire people, and to people looking for jobs:

1. Who's Hiring?
2. Who Wants to Be Hired?
3. Freelancer/Looking for Freelancer?

The main thread of importance to a company hiring people is the `Who's Hiring` thread,
which is what we are targetting in V1 of this application.

The objective is to build a CLI that scrapes the _latest_ Who's Hiring page, Parses results,
and writes new results to a Google Spreadsheet. It should include the following columns:

1. Year x Month of the thread
2. Link to thread
3. Reply User
4. Reply Content
5. Link to Reply
6. Link to User Profile
7. Timestamp of Data Collection

The system should keep appending to this table, but it should not post
duplicate content from the same thread.


---
layout: post
title:  "Ruby CLI Gem Project"
date:   2016-10-18 13:08:14 +0000
---


My ruby CLI Gem project displays five jersey prices and information from the Boston Celtics team store. With this being my first project I wasn't sure how to begin, but after watching the CLI gem walkthrough with Avi on https://www.youtube.com/watch?v=lDExWIhYKI I felt more comfortable completing this project.

After doing a quick google search for creating my own ruby gem I came across http://robdodson.me/how-to-write-a-command-line-ruby-gem/which which helped me begin my project. Once I had all of the files loaded I began coding the CLI gem's interface. Using Avi's YouTube walkthrough as a guide, I was able to go from having an interface where everything was hard coded to having dynamic content display based on each jersey.

The toughest part of the project for me was getting all of the jerseys and thri prices to be displayed in a list format. In my deal.rb file I have fice different self.scrape methods for each jersey. At first I tried to create two self.scrape methods which would return information about the jersey and the other self.scrape method would return the price. I was hoping to get this information listed together, but instead the output showed all of the jerseys then the prices there after as on list item. So instead of the output being:
1. player 1 -price
2. player 2 - price
3. player 3 - price
4. player 4 - price
5. player 5 - price

I got 1. player 1, player 2, player 3, player 4, player 5 - price 1, price 2, price 3, price 4, price 5.  I have done extensive research trying to resolve this problem and then I came up with creating a new self.scrape method for each jersey.

Overall, this was a fun project where I was able use my existing ruby skills as well as learn new ones and put them to use into a real project.

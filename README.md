# TraderBot - *Stock Trade Advising App*

**TraderBot** is an android app that advises short-term stock sellers on what stocks they should sell, buy, or hold. TraderBot is created with Java, Python, Firebase, and Chaquopy. Users can add companies to their watchlist and visualize the stock price fluctuation of such stocks.

* Task: design, implement, and test a complete stock trading recommendation system to analyze the performance of various stocks in the stock market and assist users in determining when and which stocks they should buy/sell from their watch list.
* Users: stock market traders
* Development Model: Waterfall

## User Stories

The following functionality is completed:

- [X] Registration and Login functionality
  - [X] User can **add companies to their watchlist** at any time after account creation or login
  - [X] User can **view stock price fluctuation in a graph** of a particular company's stock at any time after account creation or login
- [X] Sell & Buy Suggestion functionality
  - [X] User can **view system-generated reccommendations** of when the user should sell, buy, or hold a particular stock
- [ ] Performance Summary functionality 
  - [ ] User can **view a summary** of how accurate (profitable) previous system-generated reccommendations are
- [ ] News functionality
  - [ ] User can **view a newsfeed** on previously viewed system-generated reccommendations
- [ ] History functionality
  - [ ] User can **view a log** of the user's previous in-app activities (e.g. added a company to watchlist, login,change password)

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://github.com/Angelica-M/Stock_Trade_Advising_App/tree/master/TB_ImageDemos/TB_Graph.png' title='Graph' width=''/>
<img src='https://github.com/Angelica-M/Stock_Trade_Advising_App/tree/master/TB_ImageDemos/TB_Graph.png' width=250/>
<img src='https://github.com/Angelica-M/Stock_Trade_Advising_App/tree/master/TB_ImageDemos/TB_HomePage.png' width=250/>
<img src='https://github.com/Angelica-M/Stock_Trade_Advising_App/tree/master/TB_ImageDemos/TB_Login.png' width=250/>
<img src='https://github.com/Angelica-M/Stock_Trade_Advising_App/tree/master/TB_ImageDemos/TB_Navigation.png' width=250/>
<img src='https://github.com/Angelica-M/Stock_Trade_Advising_App/tree/master/TB_ImageDemos/TB_Search.png' width=250/>
<img src='https://github.com/Angelica-M/Stock_Trade_Advising_App/tree/master/TB_ImageDemos/TB_Watchlist.png' width=250/>

## Notes

1. Press “My Application” in your android menu after installing the application. If you already have an account, enter your account details and press “Login”. Otherwise, press “Register” to sign up for an account. You will be taken to the Home page, which is basically a display page for your account info such as your name, username, and email. In the top left corner of your screen, you will see a pull-out menu, which is basically a navigation page for your account. Press “Logout” to sign out and exit the app.
2. Press “Search” to find companies that you can add to your watchlist, there’s a few recommended companies listed below the search engine. If you click and hold for a few seconds on a company’s name, a pop-up message should appear saying “Add as favorite: Are you sure you want to add this stock to your watchlist?” with option YES or NO. If you click “yes”, the company will be added to your watchlist.
3. Press “My Watchlist” to see the stats of the companies’ stock details that are on your watchlist. With information of the current price, the highest price of the day, the lowest price of the day, closing price for the stock and the volume of it.
4. Press “Notification” to look at the messages on that were sent from the app notifying you when it was a good time to sell/buy stock from the companies you are watching. Press “Logout” to logout of the app and return to the “login” screen.

## Knowledge & Skills Gained

- Software development practices
  - Functional analysis
  - Software testing
- Python and Android development
- Time management skills 
- Teamwork and collaboration skills 
- Identifying and resolving problems

## License

  Copyright [2021] [Angelica Magnussen, Akshar Patel, Anjal Parikh, Will Chen, Isabel Metevier]

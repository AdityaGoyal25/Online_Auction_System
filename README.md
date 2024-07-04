# Online Auction System
#Overview
Any auction is a long and sensitive procedure in which a lot of information has to be taken care of, ranging from details about the bidders to their bids and so on. The aim of this project is to provide a user-friendly website wherein users can buy and sell products via an auction system in a hassle-free manner.

Our website provides a straightforward and simple procedure to carry out auction bids and even sell products via auction. With features like adding products, bidding for products, and more, our website resembles an actual auction.

We have incorporated a database in our project which contains all the necessary tables and information, allowing for the smooth functioning of our website. Due to the database, we can include features like a login system, bidding, allotting products to the highest bidder, and many more as we will see later on in this report.

Features
User Registration and Login
Allows users to register/login into our website. This functionality helps our website to identify the current user at any point, facilitating a user-friendly interface through quick record retrieval and improving the overall flow of the website.

Fields:
Name
Age
Email
Password
This information is added to the user table.
Adding Products for Bidding
Allows users to add their own products for bidding by filling up a user-friendly form:

Fields:
Name
Description
Total duration during which bidding can take place
Image
This information is added to the items table along with the time at which it is posted to keep track of the time remaining for bidding.
Submitting Bids for Products
Users can choose a product and submit a bid for it if their bid is higher than the last bid. This functionality allows for the smooth functioning of our auction website, closely resembling a real-life auction.

Fields:
Bid amount
The information is added to the bid details table, which takes the login info as other arguments.
Viewing Your Bids and Allotted Products
Users can easily view their bids and products allotted to them through the bid details table and user login info. This process is quick and easy.

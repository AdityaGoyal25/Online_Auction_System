# Online Auction System

Any auction is a long and sensitive procedure in which a lot of information has to be taken care of, ranging from details about the bidders to their bids and so on. The aim of this project is to provide a user-friendly website wherein users can buy and sell products via an auction system in a hassle-free manner.

Our website provides a straightforward and simple procedure to carry out auction bids and even sell products via auction. With features like adding products, bidding for products, and more, our website resembles an actual auction.

We have incorporated a database in our project which contains all the necessary tables and information, allowing for the smooth functioning of our website. Due to the database, we can include features like a login system, bidding, allotting products to the highest bidder, and many more as we will see later on in this report.


## Features

- USER REGISTRATION AND LOGIN\
Allows for users to register/login into our website. These allows our websites to know the current user at any point on the website. This facilitates user-friendly interface using quick record retrieval. The overall flow of website is improved.\
•	Name\
•	Age\
•	Email\
•	Password\
This info is added to the user table

- ADDING PRODUCTS FOR BIDDING\
Allows users to add their own products through bidding by filling up an user-friendly form:\
•	Name\
•	Description\
•	Total duration during which bidding can take place\
•	Image\
This info is added to the items table along with the time at which it is posted to keep track of time remaining for bidding.

- SUBMITTING BIDS FOR PRODUCTS\
User can choose a product and submit a bid for it if his/her bid happens to be higher than the last bid. This allows for smooth functioning for our auction website, closely resembling a real life auction -> only bid amount asked. The info is added to bid details table which takes the login info as other arguments.

- SEEING YOUR BIDS AND ALLOTED PRODUCTS\
User can easily view their bids and products allotted to them through the bid details table and user login info. This process is quick and easy.


------ Things to consider

1. The db.php file controls the database connection across all the PHP files (so that migrating is as simple as changing a single line).
2. The whole design is responsive, across all the pages (including history, comment, etc). This is acheived using a combination of flex boxing, and media queries.
3. I've used different heading levels for different depths of the document, to preserve the outline structure of the whole site. If this is not what's required, changing that is simply a matter of changing h1 to h2 or vice versa, and just adding that in the style.css
4. The website also has designed error pages, so that there's consistency across the user experience while browsing the website.
5. Main colours used were decided after thorough delibration, and are - rgb(254, 229, 14), #282828, #f71111, #f7f7f7, and #282828.


------ Completed Parts (All the ones mentioned below are completed)

---- (All of them, but still if needed)


Part I (4 points)
✔ Correctness of “index.html” (2 points)
✔ Correctness of “createaccount.html” (2 points)

Part II (12 points)
✔ Correct functionality of verifying user’s login into the system (verifyLogin.php) (1 point)
✔ Correct functionality of users’ account creation (create.php) (1 point)
✔ Correct functionality of the main page (main.php) (0.5 points)
✔ Correct functionality of the welcome page in “Buy A Ticket” (buywelcome.php) (1 point)
✔ Correct functionality of the seat selection page in “Buy A Ticket” (seatplantry.php) (2.5 points)
✔ Correct functionality of buying a ticket page in “Buy A Ticket” (buyticket.php) (1 point)
✔ Correct functionality of the confirm page in “Buy A Ticket” (confirm.php) (1 point)
✔ Correct functionality of the comment page in “Movie Review” (comment.php) (2 points)
✔ Correct functionality of retrieving the comment in “comment_retrieve.php” (0.5 points)
✔ Correct functionality of submitting the comment in “comment_submit.php”(0.5 points)
✔ Correct functionality of retrieving user’s purchase history in “history.php” (0.5 points)
✔ Correct functionality of logout in “logout.php” (0.5 points)

Part III (12 points) 
✔ Use of CSS in the design of index.html, createaccount.html and main.php (1 point)
✔ Use of CSS in the design of comment.php (1 point)
✔ Use of CSS in the design of history.php (1 point)
✔ Correct implementation of responsive web features and use of CSS in the design of buywelcome.php (3 points)
✔ Correct implementation of responsive web features and use of CSS in the design of seatplantry.php (4 points)
✔ Correct implementation of responsive web features and use of CSS in the design of buyticket.php (1 point)
✔ Correct implementation of responsive web features and use of CSS in the design of confirm.php (1 point)


------ Future Updates (for fun)
1. Hashing password. Storing unsalted, unhashed passwords should be a crime.
2. Adding a payment gateway.
3. Handling simuntaneous transactions (so a way to put a seat on a sort of hold for the duration of buying).
4. Adding email verification.
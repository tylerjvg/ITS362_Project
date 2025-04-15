# ITS362_Project

Login or registration -> home page (links to categories, example reviews(highest/lowest reviews video) -> categories page -> specific category (3-5 videos, hidden in dropdown)
	|												  about page 
	|												  randomized page (random video to review)
	|												  statistic page (total site average, category average)
	|
if admin -> shows all reviews, allows for deletion, -> account management page
sql - table for each category, video id (pk) for category, totals table - for statistics page - video id (fk)
sql injection - login page, select all query


schema - users (user id (pk), username, email, fname, lname, password (enc))
	 admin (admin id (pk), username, email, fname, lname, password (enc))
  	 review (review id (pk), user id (fk), rating, comments)
    	 video (video id (pk), user id (fk), url)
      	 

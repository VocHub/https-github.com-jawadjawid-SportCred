# Goals
Complete user stories for this sprint so that we have an application that allows users to make picks and predictions, make posts in the open court and interact with other user's posts, change their password and be able to log out of the application.

# Stories
IL-3: As Amanda, I want a navigation bar, so that I can access application’s other pages from there  
Acceptance test : I can see a page with buttons to all other pages of the app  
Priority/Point estimate: High/3   

IL-5: As Harry, I want to be able to make picks and predictions, so that it can show me credibility by the accuracy of my picks and predictions.  
Acceptance test : I can go on the picks and predictions page, and I'm able to choose my picks and predictions  
Priority/Point estimate: High/3  

IL-7: As Amanda, I want an “open” page, so that I can see other people’s post,   
  * As Amanda I want to be able to comment, and agree/disagree with them so that I can make my opinion known  
    * Acceptance test : I can enter and submit a comment and also click buttons to dis/agree and see a counter change  
    * Priority/Point estimate:  Medium-High/3  
  * As Amanda I want to be able to post on the “open court” so that I can make my opinion known  
    * Acceptance test : I can enter a post, submit it and see it on open court with its comments and dis/agreement counter  
    * Priority/Point estimate:  Medium-Medium/3  
  * As Amanda, I want to be able to share a SportsCred post so I can inform my followers on other social media  
    * Acceptance test : Once I share to a social media, I am able to see the post on those apps independently  
    * Priority/Point estimate:  Medium-Low/3  

IL-10: As George, I want to change my current password to a new one, so that I can ensure the safety of my account by changing passwords regularly.  
Acceptance test : I should only be able to log in with the new password I create  
Priority/Point estimate:  Low/1

# Participants
Muhammad Osman Amjad  
Maninder Dhanauta  
Jimmy Yu  
Kshitij Dahal  
Piyush Ukani  
Vineet Desai  
Mahamad Jawad Jawid  

# Team Capacity
10 points in total

# Task Breakdown
As Amanda, I want a navigation bar, so that I can access application’s other pages from there  
Acceptance test : I can see a page with buttons to all other pages of the app  
Priority/Point estimate: High/3 
  * This main page of the application includes a navigation bar to other pages of the application "Picks and Predictions", "Trivia", "Debate and Analysis"	
  * Setup Basic Routes to pages to work off of	

As Harry, I want to be able to make picks and predictions, so that it can show me credibility by the accuracy of my picks and predictions.  
Acceptance test : I can go on the picks and predictions page, and I'm able to choose my picks and predictions  
Priority/Point estimate: High/3 
  * Create picks and predictions page		
  * Show list of the next upcoming games	
  * Allow picks to be made for selected game		
  * Make ACS score and history report reflect on the the picks and predictions made on games that already happened	
  * Return list of upcoming games	
  * Keep track of users picks and predictions
  * Create notification displayed to user if ACS score changes
  * Create notification displayed to user if ACS score changes on page		

As Amanda, I want an “open” page, so that I can see other people’s post,   
  * user can create posts	
  * user can see posts that are coming in
  * send user post to DB	
  * retrieve posts from DB	
  * update post in DB	

As George, I want to change my current password to a new one, so that I can ensure the safety of my account by changing passwords regularly.  
Acceptance test : I should only be able to log in with the new password I create  
Priority/Point estimate:  Low/1
  * allow user to change password in profile page	
  * return user password from DB	

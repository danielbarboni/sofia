# Planning our application
	
	1. Answer Questions
		- What are we building?
		- Who are we building it for?
		- What features do we need to have?
	2. User Stories
	3. Model our Data
	4. Think through the pages we need in our app

## Questions

	1. What are we building? We are building a personal site for my daughter. A place where we can blog, share examples of our work as a father and mother for the first time, as have people contact us.
	2. Who are we building it for? We are building it for ourselves, our relatives and friends but also the community. Sharing what we are learning by blogging is a great way to document the steps in this wonderful family journey, as well we inspire others in the process. Also, it will eternize great memories for our loved Sofia.
	3. What features do we want to have?
		- Posts
			- Create / Edit / Destroy
			- Markdown
			- Syntax highlighting
			- Comments (Discus)
		- Projects
			- Create / Edit / Destroy
		- Contact
			- Contact form
			- Send grid
		- User (Devise)		

## User Stories
	
	As a blank, I want to be able to blank, so that blank.
	
		- As a user, I want to be abe to create posts so that I can share what I am learning and our experiences creating Sofia on my blog.
		- As a user, I want to be able to edit & destroy posts, so that I can manage my blog.
		- As a users I want to be able to write posts in markdown format so that it’s easy for me to write posts.
		- As a user, I want to be able to highlight the various syntax of code blocks that I share on my blog.
		- As a user, I want to show the visitors examples of our work, or stuff we've built.
		- As a user, I want to be able to have visitors contact me through a form on my site.
		- As a user, I want visitors to be able to leave comments on my posts.
		
## Modeling our Data

	Post title:string content:string
	
	Project title:string description:text link:string
	
	User
	
## Think through the pages we need in our app

	- Home
	- Posts#index
	- Posts#show
	- Projects#index
	- Projects#show
	- Contact
	
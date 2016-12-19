
#Plan for the blog site

1)Questions.
:  - 1.What are we building?
:  - 2.Who are we building it for? 
:  - 3.What features do we need to have?

**2)User stories. **
**3)Models for our data.**
**4)Think through the pages of our app.**


###Questions 
- What are we building? We are building a blog site.
- Who are we building it for? We are building it for ourselves.
- What features do we need to have?
 - Posts 
   1) Create / edit / delete 
   2) Comments
   3) Markdown and syntax highlighting for code blocks   
 - Users
	 1) Sign in/out
 - Contact form
 
###User stories
-  As a 'blank' , I want to be able to 'blank' , So that 'blank' .
- As a user I want to be able to create posts. So that I can share the work I do. 
- As a user I want to be able to edit/delete the posts I created. So that I can manage my posts
- As a user I want to be able to add comments for the posts. So that I can clarify blurred things.
- As a user I want the visitors to be able to contact me.  

###Models for our data.
- **Post**
   - id : int 
   - title : string
   - content : text
   - date : datetime
- **Comment**
	- id : int
   - content : text
   - date : datetime 
- **User**
  - id : int
  - username : string
  - password : string 

###Think through the pages of our app.
- Home
- Posts
- Post detail
- Create/edit/ posts
- Contact 
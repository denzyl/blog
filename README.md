1. Answer Questions
   - What are we building?
   - Who are we building it for?
   - What featured do we need to have?

2. User Stories

3. Model our Data

4. Think through the pages we need in our app

===============================

1. What are we building? A personal site. Share examples of our work and have people contact us.

2. Who are we building it for? Myself and the community as a whole. Sharing what we're learning by blogging is a great way to learn for ourselves, but we teach others in the process. Show potential employers that we know what we're talking about.

3. What features do we want to have?
    - Posts
      - Create / Edit / Destroy
      - Markdown
      - Syntax highlighting
      - Comments (Disqus)
    - Projects
      - Create / Edit / Destroy
    - Contact
      - Contact form
      - Sendgrid
    - User (Devise)

## User Stories
  As a ____, I want to be able to _____, so that ____.

1. As a user, I want to be able to create posts so that I can share what I am learning on my blog.

2. As a user, I want to be able to edit & destroy posts so that I can manage my blog.

3. As a user, I want to be able to write posts in markdown format so that it's easy for me to write posts.

4. As a user, I want to be able to highlight the various syntax of code blocks that I share on my blog.

5. As a user, I want to show the visitors and potential employers examples of my work, and stuff I've built.

6. As a user, I want to be able to have visitors contact me through a form on my site.

7. As a user, I want visitors to be able to leave comments on my posts.

## Modeling our Data

**Post**
  title:string
  content:text

**Project**
  title:string
  description:text
  link:string

**User**
  Devise takes care of this for us.

## Think through the pages we need in our app

  - Home
  - Posts#index
  - Posts#show
  - Projects#index
  - Projects#show
  - Contact
  -



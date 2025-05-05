# Simulated Blog Platform (MongoDB)
## Project Overview
This project demonstrates a MongoDB database structure designed for a blog platform. The database stores information about blog authors, their posts, and comments on those posts. It showcases MongoDB's document-oriented structure and various query capabilities.

## Database Structure
Collection: blogTEST
Each document in the collection represents a blog author with the following structure:
* _id: Unique identifier for the author
* author_name: Full name of the author
* username: Username for the author's account
* twitter_acc: Author's Twitter handle
* address: Author's physical address
* phone_numbers: Array of author's phone numbers
* blog_posts: Array of blog post documents
  
## Blog Post Structure
Each blog post is a nested document with:
* title: Title of the blog post
* date: Publication date
* body: Main content of the blog post
* related_tags: Array of tags/categories
* comments: Array of comment documents

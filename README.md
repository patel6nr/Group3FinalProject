# Group 3 FinalProject
By Nirav Patel, Ossebi Guy-Lero, Le Duc Toan.

## Introduction
Our project aims to develop a web application called "Blogger's Hub" that provides a platform for bloggers to create, publish, and share their content with readers. The application will offer a user-friendly interface for both writers and readers, fostering a community where bloggers can engage with their audience and grow their following. 

## Story Board

## Requirements
 
**1. Creating and Publishing Blog Posts**: As a User, I want to create and publish blog posts so that I can share my thoughts and ideas with others.
   
**Given**: The user is logged in to the Blogger's Hub platform.

**When**: The user navigates to the "Create New Post" page and fills out the required fields.

**Then**: The user's blog post is published and made visible to readers. 

**2. Categorizing Blog Posts**: As a User, I want to categorize my blog posts so that I can organize my content effectively. 

**Given**: The user is creating a new blog post.

**When**: The user selects one or more categories for the post. 

**Then**: The post is tagged with the selected categories. 

**3. Interacting with Other Bloggers and Readers**: As a User, I want to interact with other bloggers and readers so that I can build a 	community around my blog. 

**Given**: The user is viewing a blog post. 

**When**: The user leaves a comment on the post.

**Then**: The comment is displayed on the post and other users can respond to it. 

## Class Diagram
### Class Diagram Description 

## JSON Schema
This is what we plan to export to another app.

>{ 
>  "type": "object", 
>  "properties": { 
>    "postId": { "type": "integer" }, 
>    "title": { "type": "string" }, 
>    "content": { "type": "string" }, 
>    "author": { "type": "string" }, 
>    "categories": { 
>      "type": "array", 
>      "items": { "type": "string" } 
>    },
>
>    "comments": { 
>      "type": "array", 
>      "items": { 
>       "type": "object",
>        "properties": { 
>         "commentId": { "type": "integer" }, 
>         "content": { "type": "string" }, 
>         "author": { "type": "string" } 
>    } 


## Team Members and Roles
UI Specialist:

Business Logic/ Persistence:

DevOps/Product Owner/Scrum Master/GitHub Admin: 







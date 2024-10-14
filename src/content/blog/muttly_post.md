---
title: "Muttly Project Overview"
description: "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
pubDate: "Oct 10 2024"
heroImage: "/muttly_hero.webp"
tags: ["project"]
---
<div class="video-container">
  <iframe width="450" height="315" src="https://www.youtube.com/watch?v=PgBKb6M4rzE" frameborder="0" allow="encrypted-media" allowfullscreen></iframe>
</div>


<a href="https://muttly.onrender.com/" class="btn btn-outline btn-primary ml" target="_blank">Live Site</a> <a href="https://github.com/BSMuse/Muttly" class="btn btn-outline btn-primary ml" target="_blank">Git Hub</a>

Muttly is a creative web application that lets users combine two dog breeds to generate custom "Mutt" breeds. Leveraging the power of AI models from OpenAI and Leonardo AI, Muttly allows users to create unique stats cards for their custom dogs, save, share, and favorite them. The project was born out of a desire to explore the intersection of machine learning and creativity. This app was built in collaboration with Greg De Chant and Charlie Denahy-Knowles and was the final project for our Web Dev Bootcamp with Lighthouse Labs. 

---

## Motivation

### Why I Built Muttly:
As a fan of both dogs and cutting-edge technology, I wanted to merge the two worlds. The idea of generating custom dog breeds using AI intrigued me, and I wanted to give users a fun, interactive way to explore it. Muttly was also an opportunity to work with APIs like OpenAI and Leonardo AI while developing my skills in React and Node.js.

---

## Technical Implementation

### Tech Stack:
- **Frontend:** React, SCSS
- **Backend:** Node.js, Express
- **Database:** PostgreSQL, Neon
- **APIs:** OpenAI, Leonardo AI
- **Hosting:** Render

### Key Features:
- **Custom Mutt Generator:**
  Using OpenAI and Leonardo AI models, users can combine two dog breeds and generate a custom hybrid dog breed.
  
- **Save and Share:**
  Once users create their "Mutt," they can save the stats card, share it with others, and even favorite other people's creations.

- **AI Model Integration:**
  Integrating OpenAI's Assistant API was challenging, especially in terms of handling large requests and ensuring smooth generation of images. I learned how to handle API rate limits and optimize image generation times. Leonardo's prompting and settings was also a challenge to get the results we wanted. It took a bit of fine tuning to stop having two headed dogs generate, for instance. 

- **Database Handling:**
  PostgreSQL was used to manage users' saved cards, providing a smooth experience for fetching, saving, and updating user data. Neon (was ElephantSQL R.I.P.) hosts the database and handles the requests. 

---

## Project Management 
The team was given two weeks to develop an idea to a fully functional fullstack application. My team mates were receptive to the idea, as we broke down and explored how we could bring the unique app into reality. 

We performed long sprints going over API options and design. Thankfully, I've had experience with Leonardo from working with another application Given the complexity of integrating two APIs and building a full-stack application, we created a detailed timeline and broke the project into sprints, assining pages and tasks using Trello to manage our backlog.   

We completed the project on time and had a splendid presentation. After the others walked away from the project after the bootcamp, I further enhanced the UI, updated the database, and created responsive and new layouts for Mobile platforms. 

---

## Results and Impact

### Final Product:
Muttly is fully functional and available to the public. Users can generate their custom Mutts, save and share them, and interact with others' creations. Check out the demo below!

**[Live Demo](https://muttly.onrender.com/)** | **[GitHub Repo](https://github.com/BSMuse/Muttly)**

### Lessons Learned:
I deepened my understanding of API integration, particularly with AI models. I also learned the importance of handling backend performance to ensure a smooth user experience, especially when dealing with large datasets and external APIs.

---

## Future Improvements

### Potential Enhancements:
- **Improved AI Integration:**
  I'd like to explore using other AI models to generate more detailed dog images and stats. Alos, creating conditonal prompts comes to mind in regards to creating a gatcha or trading card kind of thmatic would be pretty cool. Generating a "shiny" Mutt or one with a unique background would enhance the novelty of the application.
  
- **User Authentication:**
  Implementing google auth so signing in isn't a chore would be ideal. 

---

## Call to Action

Love dogs and tech? Try out **Muttly** today and create your own custom dog breed! I welcome any feedback and would love to hear about the creations you come up with.

**[Try Muttly](https://muttly.onrender.com/)**

---

## Conclusion

Building Muttly has been a fantastic journey into AI integration, full-stack development, and creativity. I am proud of what this project represents and how it showcases both my technical and problem-solving skills. As I continue to work on Muttly, I look forward to evolving the platform and learning even more along the way.



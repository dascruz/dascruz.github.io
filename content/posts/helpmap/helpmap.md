---
title: "T3chFest 2023 Hackathon"
date: 2023-02-26T12:00:00+01:00
draft: false
---

Yesterday I went to my first hackathon! The theme was **technology in vulnerable situations and zones** and we could build anything we wanted. At first, I was somewhat overwhelmed as I was thinking about cool ideas along with my other two teammates. We only had 10 hours to build a functional prototype and time was running.

After getting our brains powered with sugar from the breakfast the organization gave us, we got an idea: **a map of war-affected areas that could help civilians locate important events and resources**. Now we had something to work with, and the fun part began... let's get coding!

We first needed to code the actual map, and thankfully a really good open-source library exists for building interactive and mobile-friendly maps: **Leaflet**. After an hour or so we had set up the frontend part of our application, meanwhile I got working on the backend and database part of the apps. Teamwork is amazing!

To build the database I used **MongoDB** as I have some experience working with non-relational databases, and MongoDB provides free clusters so the setup is minimal. For the backend, I used **NestJS**, a modern framework built on top of Express and Node.js that is really fast to set up and work with. After a couple of hours we already had a basic REST API for storing the events and resources that would show on the map.

A good coordination between the three of us made possible to seamlessly connect the frontend to the backend, and add some example data using **Postman** to send GET requests to the backend. Our idea was to add the option for verified civilians to add events themselves for other civilians, but time was almost up and it stayed as a possible functionality for the future.

There were really good projects at the demo showcases, such as a marketplace in developing countries or a learning platform for African kids. **We obtained the second place!** I was really happy about our final app and I can't wait to go to more events like this!

If you want to check out the code for our app, I uploaded it to my GitHub [here](https://github.com/dascruz/helpmap).

![HelpMap](../readme.png "HelpMap")

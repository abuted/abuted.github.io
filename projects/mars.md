---
layout: project
type: project
image: img/mars_logo.png
title: "MARS"
date: 2021-10-23
published: true
labels:
  - Python
  - HTML
  - CSS
  - GitHub
summary: "MARS is a program that allows users to help marine wildlife in distress."
---

<img class="img-fluid" src="../img/mars_bg.png">

For sightings, users fill out a form with information on the animal, its environment, and photos. Allows you to report sightings of marine wildlife in distress, sends your location to HMAR, and allows you to send images and information to help the animal.

For emergencies, users are provided with contact information to HMAR. In both options, HMAR is notified with the information needed to best support the animal reported. Allows HMAR volunteer to look through submissions via spreadsheet and provides them with information on animal (i.e. location, injury) to best help the animal.

## What is MARS?

MARS (Marine Animal Response System) is a comprehensive program designed to engage the public in the protection of marine wildlife in distress. Users can report sightings of marine animals by filling out a form that captures key details such as the animal’s condition, its environment, and any relevant photographs. This information helps ensure that the animal receives appropriate attention. For emergencies, MARS offers direct contact information for HMAR (Hawaiian Marine Animal Response), enabling rapid response. Whether it's a sighting or an emergency, the platform ensures that HMAR is notified with all necessary details to take quick and effective action. The program empowers individuals to contribute to marine conservation efforts by making it easy to report and respond to wildlife in need. By providing clear instructions and a user-friendly interface, MARS facilitates the flow of critical information from the public to experts. This collaborative approach enhances the chances of successful intervention and the long-term protection of marine ecosystems.

## What was my role?

We used many things when building our program, including HTML, Bootstrap, CSS, and JavaScript for the frontend, and Django Framework with Python for the backend. I was part of the backend with a few of my teammates. We integrated MongoDB as our database solution. Our primary task involved organizing and processing data, which we initially managed by structuring it within a CSV file and uploading it into PyCharm for further manipulation. After sorting and reformatting the data, we ensured it was compatible for upload into MongoDB. We developed a custom script that extracted specific data from the spreadsheet and used a function to convert this data into Unix timestamps. Upon completion of the data transformation, we uploaded each record, along with its corresponding Unix timestamp, into MongoDB. Additionally, we used GridFS to efficiently manage and retrieve photos, allowing uploads and retrieval of images directly from MongoDB.

## What did I learn?

This project was my first experience working with Django Framework and MongoDB with python, so I learned how to format and write functional code. Throughout the process, I also learned to seek out valuable resources and information that aided in our development. On the backend, we became familiar with MongoDB, learning how to store, manipulate, and manage data. We formatted spreadsheet data, uploaded it into the database, and used it for data conversion and testing sorting functions. We explored how to insert and delete data in MongoDB and managed images using a combination of GridFS and the Pillow library, which allowed us to upload, retrieve, and display images efficiently. Along the way, we encountered typos and errors within the dataset that interfered with our scripts, so I also learned how to handle faulty data by incorporating try and except statements into our code.

  
Source: <a href="https://github.com/HACC2021/MARS.git"><i class="large github icon "></i>abuted/hacc2021program</a>

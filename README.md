# Mission-to-Mars

Web-scraping with HTML and CSS

## **Project Overview**
In this project I am performing web scraping from active Nasa’s websites in order to retrieve information about Nasa’s latest article, featured picture, Mars facts and images of Mars Hemispheres. All retrieved data are put together in a single web application to showcase the gathered information.

**For this project I am using:**

- Chrome Developer Tool to identify HTML and CSS components.
- Beautiful Soup (extracts data) and Splinter (automates web browsers) to automate the scrape jupyter notebook.
- Python to write the script scraping.py.
- MongoDB, a NoSQL database to store data. MongoDB can handle the data that isn’t structured, data without relationships to other data. Instead Mongo uses a document model which means that data is stored in JSON data structures.
- Flask to render the data and create a web application app.py.
- HTML, CSS and Bootstrap 3 to customize web application index.html.

## **Scraping Mars Data**
Selecting the "Scrape New Data" button will obtain the latest news, images, and facts about Mars. News titles and summaries are extracted from NASA Mars Exploration Program News. The featured images are extracted from the Jet Propulsion Laboratory's Space Images. Mars hemisphere images are extracted from Astropedia. Finally, the Mars facts are gathered from Galaxy Facts. The scraping code used in this project is scraping.py.

After running app.py, the extracted data is successfully stored in MongoDB. A mars_app database must exist in mongo for the code to properly run.

## **Updating the Web App**

Adding Bootstrap 3 components, such as the code below, allowed the four Mars hemisphere images to be displayed side-by-side on Desktop browsers, instead of a line. This allows users to see all four images at once.

"<div class="col-md-3>" 
  
![image](https://user-images.githubusercontent.com/99419112/167024510-1293a4d6-839b-4713-b60a-7feea5aabbfb.png)

  ## **Optimization for Mobile Devices**
The Web App is also fully optimized for mobile devices, including the layout of the hemisphere images.
  
  ![image](https://user-images.githubusercontent.com/99419112/167024301-4488a5a4-8912-42f7-a7ae-ac60b5b8b36b.png)

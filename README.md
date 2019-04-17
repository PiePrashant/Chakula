# A restaurant recommendation system based on item-item collaborative filtering. 
# Libraries - Numpy, Pandas, Matplotlib, sklearn
It's a part of back-end of a web application which recommends restaurants to user based on his pased experiance. It learns from the user data which he provides to app, which gets updated in the database of project. 
Data(Restaurant Vector) is scraped from a website for a particular city using BeautifulSoup Library of Python.
User-Restaurant data was generated using random value generator of numpy.
In this modal K-nearest-neighbor(cosine simillarity) was used.  
Basic idea - Predict the rating of restaurant for user which he hasn't visited. 

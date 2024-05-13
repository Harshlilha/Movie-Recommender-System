# Movie-Recommender-System
This GitHub project implements a movie recommender system using ML and vectorization with Streamlit. It analyzes taglines, transforms them into vectors, and recommends similar movies. With a user-friendly interface, users can input taglines or titles to receive personalized suggestions. 

# How to run the project?
1.Clone or download this repository to your local machine.

2.Install all the libraries mentioned in the requirements.txt file with the command pip install -r requirements.txt

3.Get your API key from https://www.themoviedb.org/. (Refer the above section on how to get the API key)

4.Replace YOUR_API_KEY in both the places (line no. 15 and 29) of static/recommend.js file and hit save.

5.Open your terminal/command prompt from your project directory and run the file main.py by executing the command python main.py.

6.Go to your browser and type http://127.0.0.1:5000/ in the address bar.

# How to get the API key?
Create an account in https://www.themoviedb.org/, click on the API link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your API sidebar once your request is approved.

# Working of Cosine Similarity(instead of Euclidean distances)
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.

# Sources of the datasets
IMDB 5000 Movie Dataset

The Movies Dataset

List of movies in 2018

List of movies in 2019

List of movies in 2020

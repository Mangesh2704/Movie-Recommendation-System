# Movie Recommendation System

![Movie Recommendation System](final.png)

## Problem Definition

In the current landscape of digital media, users face challenges in discovering movies that match their personal preferences amidst a vast array of options. Existing recommendation systems often fail to provide accurate and personalized suggestions, leading to user frustration and decision fatigue. There is a need for an advanced movie recommendation system that utilizes cutting-edge algorithms to analyze user behavior and movie metadata effectively, providing highly personalized suggestions in real-time. This system should adapt dynamically to user feedback to ensure continuous relevance and engagement, revolutionizing the movie-watching experience and enhancing user satisfaction.

## Scope and Importance of Project

### Scope:

This project focuses on developing a content-based movie recommender system utilizing cosine similarity. It involves gathering movie metadata such as genre, cast, and plot synopsis, and implementing cosine similarity algorithms to compute similarity scores between movies based on their features. The system will then recommend movies to users based on their preferences and similarities to movies they have enjoyed. Key components include data collection, feature extraction, cosine similarity computation, and recommendation generation.

### Importance:

The project holds significance in enhancing the movie-watching experience for users by providing personalized recommendations tailored to their individual preferences. By utilizing cosine similarity, the system can effectively identify similarities between movies based on content features, thus offering relevant and engaging suggestions to users. This helps alleviate decision fatigue and frustration associated with selecting movies from a vast array of options, ultimately enhancing user satisfaction and maximizing content consumption. Additionally, the project contributes to the advancement of recommendation systems, particularly in the domain of content-based approaches, by leveraging cosine similarity as a robust similarity metric.

## Hardware and Software Requirements

### Hardware Requirements:

- Core i3 processor and above
- At least 4GB RAM
- At least 100GB storage

### Software Requirements:

- Python 3.6.10 or above
- Jupyter Lab / Notebook
- Google Colaboratory
- Visual Studio Code
- Packages: numpy, pandas, cosine similarity, scikit learn, pickle

## Analysis and Planning

### Step 1 - Gather Data:

Download the TMDb dataset, a collection of movie data, which will serve as the basis for training the recommendation system.

### Step 2 - Pre-Process Data:

Filter the dataset to include only necessary columns, such as movie ID, cast, director, genres, overview, and keywords. Remove any rows with missing values to ensure data quality.

### Step 3 - Build Model:

Develop a content-based recommendation model using text vectorization techniques, such as Bag of Words, to convert movie features into numerical representations. Calculate cosine similarity between movies to determine their similarity.

### Step 4 - Develop Front-End:

Create a user-friendly interface using Streamlit, allowing users to input a movie and receive personalized recommendations. Implement a function to fetch movie posters from the TMDb API for visual representation.

### Step 5 - Deploy the WebApp on Github Pages:

After finalizing the Streamlit application, upload the code to a GitHub repository and activate GitHub Pages to host the web app. By pushing the commits to GitHub and enabling GitHub Pages, users can access the deployed recommendation system online via the provided URL.

## Implementation

### Implementation Process:

The implementation process is further divided into three phases:

1. **Data Preprocessing**
2. **Data Analysis and Vectorization**
3. **Model Building and Testing**
4. **Designing Frontend and Deploying**

#### 1. Data Preprocessing:

- **Data Collection**: Download the TMDb dataset containing movie information.
- **Data Cleaning**: Filter the dataset to include relevant columns and remove any rows with missing values.
- **Data Transformation**: Convert categorical variables into numerical representations if necessary.

#### 2. Data Analysis and Vectorization:

- **Text Vectorization**: Utilize techniques like Bag of Words or TF-IDF to convert textual movie features into numerical vectors.
- **Feature Engineering**: Extract additional features from movie metadata if needed.
- **Exploratory Data Analysis (EDA)**: Analyze the distribution of features and correlations between variables.

#### 3. Model Building and Testing:

- **Cosine Similarity Calculation**: Compute cosine similarity scores between movies based on their feature vectors.
- **Recommendation Generation**: Develop algorithms to generate personalized movie recommendations for users.
- **Model Evaluation**: Assess the performance of the recommendation system using metrics like precision, recall, and accuracy.

#### 4. Designing Frontend and Deploying:

- **User Interface Design**: Create an intuitive and visually appealing interface for users to interact with the recommendation system.
- **Integration with Backend**: Connect the frontend interface with the recommendation model backend.
- **Deployment**: Deploy the application on GitHub Pages or other hosting platforms for public access.

## Future Enhancements

- Incorporate collaborative filtering techniques to enhance recommendation accuracy.
- Implement user feedback mechanisms to improve recommendation relevance over time.
- Explore deep learning models for more sophisticated feature representation.
- Extend the system to recommend other types of media such as TV shows, books, or music.

## Contributors

Our project's success is a testament to the power of teamwork and collaboration. Each member of our team brought unique skills, knowledge, and enthusiasm to the table, contributing to the project's development in diverse ways.
Here are our group members:

1. [Mangesh Pangam](https://github.com/Mangesh2704)

2. [Rakshita Sarap](https://github.com/RakshitaSarap)

3. [Saish Rane](https://github.com/saishrane-11)

## Acknowledgments

- Special thanks to [TMDb](https://www.themoviedb.org/) for providing the movie dataset.
- Inspiration and guidance from various online tutorials and resources.

Live Demo: https://movie-recommendation-system27.streamlit.app/

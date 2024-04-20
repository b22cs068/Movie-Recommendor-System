# Movie-Recommendataion-System
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Movie Recommendation System</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        code {
            background-color: #f4f4f4;
            padding: 2px 5px;
            border-radius: 5px;
        }
        pre {
            background-color: #f4f4f4;
            border: 1px solid #ddd;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }
        a {
            color: #0077cc;
        }
    </style>
</head>
<body>
    <h1>Movie Recommendation System</h1>
    
    <h2>Overview</h2>
    <p>This repository contains a movie recommendation system that employs multiple machine learning models to provide personalized movie recommendations based on different sets of features. The models used include K-Nearest Neighbors (KNN), Artificial Neural Networks (ANN), Support Vector Machines (SVM), and Gaussian Mixture Models (GMM).</p>
    
    <h2>Models and Features</h2>
    <ul>
        <li><strong>K-Nearest Neighbors (KNN):</strong>
            <ul>
                <li><strong>Features:</strong> User ID, Name of the Movie</li>
                <li><strong>Description:</strong> Provides recommendations by finding similar users based on movie preferences.</li>
            </ul>
        </li>
        <li><strong>Artificial Neural Network (ANN):</strong>
            <ul>
                <li><strong>Features:</strong> Genres, Ratings, User Feedback</li>
                <li><strong>Description:</strong> Predicts user preferences based on non-linear relationships in movie features and user feedback.</li>
            </ul>
        </li>
        <li><strong>Support Vector Machines (SVM):</strong>
            <ul>
                <li><strong>Features:</strong> User ID, User Feedback</li>
                <li><strong>Description:</strong> Classifies users into different preference groups to suggest movies that match their tastes.</li>
            </ul>
        </li>
        <li><strong>Gaussian Mixture Model (GMM):</strong>
            <ul>
                <li><strong>Features:</strong> User ID</li>
                <li><strong>Description:</strong> Clusters users into groups based on their movie watching patterns and preferences.</li>
            </ul>
        </li>
    </ul>

    <h2>Getting Started</h2>
    <h3>Prerequisites</h3>
    <p>Python 3.x</p>
    <p>Libraries: numpy, scipy, sklearn, keras (for ANN)</p>
    
    <h3>Installation</h3>
    <ol>
        <li>Clone the repository:
            <pre><code>git clone https://github.com/yourusername/movie-recommendation-system.git</code></pre>
        </li>
        <li>Install required Python packages:
            <pre><code>pip install -r requirements.txt</code></pre>
        </li>
    </ol>
    
    <h3>Running the Models</h3>
    <p>To run each model individually, navigate to the source code directory and execute the corresponding Python script. For example:
        <pre><code>python knn_model.py</code></pre>
    </p>
    
    <h2>Usage</h2>
    <p>Describe how to use the system to make predictions. Provide examples of commands or scripts to run, along with descriptions of the expected outcomes.</p>
    
    <h2>Contributing</h2>
    <p>We welcome contributions to improve the recommendation algorithms or any other aspects of the system. Please follow the standard fork-branch-pull request workflow.</p>
    
    <h2>License</h2>
    <p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>
    
    <h2>Authors</h2>
    <p>Your Name</p>
    
    <h2>Acknowledgments</h2>
    <p>Hat tip to anyone whose code was used, inspiration, etc.</p>

</body>
</html>

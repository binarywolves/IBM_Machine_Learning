# Presentation of findings

## streamlit included

To create this document, it is necessary not only to complete the previous tasks, but also to create a <code>streamlit</code> application, 
making the course recommendation models more interactive. 

From the courses listed in the app, the user can choose which courses she/he has audited or completed. 
Since this option is not selectable separately (only a checkmark can be put on a given course), 
I made sure in a backend.py file that the courses selected by the user are assigned 2.0 or 3.0 values using numpy's random. 

The available dataset ratings.csv is automatically completed with user's ratings as well.

models = [
"Course Similarity",
"User Profile",
"Clustering",
"Clustering with PCA",
"KNN",
"NMF",
"Neural Network",
"Regression with Embedding Features",
"Classification with Embedding Features"
]



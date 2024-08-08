# Spam-Detection-System-Using-TF-IDF-and-Machine-Learning

This project focuses on building a machine learning model to automatically classify emails as "spam" or "ham" (not spam) using text classification techniques. The process begins with converting the email text into numerical features through TF-IDF (Term Frequency-Inverse Document Frequency) vectorization. This method highlights the importance of words within each email relative to the entire dataset, making it a crucial step in preparing the data for model training.

Once the data is processed, the model is trained to differentiate between spam and legitimate emails based on these TF-IDF features. The performance of the model is evaluated on both training and test datasets, with an accuracy of over 96% achieved in both cases. This high level of accuracy indicates the model's effectiveness in identifying spam emails.

Additionally, the project includes a predictive system that applies the trained model to classify new, unseen emails. This feature allows for real-time spam detection, making the system practical for deployment in an email filtering environment.

Overall, this project showcases the application of natural language processing and machine learning in automating the task of email filtering, providing a robust solution for distinguishing between spam and non-spam messages.

# Deep-Learning-Project
The Russo-Ukrainian conflict has sparked intense debates and discussions on social media, particularly Twitter, making it a rich source of user-generated data for analysis. This study focuses on leveraging machine learning and natural language processing techniques to extract valuable insights from tweets related to the conflict.
The primary objective is to predict the personalities of Twitter users based on their posts during this geopolitical dispute. By analyzing the textual data and employing predictive algorithms, this study aims to shed light on the relationship between individual’s online expressions and their personality traits in the context of the Russia-Ukraine conflict.
LIWC (Linguistic Inquiry and Word Count) is a text analysis tool that categorizes words based on linguistic and psychological dimensions, provides insights into the composition and psychological aspects of text data.

Linguistic Categories: Classifies words based on their linguistic properties, such as pronouns, verbs,adjectives, and adverbs.

Psychological Categories: Classifies words based on their psychological connotations, such as positive emotions,negative emotions, cognitive processes, and social  processes.

Text Analysis: The process of examining and interpreting textual data to extract meaningful information and insights.

Psychological Insights: Inferences and understanding gained from analyzing text data, providing insights into psychological aspects such as personality traits, emotional states, and cognitive processes.

The Big Five model is a widely accepted framework in psychology that categorizes human personality traits into five broad dimensions.
O : Openness -
The tendency to be open-minded, creative, and receptive to new experiences.
C : Conscientiousness -
The trait of being organized, responsible, and diligent in achieving goals.
E : Extraversion -
The inclination towards social interaction, assertiveness, and seeking stimulation from the external environment
A : Agreeableness - 
The disposition to be kind, cooperative, and considerate towards others.
N : Neuroticism -
The propensity to experience negative emotions such as anxiety, sadness, and irritability.
By using the Linguistic Inquiry and Word Count (LIWC) tool, we can predict the OCEAN scores.

LIWC allows us to analyze linguistic patterns and psychological categories in text data, providing insights into an individual's personality.

To predict a user's personality, we train a Support Vector Classifier (SVC) algorithm to learn the relationships between linguistic features and OCEAN scores in the training data.

The trained SVC algorithm is then applied to the testing dataset By analyzing linguistic features and applying the model, we can make predictions about their personalities based on the OCEAN scores.
MLP (Multilayer Perceptron) classifiers: It is a type of artificial neural network with multiple layers of interconnected neurons. By training on labeled data, it can learn complex patterns and relationships in the input features to predict personality traits based on the learned weights and biases.

Long Short-Term Memory (LSTM): It is a type of recurrent neural network (RNN) architecture that can capture long-term dependencies in sequential data. It can predict the personality by processing sequences of textual or temporal data to capture contextual information and make predictions based on the learned patterns.

GRU (Gated Recurrent Unit): It is another type of recurrent neural network that addresses the vanishing gradient problem and captures dependencies in sequential data. It can predict the personality by analyzing sequential data, such as textual inputs, and leveraging gate mechanisms to selectively retain or forget information at each time step.

RCNN (Region-based Convolutional Neural Network): The custom model combines convolutional and recurrent layers to process and classify text data for personality prediction. By leveraging the local patterns captured by the convolutional layers and the sequential dependencies learned by the recurrent layers (LSTM), the model analyzes the input text to make predictions about individual’s personality traits in a compact and efficient manner.Accuracy: Accuracy is a metric that measures the overall correctness of predictions.

￼

Precision: This metric indicates the model's ability to avoid false positives.

￼

Recall: This metric indicates the model's ability to avoid false negatives.

￼

F1-score: This metric provides a balanced measure of the model's performance.

￼
conclusion
The RCNN model achieved the highest accuracy of 94%, while the Gaussian Naive Bayes algorithm performed less accurately with 77% accuracy. 

The effectiveness of linguistic characteristics obtained from the LIWC software was limited in cases where tweet information was unclear.



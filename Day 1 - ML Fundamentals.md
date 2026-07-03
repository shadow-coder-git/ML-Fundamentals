### ML Fundamentals:

#### Types of Machine Learning based on amount of supervision needed:
1) Supervised - Has 2 subcategories - Regression and Classification 
2) UnSupervised - Has 4 subcategories - Clustering, Dimenstionality Reduction, Anomaly Detection and Association Based Rule 
3) SemiSupervised
4) Reinforcement

Details:

1) Supervised (Regression) - We have both input and output values provided, based on which it creates a mathametical relation between the data points. Regression Algorithm is used when the output needs to be numerical like prediction of price of the house etc.

   > Scenario: A real estate website wants to build a tool that predicts the exact selling price of a house. They feed the algorithm a dataset containing thousands of past house sales in the city. For every house in the dataset, they know the square footage, number of bedrooms, zip code, and the exact dollar amount it sold for.


   Supervised (Classification) - We have both input and output values provided, based on which it creates a mathametical relation between the data points. Classification/Logistic Algorithm is used when the output needs to be yes/no or categorical like provision of loan to the customer based on past data.

   > Scenario: A car insurance company wants to look at a new customer's profile (age, driving history, car model) and automatically sort them into one of three risk categories: "Low Risk", "Medium Risk", or "High Risk" so they can decide whether to approve their policy. They train the algorithm using a massive database of 500,000 past drivers who were already thoroughly analyzed and assigned into one of these three specific buckets by human experts.

   <img width="638" height="359" alt="image" src="https://github.com/user-attachments/assets/24455689-d3b5-4203-9e2c-de39207c5401" />






2) Unsupervised (Clustering) - We only recieve input and based on that we need to predict the output. Clustring basically groups the nearest datapoints and creates cluster of data points.

   > Scenario: A global streaming platform wants to group its millions of subscribers into distinct buckets based on their viewing habits (e.g., how many sci-fi movies they watch, what time of day they log in, how long they watch). The platform doesn't have any pre-set categories or labels for these groups; they just want the algorithm to naturally find patterns and group similar viewers together so they can recommend new layout designs.

   <img width="511" height="400" alt="image" src="https://github.com/user-attachments/assets/69e00cbe-5c3c-46f4-b972-eae60341f7db" />

   Unsupervised (Dimensionality Reduction) - We only recieve input and based on that we need to predict the output. If we have a lot of co-related dimensions we reduce it to few dimensions like no.of rooms and no.of bathrooms can be reduced to sq.ft area.

   > Scenario: An e-commerce website tracks 500 different features for every single product on its platform (e.g., click rate, average scroll depth, zoom-in rate, return history, color popularity, package dimensions, shipping weight, etc.). Having 500 columns of data is causing their machine learning servers to crash and making calculations incredibly slow. They want to use an algorithm that can compress these 500 features down to just 5 "super-features" that capture the core patterns of the data without losing important information. They don't have any labels or target categories; they just want to shrink the data size.

   Unsupervised (Anamoly Detection) - We only recieve input and based on that we need to predict the output. If any data point is out of the common group of data points then its an anomoly like sudden spike/dip in share market value.

   > Scenario: A nuclear power plant installs thousands of live sensors to monitor its reactors (tracking core temperature, pipe pressure, vibration frequencies, etc.). Because the plant has thankfully never had a catastrophic meltdown, they don't have any data or labels for what a "meltdown" looks like on a graph. They want an algorithm that constantly watches the normal, everyday baseline data, and sounds a massive alarm the absolute second any sensor combination looks completely bizarre, weird, or unprecedented.

   <img width="780" height="595" alt="image" src="https://github.com/user-attachments/assets/572f0a3f-ec1c-4c22-a8f7-0483b7da6663" />

   Unsupervised (Association Rule Based) - We only recieve input and based on that we need to predict the output. In this algorithm we try to find the association between data points like in a mall shampoo or conditionar go hand to hand.

   > Scenario: An e-commerce giant wants to optimize its warehouse layout. They want an algorithm to scan millions of customer receipts to find items that are frequently bought together in the same transaction, even if they seem completely unrelated (e.g., discovering that people who buy diapers on Friday nights also buy beer). They will use this information to place those items physically closer to each other in the warehouse to speed up packing times.

   <img width="752" height="440" alt="image" src="https://github.com/user-attachments/assets/b9f4cb6c-0d13-488a-a799-d8e1b1a66242" />


3) Semi-Supervised - Labeling the data is costly and timetaking, so we don't label everything but the sample of unique data points and the algorithm learns to apply it to others.
   > Scenario: A medical research lab has collected 100,000 lung X-ray scans. Hiring expert radiologists to look at and label every single one of those 100,000 scans as either "Pneumonia" or "Healthy" is way too expensive and would take months. Instead, the lab pays a radiologist to carefully label just 1,000 of them. They want to use an algorithm that can take those 1,000 labeled scans, mix them with the 99,000 unlabeled scans, and learn how to classify future X-rays accurately.


4) Reinforcement - Here we neither get input nor output. The algorith follows risk/reward based rule. If the model predicts correct direction it gets the reward else punishment.
   > Scenario: A tech startup is building an autonomous drone designed to fly through thick forest canopies to map wildlife. The drone isn't given any human flight data or pre-recorded steering paths to follow. Instead, it is placed in a virtual forest simulator. Every second it flies safely without hitting a branch, it earns +5 points. If it clips a leaf, it loses -10 points. If it crashes entirely into a tree, it gets a massive penalty of -500 points and the simulation resets. Over millions of virtual flights, it figures out how to navigate tight spaces perfectly.

   <img width="605" height="432" alt="image" src="https://github.com/user-attachments/assets/2ba4f529-c5f1-4f96-93a5-a550c8c078d1" />


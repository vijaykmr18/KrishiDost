# KrishiDost
As we all are familiar with the fact that thousands of farmers die every year. Activists and scholars have offered no. of conflicting reasons such as high debt burdens, corruption in subsidies, failing to detect crop disease timely resulting in crop failure which leads to mental health issues. Major problem faced by the problem are: 1)Crop failure- due to disease 2)An over reliance on traditional crops 3)Lack of information causes economic loss 4)Middleman reaping the bulk of the revenue. So, we the team Thinker_Bots came up with the solution which will not only increase the yield per hectare but also increase their income and improve the quality of their produce. We have developed an AI based solution that bridges the gap between the farmers and customers, providing recommendations to sow the best crop, prevent damage to the crop or soil. The solution is a single stop shop to have all the above accomplished and make it available to all farmers in their regional language.

A) Crop recommendation system: Designed this classification model using random forest algorithm, giving input as nitrogen, phosphorous and potassium values, pH of soil, temp. But waking up to reality we cannot solve a ground level problem, so we need an IOT device which will test the soil give us the N P K values which we will be giving to our model. This supervised machine learning algorithm grows and combines multiple decision trees to give final results with great accuracy of 99%. output labels 32 crops including- 'rice', 'wheat', 'mungbean', 'tea', 'millet', 'maize', 'lentil', 'moth beans', 'coconut', 'tobacco', 'kidney beans', 'jute', 'coffee', 'cotton', 'groundnut', 'peas', 'rubber', 'pomegranate', 'watermelon', 'sugarcane', 'pigeon peas', 'chickpea', 'banana', 'Black gram', 'adzukibeans','grapes', 'apple', 'mango', 'muskmelon', 'orange', 'papaya'.

Problem- farmers in India have been producing the same crops for a very long time because of which soil composition and nutrients decreases, they are unable to maximize their profits and occasionally have to deal with crops failing completely.

Our solution- We have created a ML model to address the issue that is taught to evaluate soil quality based on NPK (nitrogen, potassium, and phosphorus) levels in the soil and forecast the best crop for that area to farmers so, they may maximize their income.

Future Aims- By connecting an IOT device to our model, farmers will be able to check their results by simply inputting a soil sample.

B) Crop Disease Detection we know that Without proper identification of the disease and the disease-causing agent, disease control measures can be a waste of time and money and can lead to further plant losses. Proper disease diagnosis is therefore vital.

You might be thinking that farmer who is growing the crop must be having knowledge of these things too, if not all, then maximum of them. But obvious they can't be very accurate which can result in waste of their efforts ALSO.

We used CNN and its architecture ResNet which gave 95%+ accuracy because it not only classifies image but goes for every pixel classification.

This model will be able to quickly distinguish between a wide range of diseases. In order for farmers to save their crops by taking the necessary action, this algorithm also suggests the best treatments for diseases.

To help farmers to detect diseases we create our mobile app which will be connected with our ML model. Farmers just need to click the picture of leaf or select from gallery to detect disease and know the best treatment.

Our machine learning Trained on 38 different classes for 14 crops including grapes, apple, cherry, corn, orange, peaches, pepper, potato, Raspberry, Blueberry, Soyabean, Squash, Strawberry, Tomato.

Plant Village dataset - Kaggle

Also, to make it more user friendly, we have made an android application where just by clicking the image using camera and clicking on predict, our application will read the name of disease and its cure.

C) Fertilizer recommendation system:

Designed this classification model using random forest algorithm, giving input as nitrogen, phosphorous and potassium values, and suggest the best suitable fertilizer to improve the quality of soil health.

D)Lack of information and role of middleman:

Farmers in India are typically not so well educated, which make it easy for middleman to influence them and convince them to sell their yield for low prices. Additionally, they lack knowledge about contemporary farming methods that could help them increase their revenues.

To address this, we provide our own website KRISHI-DOST.

Our web application Krishi-dost packed with ml model provide large number of feature of farmers-

Similar to how true friends support one another throughout their lives, we pledge to assist our nation’s farmers by offering them the following amenities: 1)KRISHI-DOST provide a platform, where farmers may purchase anything related to farming, such as Fertilizers, seed and medications. 2) farmers can connect directly to consumers(customers) and sell their yield directly to them eliminating the role of middleman. 3) Website offer best farming practices on the basis of result received from IOT device and ML model. 4) It enables farmers to monitor the output of their farms and grow their business and access a larger market

KRISHI-DOST MOBILE APP-

To help farmers to detect disease we create we create our mobile app KRISHI-DOST which is connected to with machine learning model. Our app is so much user friendly and easy to use.

Farmers just need to click pic of the leaf or select from gallery and our app will tell you the disease and also the best treatment.

Obstacles faced by us:
In this case, the target audience of families, farmers, and environmentalists, this project was created with their accessibility and ease of use in mind. As a result, it was crucial to include as many features as possible that would be truly helpful to both novice and expert users. These features include allowing users to access the service and the assistance they require in the format and language that is most convenient for them, as well as enabling them to connect with and receive assistance from local or specialised experts who can advise them on the best course of action for a fee.

The integration of all the features into a single service while maintaining consistency and validity across all front end HTML and CSS pages, ensuring that the Flask framework was designed and implemented in such a way that all necessary pages and resources load quickly and efficiently through the browser, and ensuring that the additional APIs that we are incorporating are completed were some of the biggest challenges we encountered while building the project. During multiple testing sessions, the website would frequently take a long time to reply to straightforward commands, crash, or produce unexpected Python errors as a result of routing directives coming from HTML sites.

To solve these obstacles, pair programming was used, where one member modified the code while the other member continuously checked for consistency and syntactical correctness, allowing for effective building.

FUTURE ASPECT:
1)Sensor technology can be used to assess the product’s quality and make it cost effective.

2)We may add an SMS alert feature, so that the customer received an SMS when a new item is purchased, a new product Is released, a delivery date is approaching, etc..

3)We can include a chatbot where farmers can talk to Agri specialists to address farming – related problems.

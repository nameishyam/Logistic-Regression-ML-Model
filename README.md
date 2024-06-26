# FAKE NEWS DETECTION
**Abstract**<br><br>
Online payment fraud poses a significant threat to the integrity of digital transactions, necessitating effective detection mechanisms to safeguard businesses and consumers. In response, machine learning techniques have emerged as a promising approach for enhancing fraud detection capabilities. This literature survey explores the landscape of online payment fraud detection using machine learning, drawing insights from a variety of research sources. We examine methodologies, techniques, and advancements in the field, covering topics such as data preprocessing, feature selection, model training, and evaluation metrics. By synthesizing findings from diverse studies, we provide a comprehensive overview of the challenges and opportunities in online payment fraud detection. This abstract serves as a roadmap for researchers and practitioners seeking to leverage machine learning for bolstering the security of digital transactions and preserving trust in online commerce.<br><br>
**Introduction**<br><br>
The rise of online commerce has revolutionized the way we conduct transactions, offering
unparalleled convenience and accessibility. However, this convenience comes with its share of
risks, as online payment platforms become targets for fraudulent activities. From credit card fraud
to identity theft, the digital realm presents numerous challenges for ensuring the security of
financial transactions.
In response to these threats, organizations are increasingly turning to machine learning techniques
to fortify their defenses against online payment fraud. By harnessing the power of data analytics
and advanced algorithms, these systems aim to detect suspicious activities, identify fraudulent
patterns, and mitigate potential risks in real-time.
This essay explores the role of machine learning in online payment fraud detection, outlining key
strategies, techniques, and considerations involved in building effective fraud detection systems.
From data collection and preprocessing to model training and deployment, we delve into the
intricacies of leveraging machine learning to safeguard digital transactions and preserve the trust
of consumers and businesses alike.
# Procedure
**A. Data Collection**<br><br>
The real-life data that includes structured data such as person's basic information like the amount he\she has spent, and the locations of where these transactions has taken place. Dataset excludes the
person’s personal details such as name, ID, and locations as to reserve their privacy. <br><br>
**B. Preprocessing**<br><br>
The collected data are preprocessed for the availability of missing values in most of the structured
data. Hence, it is essential to fill out the missed data or remove or modify them to enhance the
quality of the dataset. The preprocessing step also eliminates the commas, punctuations, and
whitespaces. Once the preprocessing of data has been completed, it is then subjected to feature
extraction followed by disease prediction. <br><br>
**C. Model Description**<br><br>
As discussed above, the dataset that we have taken consists of both structured and unstructured data. Structured data comprises essential details like transaction amount, date/time, merchant info, cardholder details, transaction type, location, previous transaction history, and a fraud indicator. This structured information provides a comprehensive view of each transaction, aiding in fraud detection.

Less common but valuable, unstructured data includes transaction descriptions, comments, customer service interactions, and merchant reviews. While not as prevalent, this textual data can offer additional context and insights, enriching fraud detection efforts.

By integrating both structured and unstructured data, analysts gain a more holistic view of transactions, enhancing fraud detection capabilities and overall financial security. Unstructured data is an added advantage of the prediction task to get a more accurate result. Dataset is split into 80% for training
and 20%for testing.

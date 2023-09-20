Watson services on IBM Cloud provide a cloud-hosted marketplace where application providers of all sizes and industries are able to tap into resources for developing applications powered by Watson services. Developers can combine the Watson services (and other services available in IBM Cloud) with additional logic to build cognitive applications.

The available resources include developer toolkits, educational materials, and access to Watson APIs. This approach makes IBM Watson technology available as a development platform in the cloud, to enable a worldwide community of software application providers to build a new generation of applications infused with Watson AI capabilities.

![](https://courses.ibmcep.cognitiveclass.ai/assets/courseware/v1/25bc7bf0bdd833b475dbc36e9c5cfe62/asset-v1:IBMCE+CEAIA1IN+1+type@asset+block/watson_service_cloud.png)

# Watson Assistant

**Intents**: A category that defines a user's goal or purpose.
**Entity**: Watson's way of handling significant parts of an input that should be used to alter the way it responds to the intent.
**Dialog**: The dialog defines what your assistant says in response to customers.
**Watson Discovery**: Add a cognitive search and content analytics engine to applications to identify patterns, trends and actionable insights that drive better decision-making. Rapidly build cognitive, cloud-based exploration applications that unlock actionable insights hidden in unstructured data. Securely unify structured and unstructured data with pre-enriched content, and use a simplified query language to eliminate the need for manual filtering of results.


## Watson Discovery

With IBM Watson® Discovery, you can boost the productivity of knowledge workers by automating the discovery of information and insights with advanced Natural Language

- Extract value from unstructured data by converting , normalizing, enriching it.
- Use a simplified query language to explore data or quickly tap into pre-enriched datasets like Discovery News collection.

It takes data in multiple formats such as word, pdfs, html. Ingests it, converts that data using NLP into rich contexts in an HTML format and then cleans it and normalizes it.
It stores it in the cloud with an index. The user goes through it using Natural Language Query against that data.

__Steps to Watson Discovery Service__
1. Create a BlueMix account
2. Log in to BlueMix, create a Watson Discovery service, and create Storage Service
3. Create Collection
4. Create custom configuration
5. Add data to the collection
	1. Sample data to train the service
	2. Data to be analyzed
6. Query the collection

## Watson Natural Language Understanding

Analyze text to extract meta-data from content such as concepts, entities, keywords, categories, sentiment, emotion, relations, semantic roles, using natural language understanding. With custom annotation models developed using Watson Knowledge Studio, identify industry/domain specific entities and relations in unstructured text.

It offers a suite of features that can be used for text analysis:- 
	Concepts  Entities  Keywords  Categories  Sentiment  Emotion  Relations  Semantic Roles  Metadata
Allows to understand the topics mentioned in the text.

**Natural Language Classifier**: The **Natural Language Classifier service applies** AI techniques to return the best matching classes for a sentence or phrase. For example, you submit a question and the service returns keys to the best matching answers or next actions for your application. You create a classifier instance by providing a set of representative strings and a set of one or more correct classes for each training. After training, the new classifier can accept new questions or phrases and return the top matches with a probability value for each match.

## Watson Visual Recognition

Visual Recognition understands the contents of images. This service analyzes images for scenes, objects, faces, colors, food, text, explicit content and other subjects that can give you insights into the visual content. 

It can turn images into organized information. It can learn any type of visual data.

## Watson Speech to Text

The Speech to Text service converts the human voice into the corresponding text. Use this service to convert audio and voice into text for a quick understanding of content. It can be used anywhere there is a need to bridge the gap between the spoken word and the written form, including voice control of embedded systems, transcription of meetings and conference calls, and dictation of email and notes. This easy-to-use service uses machine intelligence to combine information about grammar and language structure with knowledge of the composition of the audio signal to generate an accurate transcription.  
  
The following languages are currently available: English (US), English (UK), German (Broadband model only), Japanese, Arabic (MSA, Broadband model only), Mandarin Chinese, Portuguese (Brazil), Spanish, French (Broadband model only) and Korean.

## Watson Text to Speech 

Use the Watson Text to Speech API to convert written text into natural sounding audio in a variety of languages and voices. The Text to Speech service processes text and natural language to generate synthesized audio output complete with appropriate cadence and intonation. It is available in several voices:  
  

- English (US): 2 female voices, 1 male voice
- English (UK): 1 female voice
- French: 1 female voice
- German: 1 female voice, 1 male voice
- Italian: 1 female voice
- Spanish (Castilian): 1 female voice, 1 male voice
- Spanish (North American): 1 female voice
- Portuguese (Brazil): 1 female voice
- Japanese: 1 female voice

## Watson Language Translator

Enables application developers to directly process translations using a simple standard RESTful API.
language Translator service offers multiple domain specific translation models in addition with texts with very specific terminology and language.
3 Levels of customizations:

- **Forced Glossary Customization** allows you to upload pairs of matching terms in the source and target language. These pairs can completely overrule the original translation modules. 
- **Parallel Phrase Customization** allows you to upload a series of matching phrases in source and target language. This doesn't completely overrule the original translation modules.
- **Corpus Level Customization** allows you to upload a plain text file that contains a body of text in the target language. It can be used to make the translation more human.

## Watson Personality Insights Service

Watson Personality Insights is an IBM service that allows you to gain insight about a user based on social media, digital correspondence, or any other communication. 
The service analyzes the written input and returns the user's personality based on the Big 5 personality traits, needs, and values.
Additionally, the service also returns the consumption preference of the user, based on their personality.

The Big Five treats are:

- Openness to experience: Curious versus Cautious. Could be broken down in these facets: adventurousness, artistic interests, emotionality, imagination, intellect, liberalism.
- Conscientiousness: Organized versus Easy-going. Facets: achievement striving, cautiousness, dutifulness, orderliness, self-discipline, self-efficacy.
- Extroversion: Outgoing versus Reserved. Facets: activity level, assertiveness, cheerfulness, excitement seeking, friendliness, gregariousness.
- Agreeableness: Friendly vs challenging: altruism, cooperation, modesty, morality, sympathy, trust.
- Neuroticism: Sensitive vs Confident. Facets: anger, anxiety, depression, immoderation, self-consciousness, vulnerability.

Values
The values returned are a set of traits about the person that influence their decision making.
These values include:
-  Conservation/Tradition
-  Self-transcendence/Helping others 
- Hedonism/Taking pleasure in life 
- Self-enhancement/Achieving success 
- Open to change/Excitement

Needs
The Needs model describes which aspects of a product are likely to resonate with a person.
These include:
- Excitement,
- harmony, 
- curiosity,
- ideal,
- closeness,
- self-expression,
- liberty,
- love,
- practicality,
- stability,
- challenge, and structure.

Personality Insights Use Cases
- A way to understand your customer
	- Learn what kind of person they are so you can offer a better experience 
	- Send targeted advertisements for a more personal experience
- Matching customers with compatible sales people
	- You can match a customer's personality with a compatible sales representative based on their personality.
-  Understand consumption preferences of a customer o Allow you to predict what a customer would likely buy.

## Watson Tone Analyzer

IBM Watson Tone Analyzer analyzes the tone of input content.
Tone Analyzer uses linguistic analysis to detect three types of tones from communications: emotion, social, and language. 
There are two endpoints available for you to use; the general purpose endpoint for analyzing text, or the customer engagement endpoint for analyzing conversation. Each endpoint helps you understand the emotional and language tones used in communication.

## Watson Studio

IBM Watson Studio is a collaborative environment with AI tools that a team can use to collect and prepare training data, and to design, train, and deploy machine learning models.  
  
It includes a range of tools, including graphical tools to build a model and tools that automate running thousands of experiment training runs and hyperparameter optimization. Watson Studio AI tools support popular frameworks, including TensorFlow, Caffe, PyTorch, and Keras.  
  
Watson Studio AI tools can be grouped into four categories:  
  

- Visual recognition
- Natural language classification
- Machine learning
- Deep learning

## Watson Machine Learning

Watson Machine Learning enables users to perform two fundamental operations of machine learning: training and scoring.  
  

- Training is the process of refining an algorithm so that it can learn from a data set. The output of this operation is called a model.
- Scoring is the operation of predicting an outcome by using a trained model. The output of the scoring operation is another data set that contains predicted values.

  
Watson Machine Learning is designed to address the needs of two primary users:  
  

- Data scientists: Create machine learning pipelines that use data transformations and machine learning algorithms. They typically use notebooks or external tools to train and evaluate their models. Data scientists often collaborate with data engineers to explore and understand the data.
- Developers: Build intelligent applications that use the predictions output by machine learning models. Watson Machine Learning is integrated with Watson Studio.

## IBM Watson Knowledge Studio

IBM Watson Knowledge Studio enables developers and domain experts to collaborate and create custom annotator components for unique industries and domains. These annotators can identify mentions and relationships in unstructured data and be easily administered throughout their lifecycle by using one common tool. Annotator components can be deployed directly to Watson Explorer, Watson Natural Language Understanding, and Watson Discovery.


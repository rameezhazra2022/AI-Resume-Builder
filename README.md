https://www.youtube.com/watch?v=VF2D9hEV1cE

Method#1: ChatGPT X LaTeX

ChatGPT Prompt

Build a resume for me in Latex - using a fancy colorful template.

My name is Pooja Sinha. B.Tech. from ABC University, Gurgaon - completed in 2023. I am currently looking for a Data Science job. I have done 4-5 Machine Learning Projects, including Sentiment Analysis, Fake News Detection, Traffic Sign Detection, etc. I am currently working as a Data Science Intern at XYZ Limited.

Fill in the gaps you may find in the script appropriately. I need a fancy colorful LaTeX resume.


Tool Links
ChatGPT: https://chat.openai.com/ 
Overleaf: https://www.overleaf.com/ 


LaTeX Code

\documentclass[11pt,a4paper,sans]{moderncv}

\moderncvstyle{banking}
\moderncvcolor{blue}

\usepackage[utf8]{inputenc}
\usepackage[scale=0.75]{geometry}

\name{Pooja}{Sinha}
\title{Data Scientist}
\address{123 Main Street}{Gurgaon}{India}
\phone[mobile]{+91~1234567890}
\email{pooja.sinha@email.com}
\homepage{www.linkedin.com/in/poojasinha}

\begin{document}

\makecvtitle

\section{Education}
\cventry{2019--2023}{Bachelor of Technology}{ABC University}{Gurgaon}{\textit{CGPA -- 8.0}}{}

\section{Experience}
\cventry{2022--Present}{Data Science Intern}{XYZ Limited}{Gurgaon}{}{Worked on various data science projects, including:
\begin{itemize}
\item Sentiment analysis
\item Fake news detection
\item Traffic sign detection
\item And more
\end{itemize}}

\section{Skills}
\cvitem{Programming}{Python, R, SQL}
\cvitem{Data Analysis}{Pandas, Numpy, Matplotlib, Seaborn}
\cvitem{Machine Learning}{Scikit-learn, Keras, Tensorflow}
\cvitem{Tools}{Git, Jupyter Notebook, Tableau}
\cvitem{Languages}{English, Hindi}

\section{Projects}
\cvitem{Sentiment Analysis}{Developed a sentiment analysis model using natural language processing techniques to classify customer reviews as positive or negative.}
\cvitem{Fake News Detection}{Built a machine learning model to identify fake news articles using NLP and classification algorithms.}
\cvitem{Traffic Sign Detection}{Developed a computer vision system using deep learning algorithms to detect traffic signs in real time.}

\section{Interests}
\cvitem{Data Science}{Keeping up with the latest trends and developments in the field.}
\cvitem{Sports}{Playing cricket and badminton in my free time.}

\end{document}


ChatGPT Prompt for adopting this LaTeX Template

My name is Nilanjan Paul. I am currently looking for Software Engineering jobs. Working as an Intern with MNO Limited. Completed graduation from PQR University in New Delhi in 2022. 

Fill in all the gaps as per Nilanjan's profile. Write my resume in LaTeX strictly as per this sample LaTeX template:

<Insert Template here>


Method#2: ChatGPT X Canva

ChatGPT Prompt

Help me write my resume. Here's my profile brief:

My name is Pooja Sinha. B.Tech. from ABC University, Gurgaon - completed in 2022. I am currently looking for a Data Science job. I have done 4-5 Machine Learning Projects, including Sentiment Analysis, Fake News Detection, Traffic Sign Detection, etc. I am currently working as a Data Science Intern at XYZ Limited, Gurgaon (2023-23).


Tool Links
ChatGPT: https://chat.openai.com/
Canva: https://www.canva.com/ 
Method#3: ChatGPT X Reactive Resume

ChatGPT Prompt

Help me write my resume in JSON Format. Here's my profile summary:

My name is Nilanjan Paul. B.Tech. from ABC University, Gurgaon - completed in 2022. I am currently looking for a Data Science job. I have done 4-5 Machine Learning Projects, including Sentiment Analysis, Fake News Detection, Traffic Sign Detection, etc. I am a Data Science Intern at XYZ Limited, Gurgaon (2023-23).

Sample JSON resume format is provided below. Strictly follow the format and makeup information wherever missing according to my profile. I need all the sections to be included. Don't drop anything. Be short and crisp in writing.

JSON Resume Template between three backticks below:
```
{
"$schema": "https://raw.githubusercontent.com/jsonresume/resume-schema/v1.0.0/schema.json",
"basics": {
"name": "Pooja Sinha",
"label": "Data Scientist",
"image": "",
"email": "pooja.sinha@example.com",
"phone": "(123) 456-7890",
"url": "http://www.example.com",
"summary": "I am a B.Tech. graduate from ABC University, Gurgaon (completed in 2022) and currently seeking a Data Science job. I have experience in working on 4-5 Machine Learning projects, including Sentiment Analysis, Fake News Detection, and Traffic Sign Detection. Currently, I am working as a Data Science Intern at XYZ Limited, Gurgaon (2023-23).",
"location": {
"address": "",
"postalCode": "",
"city": "Gurgaon",
"countryCode": "IN",
"region": "Haryana"
},
"profiles": [
{
"network": "LinkedIn",
"username": "poojasinha",
"url": "https://www.linkedin.com/in/poojasingha"
},
{
"network": "GitHub",
"username": "poojasingha",
"url": "https://github.com/poojasingha"
}
]
},
"work": [
{
"name": "XYZ Limited",
"location": "Gurgaon, India",
"description": "",
"position": "Data Science Intern",
"url": "",
"startDate": "2023-01-01",
"endDate": "2023-12-31",
"summary": "Worked on various data science projects, applying machine learning techniques to solve real-world problems. Collaborated with cross-functional teams to analyze data, build models, and provide actionable insights.",
"highlights": []
}
],
"education": [
{
"institution": "ABC University",
"url": "",
"area": "Computer Science",
"studyType": "Bachelor",
"startDate": "2018-08-01",
"endDate": "2022-05-01",
"score": "",
"courses": []
}
],
"projects": [
{
"name": "Sentiment Analysis",
"description": "Developed a sentiment analysis model using natural language processing techniques to classify text as positive, negative, or neutral.",
"highlights": [
"Achieved an accuracy of 85% on a sentiment analysis dataset",
"Implemented the model using Python and the scikit-learn library",
"Performed feature engineering and applied various machine learning algorithms"
],
"keywords": [
"Sentiment Analysis",
"Natural Language Processing",
"Machine Learning",
"Python",
"scikit-learn"
],
"startDate": "",
"endDate": "",
"url": "",
"roles": [],
"entity": "",
"type": ""
},
{
"name": "Fake News Detection",
"description": "Developed a machine learning model to classify news articles as fake or real based on their content and source credibility.",
"highlights": [
"Built a dataset of labeled news articles",
"Implemented the model using Python and TensorFlow",
"Achieved an accuracy of 90% on a test dataset"
],
"keywords": [
"Fake News Detection",
"Machine Learning",
"Python",
"TensorFlow"
],
"startDate": "",
"endDate": "",
"url": "",
"roles": [],
"entity": "",
"type": ""
},
{
"name": "Traffic Sign Detection",
"description": "Developed a deep learning model to detect and classify traffic signs in images captured from a vehicle's camera.",
"highlights": [
"Collected and annotated a dataset of traffic sign images",
"Implemented the model using Python and TensorFlow",
"Evaluated the model's performance on a test dataset"
],
"keywords": [
"Traffic Sign Detection",
"Deep Learning",
"Python",
"TensorFlow"
],
"startDate": "",
"endDate": "",
"url": "",
"roles": [],
"entity": "",
"type": ""
}
],
"skills": [
{
"name": "Python",
"level": "Advanced",
"keywords": []
},
{
"name": "Machine Learning",
"level": "Advanced",
"keywords": []
},
{
"name": "Data Analysis",
"level": "Intermediate",
"keywords": []
},
{
"name": "Deep Learning",
"level": "Intermediate",
"keywords": []
},
{
"name": "Natural Language Processing",
"level": "Intermediate",
"keywords": []
},
{
"name": "TensorFlow",
"level": "Intermediate",
"keywords": []
},
{
"name": "scikit-learn",
"level": "Intermediate",
"keywords": []
}
],
"languages": [
{
"language": "English",
"fluency": "Fluent"
},
{
"language": "Hindi",
"fluency": "Native"
}
],
"interests": [
{
"name": "Data Science",
"keywords": []
},
{
"name": "Machine Learning",
"keywords": []
},
{
"name": "Artificial Intelligence",
"keywords": []
}
],
"references": [
{
"name": "John Doe",
"reference": "I had the pleasure of working with Pooja during her internship at XYZ Limited. She demonstrated excellent analytical and problem-solving skills in the field of data science. Pooja is a dedicated and highly motivated individual who would be a valuable asset to any data science team."
}
],
"meta": {
"canonical": "",
"version": "v1.0.0",
"lastModified": "2023-06-05T00:00:00"
}
}
```




Tool Links
ChatGPT: https://chat.openai.com/ 
Reactive Resume: https://rxresu.me/ 
JSON Editor: https://jsoneditoronline.org/ 
JSON Resume Template: https://github.com/jsonresume/resume-schema/blob/master/sample.resume.json 


Step-by-Step Process

Part#1
- Go to ChatGPT and use the above prompt for getting a JSON Resume
- Copy the JSON Code
- Save the .json file in the local disk
	- By using Notepad / TextEdit Tools
	- Or go to: jsoneditoronline.org/

Part#2
- Now go to Reactive Resume again & upload the JSON
- Go to Reactive Resume, create a free account
- Click on Import from External Sources
- Copy JSON Resume Format Link. And voila!!
- Platform allows easy customizations and offers a galore of themes



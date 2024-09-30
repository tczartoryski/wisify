# Wisify.ai - Legal Document Summarization Platform
Welcome to Wisify.ai, a cutting-edge platform designed specifically for legal professionals seeking customized, efficient, and comprehensive summaries of lengthy legal documents. Wisify.ai empowers lawyers and legal researchers by transforming extensive texts into concise, digestible summaries tailored to their specific needs.
## Introduction
In the fast-paced world of law, time is of the essence. Wisify.ai provides an innovative and indispensable tool that allows legal professionals to upload any length document and receive tailored summaries optimized for legal content. Whether you need a quick 5-minute rundown of a case, a 30-minute audio summary for your commute, or an hour-long podcast of a comprehensive document, Wisify.ai has you covered.  

  Please note that this website is planned to be monetized in the future, the source code is not provided. However, you can use the website and explore its features at the following link:  [wisify.ai](https://thefinalapp-frontend-976201422880.us-central1.run.app/auth/sign-in)
    
## Key Features
* **Customizable Summary Length:** Choose the duration and depth of the summary based on your requirements, from brief overviews to detailed analyses.  
* **Audio Summaries:** Convert long documents into audio files, perfect for on-the-go listening and multitasking.  
* **Legal Document Optimization:** Unlike generic summarization tools, Wisify.ai is finely tuned to handle the complexities and nuances of legal texts.  
* **Overcoming Token Limits:** Unlike other AI tools such as ChatGPT, Wisify.ai is not constrained by token limits, enabling the generation of long and detailed summaries.

## Technologies Used
* Front-end: React with TypeScript, built with Material UI
* Back-end: Django REST Framework
* Authentication: JWT (JSON Web Tokens)
* APIs:
  * Google Cloud Storage
  * Large Language Models (LLMs)
  * Text-to-Speech Services
* Storage: Google Cloud Storage (S3 buckets)
* Database: MySQL, running on a Google Cloud SQL Server
* Hosting: Google Cloud Run Services
* Integration Framework: LangChain for leveraging and tailoring existing LLMs to our use case

## Next Steps
* **Chat Feature:** A chat feature will be added that will utilize embeddings along with LangChain to allow users to converse with multiple documents. This is especially important for lawyers who have to pull information from multiple sources.
* **Integration with Cloud Storage Services:** Integration with Google Drive and Dropbox will be implemented to streamline the process of uploading and managing documents within the platform.
Experience the future of legal document summarization with Wisify.ai—where efficiency meets precision, tailored exclusively for the legal domain.

## How to / Usage
#### **Sign Up:**  
Sign up using your email address and a password.
This will bring you to the home page dashboard where you can see the latest recordings and documents that are being worked on.
#### **Navigating to Documents Page:**
Click on the tab on the side navigation bar to go to the documents page.
Here you can upload documents and view the documents that have been uploaded in the documents table.
#### **Uploading Documents:**  
When uploading documents, you can assign them to specific clients and specify the type of document.
You can click on a document to view it, and you can also click to summarize a document.
#### **Summarizing Documents:**
Clicking to summarize a document will pop up a modal that tells you the range for which the document can be summarized.
If the document is too short, it will notify you that summarization is not possible.
After selecting a time range on the slider, a loading screen will appear until the audio file is created.
#### **Accessing Recordings:**
The created audio file will exist in the recordings page, accessible via the side navigation.
Here you can view all the recordings created, click on a recording to pop up a modal where you can listen to the audio file and also download it.
You can also download the summary that was generated.
#### **Account Management:**
In the account tab, you can reset your password.
#### **Chat Feature:**
There is a chat tab under development; currently, it leads to an error page.

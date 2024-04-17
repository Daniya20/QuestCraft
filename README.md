#QuestCraft: Automatic Question Paper Generator
In the dynamic realm of education, where educators strive to deliver top-notch assessments and enriching learning encounters, an innovative solution emerges to streamline a crucial process – the generation of question papers.
Welcome QuestCraft, your ultimate ally in crafting insightful, varied, and meticulously structured question papers.
System Requirements:
To ensure optimal performance of the QuestCraft application, please ensure that your system meets the following minimum requirements:
Operating System: Windows 10, macOS, or Linux (Ubuntu recommended)
Processor: Intel Core i5 or equivalent
RAM: 8GB or higher
Storage: 100MB of available disk space for installation
Python Version: Python 3.8.6 or later
Please note that while the application may run on systems that do not meet these specifications, performance may be suboptimal, and certain features may not function as intended.
Executing the application:
To run the application, users are required to execute the following pip commands in the command prompt:
```
pip install django
pip install nltk
pip install transformers
pip install flashtext
pip install Pywsd
pip install summarizer
pip install fpdf
pip install openpyxl
python -m spacy download en
pip install git+https://github.com/boudinfl/pke.git
pip install torch
pip install bert-extractive-summarizer
```
MCQ Generation Procedure: The procedure encompasses preprocessing text, extracting pivotal keywords, generating concise summaries, and crafting multiple-choice questions from the processed text. It adheres to the protocol of uploading a text file, extracting its contents, and executing the necessary processing steps.
Once all the necessary dependencies are installed, the final step involves navigating to the directory where the manage.py file is located, typically on the initial page, and opening the command prompt there. Subsequently, execute the following command:
```
py manage.py runserver
```
Please note that it may take some time for nltk to download and pwd, so your patience is appreciated.
Feedback Mechanism:
We value your feedback and strive to continuously improve the QuestCraft application. If you encounter any issues, have suggestions for new features, or would like to share your experience using the application, please don't hesitate to get in touch with us.
You can provide feedback through the following channels:
Email: questcraftbot@gmail.com
Feedback Form: https://forms.gle/2B8okmtdJZPMRPL99
Your feedback is invaluable to us, and we appreciate you taking the time to share your thoughts and suggestions.
Support and Queries:
If you have any queries or require assistance with installing or using the QuestCraft application, please feel free to reach out to us via email at questcraftbot@gmail.com. 
Our support team is dedicated to assisting you and ensuring that you have a seamless experience with the application. We strive to respond to all queries and support requests promptly, so please don't hesitate to contact us if you need any help or assistance.
Thank you for choosing QuestCraft, and we look forward to hearing from you!

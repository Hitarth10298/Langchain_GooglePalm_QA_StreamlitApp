### Project Highlights

Use a real CSV file of FAQs that Codebasics company is using right now.
Their human staff will use this file to assist their course learners.
We will build an LLM based question and answer system that can reduce the workload of their human staff.
Students should be able to use this system to ask questions directly and get answers within seconds

### Installation

1. Clone the repository to your local machine using git command : git clone "https://github.com/Hitarth10298/Langchain_GooglePalm_QA_StreamlitApp.git"
2. pip install -r requirements.txt (Try to create virtual environment (venv) before running this command)
3. Acquire an API key through makersuite.google.com and put it in the .env file (  GOOGLE_API_KEY="your_api_key_here"  )


### Usage

1. Run the streamlit app (streamlit run main.py)
2. The web app will open in your browser.

 - To create a knowledebase of FAQs, click on Create Knolwedge Base button. It will take some time before knowledgebase is created so please wait
 - Once knowledge base is created you will see a directory called faiss_index in your current folder

Now you are ready to ask questions. Type your question in Question box and hit Enter


### Sample Questions

1. Do you guys provide internship and also do you offer EMI payments?
2. Do you have javascript course?
3. Should I learn power bi or tableau?
4. I've a MAC computer. Can I use powerbi on it?
5. I don't see power pivot. how can I enable it?

### Project Structure

1. main.py: The main Streamlit application script
2. langchain_helper.py: This has all the langchain code
3. requirements.txt: A list of required Python packages for the project
4. .env: Configuration file for storing your Google API key

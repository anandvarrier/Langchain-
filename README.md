# Langchain
In this repository, I have worked on small projects for learning purposes. Feel free to explore like I am doing. 
Tools&Chains01: Here, I have developed an interface using Stream Lit UI. 
Observation: 
  1) It behaves like a chatbot. 
  2) To run the code: on command prompt->activate the enviornment-> streamlit run filename.py->go to browser and ask any question and press submit 
  3) I have created 4 custom tools (which is similar to any function). 
  4) When the user asks a question related to the tools we have written. The application makes use of the tools that we have provided and gives us our answers.
  5) examples of questions that one can try out: A) what is the 10th fibonacci number in the series? B) encrpty/decrypt a 'word of your choice'. 
                                                 C) Which tools does the model use? D) Sort the 'string of your choice'.
  6) While running the application on the browser, make sure you have a minimized editor opened on the side. You will be able to view its calulations.
  7) Strangely, we can actually ask it any kind of question. It fetches from open source internet as it uses OpenAI API. 
                        
 
Custom Agents and Tools: Here, I have experimented on creating Custom Tools and Agents. 
I appreciate @insightbuilder for valuable their guidance.
Observation: 
  1) Agents
       ^
     Tools
       ^
 Functions/Class
 
  2) We can customize the behaviour of Agents by changing parameters.
  3) The response that we want depends upon 2 main factors
      i) the way we write our functions ultimately our tools
      ii) the way we give our prompts

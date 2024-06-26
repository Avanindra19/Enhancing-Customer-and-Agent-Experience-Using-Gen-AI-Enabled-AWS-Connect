# Enhancing-Customer-and-Agent-Experience-Using-Gen-AI-Enabled-AWS-Connect


#Project Summary

Why did we choose this problem?


-> Contact centers encounter several critical challenges: long wait times leading to customer dissatisfaction and potential churn, limited service hours restricting interaction, impersonal service impacting loyalty, high operational costs, scalability issues, inefficient data handling, and time-consuming post-contact processing.

How do we approach to provide a difference?


-> The integration of Gen AI addresses these issues by reducing wait times, enabling 24/7 service, personalizing interactions, cutting operational costs, improving scalability, optimizing data analysis, and automating post-contact tasks.

<img width="623" alt="Screenshot 2024-04-07 at 10 53 52 PM" src="https://github.com/Avanindra19/Enhancing-Customer-and-Agent-Experience-Using-Gen-AI-Enabled-AWS-Connect/assets/55397511/ddbe57eb-dfaa-4ce3-84d5-ccd2ddb0832b">



Moreover,Mckinsey has reported that Gen AI offers transformative benefits for contact centers in the following ways : Enhanced productivity: Studies show a potential 14% increase in issue resolution per hour and a 9% reduction in handling time. Improved service quality: Less-experienced agents benefit most, while overall productivity and quality rise. Customer self-service: Up to 50% automation of customer inquiries is feasible through AI-powered chatbots. Speedier responses: Real-time AI assistance reduces response times for sales representatives. Increased sales and coaching: AI-driven insights aid in personalized sales strategies and agent coaching.

Implementing Gen AI could potentially save contact centers 30 to 45% of current operational costs, focusing solely on direct productivity gains without considering the potential boost in customer satisfaction from a more tailored experience.


<img width="392" alt="Screenshot 2024-04-07 at 10 53 59 PM" src="https://github.com/Avanindra19/Enhancing-Customer-and-Agent-Experience-Using-Gen-AI-Enabled-AWS-Connect/assets/55397511/cdd5272c-a090-4711-a14b-45e522d110bf">


Source:https://www.mckinsey.com/capabilities/mckinsey-digital/our-insights/the-economic-potential-of-generative-AI-the-next-productivity-frontier#business- value

What is the difference that we have created through our solution?


<img width="606" alt="Screenshot 2024-04-07 at 10 54 04 PM" src="https://github.com/Avanindra19/Enhancing-Customer-and-Agent-Experience-Using-Gen-AI-Enabled-AWS-Connect/assets/55397511/dbd9f644-f065-4b64-82c1-d73da4f8a170">



-> To enhance both customer’s and agent’s experience using GenAI ,we made the below solution.This solution utilizes AWS services such as Connect,Bedrock,Kendra ,S3,Lambda and Lex.The Customer makes the call to the system, and the call is handled first by the lex chatbot and then, if required ,by the human agent. The following two are the main integrations for our solution:

Lex Chatbot Integration: Our Lex chatbot seamlessly integrates with AWS Bedrock housing the LLM model. Leveraging AWS Kendra, the chatbot scours policy documents stored in S3, swiftly retrieving the most pertinent document matching the customer's query. Kendra's output fuels the LLM model, generating personalized responses tailored to each customer query.

AWS Wisdom Integration: For customers preferring human interaction, our system seamlessly directs their call to a human agent via AWS Connect. Additionally, by integrating AWS Connect with Wisdom, our agents receive real-time document recommendations based on the ongoing customer query. Wisdom offers a ranked list of relevant documents, optimizing agent support and improving both customer experiences and agent productivity.

Our comprehensive integration of AI-driven models, AWS services, and real-time agent support mechanisms ensures a streamlined and personalized experience for both customers and agents, setting a new standard in customer service delivery.

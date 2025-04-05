# iManage-Traffic-App

Problem:
Urban traffic congestion leads to significant time loss, pollution, and fuel consumption. Static
traffic signals and traditional rule-based systems fail to optimize traffic flow dynamically.

Challenge:
Develop a multi-agent system where AI-powered traffic lights, smart vehicles, and drones
collaborate to manage real-time traffic, reducing congestion and improving emergency vehicle
response times.


Solution:
Multi AI agent system that perform real time predictive analytics and machine learning on where accident are likely to happen. Base on result per a specific timeframe, disaster response team will receive a report and then from the report, they will  plan accordingly on how to response. For example, tow vehicle will be nearby, fire department will plan accordingly and police will be nearby in zone that are considered at risk for an accident.


Solution Architecture
<img width="957" alt="Screenshot 2025-04-05 at 11 49 00" src="https://github.com/user-attachments/assets/1d07a7f6-65c7-48fd-8409-85794b33bf3d" />

Database: Have a database that record all the accident that happen in the past as well as accident that is happen now
Data Analytic Agent: Provide real time data analytic as traffic data are incoming and then will send analytic report to reporting agent.
Predictive Ai Agent: Will receive data from the analytic Ai Agent and build a machine learning model that predict where accident are likely to happen. Prediction will be send to reporting Ai Agent.
Reporting Ai Agent will send report to disaster response user interface.
Disaster response interface: customer facing application 

Database

Front-end
--React Application that is a model friendly and Desktop friendly. App that adapt to all types of screen sizes
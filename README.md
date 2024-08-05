# Agentic Automated Event Planning
This project demonstrates the use of CrewAI's multi-agent system to manage various aspects of event planning and execution. Using CrewAI in a Google Colab environment, we have three specialized agents—Venue Coordinator, Logistics Manager, and Marketing and Communications Agent—working together to plan a Tech Innovation Conference in Mumbai.

## Overview
The project employs the following agents, each with distinct roles and goals:

1. **Venue Coordinator**: Identifies and books an appropriate venue based on event requirements.
2. **Logistics Manager**: Manages all logistics for the event, including catering and equipment.
3. **Marketing and Communications Agent**: Effectively markets the event and communicates with participants.

## Installation
To run this project, you'll need to install the required packages. These packages include CrewAI, crewai_tools, langchain_community, and langchain_groq. Installation can be done using pip.

## Environment Setup
API keys are necessary for accessing external services. The keys for GROQ and SERPER need to be set up in the environment variables using os.environ. These keys will be used by the agents to perform their tasks effectively.

## Agents and Tasks
### Venue Coordinator
The Venue Coordinator is responsible for finding and booking a suitable venue for the event. This agent uses tools for web scraping and search to identify venues that meet the event's requirements, such as location, capacity, and budget. The agent's goal is to secure a venue that aligns with the event's theme and logistical needs.

### Logistics Manager
The Logistics Manager handles all logistical aspects of the event, including arranging catering services and equipment setup. This agent ensures that all necessary resources are in place and that everything runs smoothly on the event day. The Logistics Manager uses the same web scraping and search tools to coordinate these arrangements.

### Marketing and Communications Agent
The Marketing and Communications Agent is tasked with promoting the event and engaging with potential participants. This agent creates marketing strategies, crafts messages, and uses various channels to maximize event exposure. The goal is to ensure high attendance and active participation.

## Event Management Crew
The CrewAI system combines these agents into a cohesive team, referred to as a "crew." Each agent is assigned specific tasks that contribute to the overall success of the event. Tasks include finding a venue, coordinating logistics, and marketing the event. The crew works collaboratively to achieve the project's goals.

## Event Details
The details for the Tech Innovation Conference include the event topic, description, city, tentative date, expected participants, budget, and venue type. These details guide the agents in performing their tasks and making decisions that align with the event's objectives.

## Example Output
The output from the Venue Coordinator agent is stored in a JSON file, containing details about the selected venue. This information includes the venue name, address, capacity, and booking status.

## Usage
To use this project, run the Colab notebook, which initializes the agents and assigns them their respective tasks. The agents will perform their duties, and the results will be saved in output files. Review these files to see the details of the venue, logistics arrangements, and marketing activities.

## License
This project is licensed under the MIT License.


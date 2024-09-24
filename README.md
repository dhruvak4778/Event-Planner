# Event-Planner
**Event Planner**
Event Planner is a chatbot specifically designed to assist users in organizing and managing events. By integrating scheduling tools, guest management, and venue recommendations into a large language model (LLM), this chatbot provides personalized event planning advice, timeline management, and coordination of event logistics.

**Features**
Interactive chatbot interface for event planning inquiries.
Scheduling, guest list management, and venue recommendations.
Personalized event timelines and task reminders.
Integration with calendar apps and online event management tools.
Automated invitations and RSVP tracking.
Installation
To get started with Event Planner, follow these steps:

**Clone the repository:**
git clone https://github.com/dhruvak4778/event-planner.git
cd EventPlanner

Install the Gaia Node by running the following command:
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash

Run the following command to update your config.json to run with a small language model:
gaianet init --config https://raw.githubusercontent.com/harishkotra/Gaia-8G/refs/heads/main/config_8g.json

**Start the node:**
gaianet start

**How to Use**
Open your web browser and navigate to the generated link.
Start interacting with the chatbot by typing your event planning needs (e.g., "Plan a birthday party for 20 people," "Send invites for the office meeting," or "Find a venue for a wedding in New York").

**License**
This project is licensed under the MIT License. See the LICENSE file for details.


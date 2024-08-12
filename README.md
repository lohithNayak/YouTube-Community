YouTube Community Website with Weather Widget
This project is a website dedicated to the YouTube community, highlighting its features and providing users with valuable resources. Additionally, the website includes a weather widget that displays the current weather, temperature, and time for a specific location (Bengaluru).

Prerequisites
To run this project, you'll need the following installed on your machine:

1.  Visual Studio Code (VS Code): A powerful and popular code editor.
2. Live Server Extension for VS Code: A VS Code extension that allows you to launch a local development server with 	live reload.

How to Run the Project
Follow these steps to run the website locally:

1)  Clone the Repository:
	https://github.com/lohithNayak/YouTube-Community.git

2) Open a terminal and run the following command to clone the repository:
git clone https://github.com/lohithNayak/YouTube-Community.git

3) Open the Project in VS Code:

Open VS Code.
Navigate to File > Open Folder... and select the folder where you cloned the repository.

4) Install Live Server Extension:
a. If you haven't already installed the Live Server extension, you can do so by:
b. Go to the Extensions view by clicking the Extensions icon in the Sidebar.
c. Search for "Live Server" and click "Install."

5) Run the Website:
After opening the project in VS Code, right-click on the index.html file in the Explorer view and select "Open with Live Server."
Your default browser will open, and the website will be running locally. You should see the YouTube community content along with the weather widget displaying the current weather and time for Bengaluru.
Make Changes and See Live Updates:

As you make changes to the HTML, CSS, or JavaScript files, Live Server will automatically refresh the browser to reflect the changes.
API Key Configuration for Weather Widget
The weather widget uses an API key from WeatherAPI.com. To use your own API key:

Visit WeatherAPI.com to get a free API key.
Replace the apiKey variable in the index.html file with your API key:

const apiKey = 'your-api-key-here'; (line no. 644)

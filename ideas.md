## Miru
- A simple diagramming tool to replace the draw.io core that we currently use
- moving from JavaScript API calls, to natively querying data from the Laravel PHP backend
- Developing a data collector and database, so we are not limited to only using IXP Manager
- Developing an interface for us to retrieve live results from testing and checking logs on our system

## Cerberus
- Building a monitoring dashboard to better track the traffic that we see on our network
- Add notification capabilities, so we can notify users when changes are detected in the network


# Idea Write Ups

## Diagram Creation

Project: Simplifying Topology Diagram Creation

Description: Create a web-based diagramming tool to replace the current draw.io core that we use. The tool should be user-friendly and easy to use, allowing users to create network topology diagrams with minimal effort. It should provide basic diagramming shapes and a simple interface for connecting these shapes.

Skills required: Web development, JavaScript, HTML and CSS. Knowledge of diagramming libraries like d3.js or mxGraph would be preferred

## JavaScript

Project: Optimising Data Retrieval for Miru

Description: Develop a system to optimise data retrieval for Miru. The current setup involves making API calls from the frontend JavaScript to retrieve data from the backend. This approach can become slow and inefficient as the number of API calls increases. The project involves replacing the current API calls with a system that allows for native data querying from the Laravel backend. This will eliminate the need for API calls and improve the speed and efficiency of data retrieval.

Skills required: PHP, Laravel, SQL, and experience with optimising database queries and data retrieval methods.

## Simplified data collector

Project: Building an Independent Data Collection and Management System

Description: Develop a standalone data collection and management system that can be used independently of IXP Manager. The system should be able to collect data from a variety of sources, including network devices and other systems, and store it in a database. The database should be easy to query and visualise, allowing users to analyse and make sense of the collected data. The system should also be flexible and scalable, allowing for the addition of new data sources as needed.

Skills required: Python, SQL, data collection and management, and experience with database management systems like MySQL or PostgreSQL.


## Streamline System Testing

Project: Streamlining System Testing and Log Analysis

Description: Develop a user-friendly interface for retrieving live results from system testing and analysing logs. The interface should be able to retrieve test results and log data in real-time, and display it in a clear and concise manner. It should also provide tools for filtering, sorting, and visualising the data, making it easier for users to understand and analyse the results. The interface should be accessible from any web browser, allowing users to monitor the system from any location.

Skills required: Web development, JavaScript, HTML, CSS, and experience with data visualisation libraries like D3.js or Chart.js.

## Cerberus Dashboard

Project: Visualising OpenFlow Network Traffic with Grafana

Description: Develop a Grafana dashboard for tracking the traffic on an OpenFlow network. The dashboard should provide real-time information about the network's performance, including traffic volume, bandwidth utilisation, and other key metrics. It should use Grafana's powerful visualisation capabilities with Prometheus to provide meaningful insights into the network's performance. The dashboard should be scalable and flexible, allowing for the addition of new metrics and visualisations as needed.

Skills required: Python and familiarity with Grafana and Prometheus and its data source plugins. Optionally, knowledge and experience with OpenFlow networks would be beneficial.


## Network Notifications

Project: Improving Network Awareness with Network notifications

Description: Develop a notification system for Cerberus, our OpenFlow network controller. The system should be able to detect changes in the network, such as changes in port status or bandwidth utilisation, and notify users through various channels, such as email. The system should be flexible and customisable, allowing users to choose which changes they would like to be notified about, and how they would like to be notified.

Skills required: Python. Optionally, familiarity with OpenFlow networks and network controllers, as well as experience with developing notification systems and APIs for sending notifications through various channels.

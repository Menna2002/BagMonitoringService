# Bag Monitoring Service

## Overview
### `Application Developed using the Master of Things platform`
SmartBag Tracker is an IoT handbag/backpack monitoring application designed to help end users track their handbag's location and status (open or closed) in real-time. 
The system uses IoT devices equipped with GPS and light intensity sensors to provide comprehensive monitoring and alert features.

## Features
- **Real-time Tracking**: Monitor the handbag's location using GPS sensors.
- **Status Monitoring**: Determine if the bag is opened or closed based on light intensity.
- **User Authentication**: End users can log in with their Bag ID and password to track their bag.
- **Customer Service Portal**: Allows customer service agents to register new bags, define sensors, and manage bag owner information.
- **Map Integration**: Displays the bag's location on a map with customized markers.
- **Historical Data**: Access historical location and status information.
- **Email Alerts**: Sends email notifications to users if the bag is opened or moves outside a predefined geofenced area.

## Technical Implementation
1. **Sensors**: Utilizes mot IoT Kit sensors for GPS and light intensity.
2. **Virtual Sensors**: Each bag is represented by a virtual sensor ID, which tracks GPS location and light intensity.
3. **Template Page**: Built a template page containing common components/plugins for use across all application pages.
4. **Map Plugin**: Integrated a map plugin to display bag locations with customized marker icons.

## Project Demo (youtube link)
[![Bag Monitoring Service](https://img.youtube.com/vi/yMDzGy8Ukks/0.jpg)](https://www.youtube.com/watch?v=yMDzGy8Ukks&list=PLATvI0lqsAdNWEIsycNPKyvmuxMzmgL6L&autoplay=1)

## Conclusion
SmartBag Tracker provides a comprehensive solution for monitoring and tracking handbags, ensuring users can easily locate their bags and receive alerts for any unauthorized access or movement beyond a safe zone.

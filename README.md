# n8n-gardening-automations
Gardening automations in n8n

## Watering Scheduler

A n8n scheduler that reminds you to water the plants in the garden when it doesn't rain for two days in a row.
It creates events named "Water the plants" in your Google Calendar for the next week when the weather forecats indicates it's not going to rain for two days in a row. The events are removed/adjusted if the weather forecast changes. 

### Requirements

Requires credentials for accessing Google Calendar and credentials for openweathermap.org (free tier). 

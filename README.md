# Predictive Analysis for Manufacturing Operations

## Description
This API predicts machine downtime based on manufacturing data such as temperature and run-time.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/repo-name.git
   cd repo-name

## API Testing Instructions

# Testing API Locally

 Using Postman Web

1. Go to Postman Web and log in.

2. Create a POST request to:

```bash
http://127.0.0.1:5000/predict
```
3. In the Body section, select raw and choose JSON format.

4. Add the following test data in json format :
```bash 
{
   "Temperature": 80,
   "Run_Time": 120
}
```
5.Click Send and check the response.

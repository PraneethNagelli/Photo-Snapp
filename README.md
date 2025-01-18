# Photo Snapp Application

## Overview  
Photo Snapp is a Python-based application built using Flask that allows users to capture photos directly from their webcam.  

## Getting Started  

### Running the Application Locally  
To start the application, run the following command:  
```bash
docker-compose up photo-snapp
```  

### Restarting the Application  
If you need to restart the application, execute the command below:  
```bash
docker-compose rm photo-snapp -f && docker image rm -f photo-snapp-photo-snapp && docker-compose up photo-snapp
```  

### Accessing the Application  
Once the application is running, you can access it via:  
[http://127.0.0.1:5000](http://127.0.0.1:5000)

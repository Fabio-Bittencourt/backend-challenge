# Woliver - Backend Code Challenge

## Description

Welcome to Woliver's backend code challenge! The goal of this challenge is to create a service to provide listings data for a web application from a real estate company, following the **Acceptance criteria**. The backend of application (see **System Architecture**) contains a listings service, which has:
- XML parser: Parses data from the real estate's properties from an XML file
- Database: Stores the data parsed from the XML
- REST API: Provides an interface to retrieve the data needed for the web application

The backend should be writting using Python language, feel comfortable to chose the remaining set of technology you are familiar with to create the service. Elaborate briefly the architectural decisions, design patterns and frameworks you used on your solution.


## Resources

#### System Architecture
![image](https://user-images.githubusercontent.com/10841710/143500271-a7bd35e5-5823-42b7-9be6-5c3c3cf06ffe.png)

#### XML
https://content.woliver.net/assets/listings.xml


## Acceptance criteria

1. Provide clear instructions on how to run the application in development mode
2. Provide clear instructions on how the application would run in a production environment
3. Create a function to parse data from the XML from the provided **Resources**
4. Allow the listings service to store the data parsed from the XML into a database
5. Create a RESTful API allowing retrieve and list operations on the listings, based on the web application needs seen on **System Architecture** wireframe
6. Allow the web application to filter listings by City, Neighborhood, Bedrooms and Rent Price values
7. Elaborate an answer on how the database would keep the listings data always updated, given the XML is dynamic and has a daily update
8. Considering the listings service needs to scale and parse another 50 XMLs and each XML contains 10k listing pictures, how would we store all the pictures on the database given the database update strategy?


## Additional Information

- The usage of git will be taken into consideration on the evaluation
- Fork this repository to your github account to submit your code
- All the written information requested on **Acceptance criteria** should be added on a README.md file inside the repository

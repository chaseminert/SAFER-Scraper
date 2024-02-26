# FMCSA SAFER Scraper

## Project Overview
The FMCSA SAFER Scraper is a Java application designed to automate the retrieval of information for newly generated DOT numbers from the SAFER website. Tailored for Transportation Compliance Service, this tool streamlines the process of generating potential leads by efficiently scraping and processing relevant data in real-time.

## Key Features
- **Real-time Data Scraping**: Dynamically fetches data for DOT numbers generated the previous day.
- **Tracking Mechanism**: Maintains a record of the last DOT number processed, ensuring seamless operation from one day to the next.
- **Error Handling**: Robust error handling mechanisms are in place to manage instances where the JSON data may lack specific information.

## Technologies Used
- **Java**: The core programming language.
- **Unirest Library**: Utilized for making API requests and retrieving JSON data.
- **JSON Library**: Employed for parsing the JSON data returned by the API.
- **Maven**: Facilitates dependency management through the `pom.xml` file.

## Challenges Overcome

### Dependency Management
Initially, managing dependencies in Java proved to be a challenge. I relied on manual jar management, which became cumbersome as the project grew. Learning how to use Maven improved efficiency and reliability in handling dependencies. By adopting Maven and creating a `pom.xml` file, I streamlined dependency management, ensuring consistent builds and simplified project maintenance.

### API Usage
Working with APIs presented its own set of challenges, particularly in data retrieval and manipulation. Mastering the Unirest library for making HTTP requests and processing JSON data proved to be difficult in a language like Java. Through thorough documentation review and hands-on practice, I gained proficiency in leveraging APIs to enhance data handling capabilities. Additionally, familiarity with the JSON library facilitated seamless parsing of JSON responses, enabling efficient extraction of relevant data.

## Overall Impact And Significance
This project has generated thousands of leads for Transportation Compliance Service, resulting in over $40,000 in sales revenue. Its strategic implementation has played a pivotal role in driving business growth and achieving significant outcomes for the organization.

## Installation and Usage
Due to the proprietary nature of this project and its specific application within Transportation Compliance Service, detailed setup and usage instructions are not publicly available. This project is designed to operate within a specific infrastructure and requires appropriate access and permissions.

## Contribution
This project is closed to external contributions. It has been developed specifically for, and is maintained by, Transportation Compliance Service.

## License
This project is proprietary and confidential. Unauthorized copying of the files, via any medium, is strictly prohibited without express permission.

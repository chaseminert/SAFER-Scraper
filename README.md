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
1. **Dependency Management**: Transition from manual jar management to Maven for efficient dependency handling.
2. **API Usage**: Mastered the use of Unirest for API communication and the JSON library for parsing, enhancing data handling capabilities.

## Screenshots/Demo
TBD - Demonstrations of the scraper in action will be provided.

## Installation and Usage
Due to the proprietary nature of this project and its specific application within Transportation Compliance Service, detailed setup and usage instructions are not publicly available. This project is designed to operate within a specific infrastructure and requires appropriate access and permissions.

## Contribution
This project is closed to external contributions. It has been developed specifically for, and is maintained by, Transportation Compliance Service.

## License
This project is proprietary and confidential. Unauthorized copying of the files, via any medium, is strictly prohibited without express permission.

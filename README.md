# Canadian Post-Secondary Institutions Data Visualization
This web application is designed to visualize data on Canadian post-secondary institutions, utilizing the official dataset from the Canadian government. The app allows users to explore institutions based on key attributes such as institution name, academic level, and program length. By providing an intuitive and interactive interface, this tool helps prospective students navigate through various options, enabling them to make informed decisions when selecting an institution and program that best aligns with their academic and career goals. The dataset ensures accuracy and up-to-date information, making it a reliable resource for anyone looking to explore post-secondary education options in Canada.


<img width="734" alt="image" src="https://github.com/user-attachments/assets/7fbba119-45cc-41c2-ab40-ee7c97871852" />


<img width="732" alt="image" src="https://github.com/user-attachments/assets/c704f556-b35b-4996-906b-658c2f78cd40" />


## Project Overview
This interactive web application provides comprehensive data visualization for Canadian post-secondary institutions and programs. The project aims to make educational data more accessible and transparent for stakeholders in the Canadian education sector.

🔗 **Live Demo:** [https://fransiscustobias.com/mm802](https://fransiscustobias.com/mm802)

## Dataset
This project utilizes the dataset of Canadian post-secondary institutions, sourced from the official Government of Canada website. The dataset provides comprehensive information on recognized institutions across Canada, including their names, locations, and types. By leveraging this data, the project aims to visualize trends and insights in the Canadian post-secondary education system, enabling users to explore and understand key patterns and distributions of institutions throughout the country. The data ensures accuracy and reliability, reflecting the most up-to-date information on accredited institutions eligible for student loans and grants.

**Data Source:** [Government of Canada Open Data - Post-Secondary Institutions](https://open.canada.ca/data/en/dataset/ab36a4ab-9b69-49b1-8be6-6faa3f0d0c67)

<img width="881" alt="image" src="https://github.com/user-attachments/assets/2104aba3-6d0c-44ee-8e6b-ce105be1de9e" />

## Features
- Interactive data visualizations powered by D3.js and Plotly.js
- Dynamic dropdown menus for intuitive data exploration
- Seamless navigation between different visualization pages
- Comprehensive institutional and program data
- User-friendly interface for educational decision-making

## Technologies Used
- **Frontend:**
  - HTML5
  - CSS3
  - JavaScript
  - D3.js
  - Plotly.js
  
- **Backend:**
  - PHP
  - XAMPP (Apache, MySQL/MariaDB)

## Development Environment
- Visual Studio Code/Sublime Text/PHPStorm
- XAMPP local server environment
- Modern web browsers (Chrome, Firefox, Edge) for testing

## Getting Started
1. Clone this repository
2. Install XAMPP on your local machine
3. Place the project files in your XAMPP htdocs directory
4. Start Apache and MySQL services in XAMPP
5. Access the application through your local server

## Project Structure
- `index.html` - Main landing page with initial visualizations
- `secondpage.html` - Secondary visualization page
- Additional assets and resources organized in respective directories

## Browser Compatibility
Tested and optimized for:
- Google Chrome
- Mozilla Firefox
- Microsoft Edge

## Contributing
Contributions, issues, and feature requests are welcome. Feel free to check issues page if you want to contribute.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For any inquiries about this project, please visit [https://fransiscustobias.com/mm802](https://fransiscustobias.com/mm802)
"""

# Write to README.md
with open('README.md', 'w') as f:
    f.write(readme_content)

print("Updated README.md has been generated successfully with the dataset section!")

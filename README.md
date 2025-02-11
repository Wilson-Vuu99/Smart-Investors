# Smart Investor

## Overview
Smart Investor is a web application designed to provide a risk-free investing experience using a paper trading account. The platform allows users to simulate stock market trading with live stock data, helping them develop investment strategies without financial risk.

## Features
- **Paper Trading Account**: Users can practice trading stocks in a simulated environment.
- **Live Stock Data**: Integrated with the Yahoo Finance API to provide real-time stock prices.
- **Multi-User Support**: XAMPP-powered backend enables multiple clients to access the platform.
- **Version Control**: Git/GitHub was used to manage and merge contributions from different team members.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP, MySQL
- **API Integration**: Yahoo Finance API
- **Development & Deployment**: XAMPP
- **Version Control**: Git/GitHub

## Installation
### Prerequisites
- XAMPP installed on your system
- PHP and MySQL configured within XAMPP
- Git for version control (optional)

### Setup Instructions
1. **Clone the repository**:
   ```sh
   git clone https://github.com/your-repo/smart-investor.git
   ```
2. **Start XAMPP**:
   ```sh
   # Open XAMPP Control Panel
   # Start Apache and MySQL services
   ```
3. **Import Database**:
   ```sh
   # Open phpMyAdmin in your browser (http://localhost/phpmyadmin)
   # Create a new database (smart_investor)
   # Import the provided SQL file from the `database` folder
   ```
4. **Configure API Access**:
   ```sh
   # Obtain an API key from Yahoo Finance (if required)
   # Update the API credentials in the project files
   ```
5. **Run the Application**:
   ```sh
   # Place the project folder inside htdocs
   # Open a browser and go to http://localhost/smart-investor
   ```

## Usage
1. Register an account and log in.
2. Search for stocks and view live prices.
3. Buy and sell stocks using the paper trading feature.
4. Track portfolio performance.

## Contributing
Contributions are welcome! To contribute:
```sh
# Fork the repository
# Create a new branch (feature-branch)
# Commit your changes and push to GitHub
# Submit a pull request
```

## License
This project is licensed under the MIT License.

## Contact
For questions or collaboration, reach out via [your email or GitHub profile link].


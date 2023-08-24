# Shape-ai
# Current Weather of Any City Project

## Overview

This project provides a simple Python script to retrieve and display the current weather of any city using an API key from a weather data provider. It's a beginner-friendly project aimed at demonstrating how to make API requests, handle JSON data, and present it in a user-friendly way.

## Features

- Fetches real-time weather data for any city worldwide.
- Displays essential weather information, including temperature, humidity, wind speed, and conditions.
- Easy-to-understand Python code, suitable for beginners.
- Utilizes an API key for data retrieval.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x installed on your local machine.
- An API key from a weather data provider. You can obtain a free API key by signing up on their website.

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/current-weather-project.git
   ```

2. Navigate to the project directory:

   ```bash
   cd current-weather-project
   ```

3. Create a file named `config.py` in the project directory and add your API key as follows:

   ```python
   # config.py
   api_key = "YOUR_API_KEY_HERE"
   ```

4. Install the required Python libraries using pip:

   ```bash
   pip install requests
   ```

## Usage

To use this project, follow these steps:

1. Open your terminal and navigate to the project directory.

2. Run the script using Python:

   ```bash
   python weather.py
   ```

3. When prompted, enter the name of the city for which you want to fetch the weather.

4. The script will make an API request, retrieve the weather data, and display it in the terminal.

## Example

Here's an example of how to use this project:

```bash
python weather.py
Enter the name of the city: New York
```

The script will then display the current weather in New York, including temperature, humidity, wind speed, and conditions.

## Contributing

Contributions are welcome! If you'd like to improve this project or add new features, please fork the repository and create a pull request. Feel free to open issues for bug reports or feature requests as well.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to [Weather Data Provider](https://weather-provider.com) for providing the weather data API.

Happy coding!

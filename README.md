# Weather Blazor App

A simple weather application built with Blazor that displays weather information using the OpenWeatherMap API.

## Features

- Real-time weather data display
- Integration with OpenWeatherMap API
- Environment variable configuration for secure API key management

## Prerequisites

- .NET 8.0 SDK or later
- An OpenWeatherMap API key (get one at [OpenWeatherMap](https://openweathermap.org/api))

## Setup

1. Clone the repository:

```bash
git clone https://github.com/your-username/weather-blazor.git
```

2. Navigate to the project directory:

```bash
cd weather-blazor
```

3. Run the application:

```bash
dotnet run
```

The application will be available at `https://localhost:xxxx` (port number will be displayed in the console).

## Environment Variables

The application uses the following environment variables:

- `OPENWEATHERMAP_API_KEY`: Your OpenWeatherMap API key

## Project Structure

- `Components/Pages/Weather.razor`: Main weather display component
- `Program.cs`: Application entry point and configuration
- `.env`: Environment variables (not tracked in git)
- `.env.example`: Example environment variable template

## Technologies Used

- Blazor Server
- .NET 8.0
- dotenv.net (for environment variable management)
- OpenWeatherMap API

## Acknowledgments

- OpenWeatherMap for providing the weather data API
- Blazor framework documentation
- dotenv.net package
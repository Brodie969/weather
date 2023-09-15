# brodie969/weather

A simple weather app I made using the API on https://www.weatherapi.com 

# How To Run Locally:

1. Get your free API Key from [WeatherAPI](https://www.weatherapi.com)

2. Clone this repo

[Download the .zip](https://github.com/brodie969/weather/archive/refs/heads/main.zip)

Or Use Git:
```bash
git clone https://github.com/brodie969/weather/
```

3. Create a file called `secrets.js`.

4. Place the URL, along with your key and city in `secrets.js` like this:

```javascript
export const API_KEY = 'http://api.weatherapi.com/v1/current.json?key=123456789&q=City';
```

5. Start a local development server with your preferred method

6. Go to localhost in your browser, and now your local weather is there!

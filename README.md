# Weather App using React JS

This is a simple and responsive **Weather App** built with **React JS**. It fetches real-time weather data from the [OpenWeatherMap API](https://openweathermap.org/api) and displays key weather metrics such as **temperature**, **humidity**, **wind speed**, and **current conditions** based on the city entered by the user.

## Features

-  Search weather by **city, state, or country**
-  Displays **temperature**, **humidity**, **wind speed**, and **weather condition**
-  Uses **OpenWeatherMap API** for real-time weather data
-  Dynamic weather icons based on current weather conditions
-  Default weather for **London** on initial load
-  Fast and responsive UI with clean design

## Tech Stack

- React JS
- CSS
- OpenWeatherMap API
- Vite

## Results

![image](https://github.com/user-attachments/assets/88935452-b6b9-44be-a18b-f7b9cdb923ed)
![image](https://github.com/user-attachments/assets/f27f1c16-260d-4a91-b68d-809db30965f4)
![image](https://github.com/user-attachments/assets/2f38b94f-c0f0-4767-a145-8f44cb103a3b)
![image](https://github.com/user-attachments/assets/230d25fd-f1cf-40cc-89d4-fc113e68a11c)

##  How It Works

- `useRef()` is used to access the search input field without re-rendering the component.
- `useEffect()` runs once on initial render to fetch the default weather data for **London**.
- `fetch()` calls the **OpenWeatherMap API** using the city name and retrieves weather data in **metric units**.
- The `icon` value from the API response is matched to a local weather icon from the `assets` folder.
- The component uses conditional rendering to show the weather data only when it is available.
  
## How to run
    
1. Clone the repository:
    ```bash
   git clone https://github.com/your-username/weather-app.git
   cd weather-app/
   ```

2. Install Dependencies
    ```bash
    npm install
    ```

3. Add your .env file with the API key.
   
4. Start the development server:
    ```bash
    npm run dev
    npm run build
    ```

<h1>Visual Crossing Weather App</h1>

<p>This Android app provides weather data for a specified location, including current weather, hourly forecasts (48 hours), and daily forecasts (15 days). The app utilizes the <a href="https://www.visualcrossing.com/">Visual Crossing Weather API</a> to fetch weather data. It is built using <strong>Android Studio</strong> and <strong>Java</strong>.</p>

<h2>Features</h2>
<ul>
  <li>Displays current weather, hourly forecasts (48 hours), and daily forecasts (15 days) for a selected location.</li>
  <li>Two activities: 
    <ul>
      <li><strong>Home weather screen</strong> - Displays current weather and hourly forecast, with an alternate layout for landscape mode.</li>
      <li><strong>Daily forecast screen</strong> - Displays the 15-day daily forecast, with a single layout for both portrait and landscape modes.</li>
    </ul>
  </li>
  <li>Toggle units between imperial (°F) and metric (°C) via the options menu.</li>
  <li>Change location using the location icon in the options menu.</li>
  <li>Uses RecyclerView for displaying lists of hourly and daily forecasts.</li>
  <li>Handles JSON data and time conversion for the forecasts.</li>
  <li>Option to view detailed weather data by tapping on a forecast entry.</li>
</ul>

<h2>Technologies Used</h2>
<ul>
  <li><strong>Android Studio</strong> - Development environment.</li>
  <li><strong>Java</strong> - Programming language.</li>
  <li><strong>Visual Crossing Weather API</strong> - For fetching weather data.</li>
  <li><strong>RecyclerView</strong> - For displaying weather data lists (hourly and daily forecasts).</li>
  <li><strong>Android Volley</strong> - For API requests and handling JSON responses.</li>
  <li><strong>Dialogs</strong> - For alerts and weather details.</li>
  <li><strong>Time conversion</strong> - For handling and displaying time-related data.</li>
  <li><strong>Option-Menus</strong> - For user interactions such as toggling units and changing location.</li>
</ul>

<h2>Setup and Installation</h2>
<ol>
  <li>Clone the repository:
    <pre><code>git clone https://github.com/RikGanguli/Android-Weather-Application.git</code></pre>
  </li>
  <li>Open the project in Android Studio.</li>
  <li>Ensure you have the required dependencies in your <code>build.gradle</code> file (e.g., Android Volley, RecyclerView, etc.).</li>
  <li>Add the following permissions to your AndroidManifest.xml:
    <pre><code>&lt;uses-permission android:name="android.permission.INTERNET" /&gt;</code></pre>
  </li>
  <li>Get an API key from <a href="https://www.visualcrossing.com/sign-up">Visual Crossing Weather API</a> by signing up for a free account.</li>
  <li>Insert your API key into MainActivity.java.</li>
  <li>Run the app on an Android device or emulator.</li>
</ol>

<h2>API Setup</h2>
<ol>
  <li>Sign up for a free account on the <a href="https://www.visualcrossing.com/">Visual Crossing website</a>.</li>
  <li>Obtain your API key from the account page under the “Key” label in the “Your Details” section.</li>
  <li>Add your API key in MainActivity.java.</li>
</ol>

<h2>Usage</h2>
<ul>
  <li>On launch, the app displays the current weather and hourly forecast for the default location.</li>
  <li>Tap the location icon in the options menu to change the weather location.</li>
  <li>Toggle between °C and °F in the options menu by tapping the temperature unit icon.</li>
  <li>Tap the calendar icon to view the 15-day daily forecast.</li>
  <li>Swipe through the weather data using the RecyclerView.</li>
</ul>

<h2>Screenshots</h2>
<p></p>

<h2>Credits</h2>
<p>Developed by Rik Ganguli Biswas</p>
<p>Powered by <a href="https://www.visualcrossing.com/">Visual Crossing Weather API</a></p>

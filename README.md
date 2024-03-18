
<img src="https://media.giphy.com/media/ZVik7pBtu9dNS/giphy.gif" alt="Fun GIF">
    <p>This repository contains the source code for a Know Your Customer (KYC) website. The KYC website is a platform designed to facilitate businesses in performing identity verification on their customers. It offers various features including capturing live photographs, verifying basic details such as name, date of birth, address, PAN card, and Aadhaar card, providing conversational form guidance, and supporting multiple languages.</p>

<h3>Tech Stack Used</h3>
<ul>
        <li>Node.JS</li>
        <li>Express.JS</li>
        <li>EJS</li>
        <li>MongoDB</li>
        <li>REST API's</li>
    <li>Open CV</li>
    </ul>

<h2>Features</h2>
    <ul>
        <li><strong>Live Photograph Capture:</strong> Utilizes JavaScript audio and video tags to capture a user's live photograph, which is then stored on the cloud platform powered by Cloudinary.</li>
        <li><strong>Basic Details Verification:</strong> Stores and verifies basic details like name, date of birth, address, PAN card, and Aadhaar card which are verified using using APIs and various npm packages.</li>
        <li><strong>Conversational Form:</strong> Provides a conversational audio interface that guides users on how to fill the form effectively.</li>
        <li><strong>Multilingual Support:</strong> Supports over 100 languages using internationalization powered by Google APIs. Future plans include adding internationalization using AJAX.</li>
        <li><strong>Database Handling:</strong> Utilizes MongoDB as the NoSQL database for storing user data.</li>
    </ul>

<h2>Setup</h2>
    <ol>
        <li>Clone the repository:</li>
        <pre><code>git clone https://github.com/your-username/kyc-website.git</code></pre>
        <li>Install dependencies:</li>
        <pre><code>npm install</code></pre>
        <li>Configure Cloudinary API keys in <code>config.js</code>:</li>
        <pre><code>module.exports = {
    cloudinary: {
        cloudName: 'your-cloud-name',
        apiKey: 'your-api-key',
        apiSecret: 'your-api-secret'
    },
    // Add other configuration variables as needed
};</code></pre>
        <li>Configure MongoDB connection string in <code>config.js</code>:</li>
        <pre><code>module.exports = {
    mongodb: {
        connectionString: 'your-mongodb-connection-string'
    },
    // Add other configuration variables as needed
};</code></pre>
        <li>Run the application:</li>
        <pre><code>npm start</code></pre>
    </ol>

<h2>Usage</h2>
    <ul>
        <li>Visit the website and follow the instructions for capturing a live photograph and filling out the KYC form.</li>
        <li>Once the form is submitted, the provided details will be verified using APIs and stored in the MongoDB database.</li>
    </ul>



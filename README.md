<h1>QR Code Generator</h1>

<p>This Node.js application allows you to input a URL and generates a corresponding QR code image. Additionally, the entered URL is saved to a text file. The project leverages the <code>inquirer</code> package for user input, <code>qr-image</code> for generating the QR code, and Node's native <code>fs</code> module for file handling.</p>

<h2>Features</h2>
<ul>
    <li><strong>User Input</strong>: Prompts the user to enter a URL.</li>
    <li><strong>QR Code Generation</strong>: Converts the entered URL into a QR code image.</li>
    <li><strong>File Creation</strong>: Saves the QR code as an image file (<code>qr_img.png</code>) and the URL as text in <code>URL.txt</code>.</li>
</ul>

<h2>Getting Started</h2>

<h3>Prerequisites</h3>
<p>Ensure you have Node.js installed. If not, download and install it from the <a href="https://nodejs.org/" target="_blank">official Node.js website</a>.</p>

<h3>Installation</h3>

<p><strong>Clone the Repository:</strong></p>
<pre><code>git clone https://github.com/pranav7368/QRCode_generator.git</code></pre>

<p><strong>Navigate to the Project Directory:</strong></p>
<pre><code>cd qr-code-generator</code></pre>

<p><strong>Install Dependencies:</strong></p>
<pre><code>npm install</code></pre>
<p>This will install the necessary npm packages listed in the <code>package.json</code> file:</p>
<ul>
    <li><code>inquirer</code>: For interactive command-line prompts.</li>
    <li><code>qr-image</code>: For generating QR code images.</li>
</ul>

<h2>Usage</h2>

<p><strong>Run the Application:</strong></p>
<pre><code>node index.js</code></pre>

<p><strong>Enter a URL:</strong> You will be prompted to enter a URL when the application runs:</p>
<pre><code>? Type in your URL:</code></pre>

<p><strong>Output:</strong></p>
<ul>
    <li>The application generates a QR code image and saves it as <code>qr_img.png</code>.</li>
    <li>The entered URL is saved to a text file named <code>URL.txt</code>.</li>
    <li>A success message is displayed in the console: <code>The file has been saved!</code>.</li>
</ul>

<h2>Project Structure</h2>
<pre><code>qr-code-generator/
├── node_modules/
├── index.js
├── package.json
└── README.md</code></pre>

<h2>Dependencies</h2>
<ul>
    <li><code>inquirer</code>: ^9.0.0</li>
    <li><code>qr-image</code>: ^3.2.0</li>
    <li><code>fs</code>: Node.js built-in module, no additional installation required.</li>
</ul>

<h2>License</h2>
<p>This project is licensed under the MIT License. See the LICENSE file for more details.</p>

<h2>Acknowledgments</h2>
<p>Thanks to the developers of <code>inquirer</code> and <code>qr-image</code> for their useful packages that made this project possible.</p>

</body>
</html>

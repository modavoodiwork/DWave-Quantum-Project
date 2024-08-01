<h1>Initial Setup</h1>
<h2>Install Ocean</h2>
<div><b>For IDEs installed locally on your system</b></div>
<div>Run the following terminal command: <code>pip install dwave-ocean-sdk</code></div>
<br>
<br>
<div><b>For Cloud IDEs (i.e. GitHub codespaces)</b></div>
<div>Any IDE (local or cloud-based) supporting the Development Containers specification (aka “devcontainers”) will automatically update to a recent Ocean SDK if configured to use an <a href=https://github.com/dwavesystems/ocean-dev-docker>Ocean-Dev Docker Image</a>.</div>
<div>Sample repository to help you get started: <a href=https://github.com/dwavesystems/ocean-devcontainer>ocean-devcontainer</a></div>
<br>  
<h2>Authorize Access to Leap</h2>
<div>The following procedure will authorize the Ocean software to access your <i>current active project</i> in your Leap account and store the 'Solver API Token' into your development environment.</div>
<br>
<div>1 - Run the following terminal command: <code>dwave setup --oob</code></div>
<div>2 - Visit the URL provided in the terminal and select the option to authorize when prompted</div>
<div>3 - Copy the 'authorization code' provided on the website and paste it into the terminal to complete the process</div>
<br>
<div><strong>Alternative steps</strong></div>
<div>- Login to the Leap dashboard and copy the 'Solver API Token'</div>
<div>- In the terminal, run the command <code>dwave setup</code> and paste the 'Solver API Token' when prompted</div>
<br>
<h2>Confirm Setup</h2>
<div>Run the following terminal command to confirm a successful setup</div>
<code>dwave ping --client qpu</code>

<h1>Initial Setup</h1>
<h2>Install Ocean</h2>
<div>For <b>IDEs installed on your system</b><br>
Run the following terminal command: <code>pip install dwave-ocean-sdk</code>
<br>
<br>
<div>For <b>Cloud IDEs</b> that support the Development Containers specification (aka “devcontainers”), your development environment will be updated with a recent Ocean SDK if you configure it to use <a href=https://github.com/dwavesystems/ocean-dev-docker>Ocean-Dev Docker Images</a>.</div>
<div>To get started, copy this sample repository: <a href=https://github.com/dwavesystems/ocean-devcontainer>ocean-devcontainer</a> and run it in your Cloud IDE.</div>
<br>  
<h2>Authorize Access to Leap</h2>
<div>The following procedure will authorize the Ocean software to access your Leap account and store the 'Solver API Token' for your <i>active project</i> in your development environment.</div>
<br>
<div>1 - Run the following terminal command: <code>dwave setup --oob</code></div>
<div>2 - Visit the URL provided in the terminal and select the option to authorize when prompted</div>
<div>3 - Copy the 'authorization code' provided on the website and paste it into the terminal to complete the process</div>
<br>
<div><strong>Optional, manual copy/paste setup steps</strong></div>
<div>- Login to the Leap dashboard and copy the 'Solver API Token'</div>
<div>- In the terminal, run the command <code>dwave setup</code> and paste your 'Solver API Token' when prompted</div>
<br>
<h2>Confirm Setup</h2>
<div>Run the following terminal command to confirm setup</div>
<code>dwave ping --client qpu</code>

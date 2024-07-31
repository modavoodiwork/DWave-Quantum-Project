<h1>Initial Setup</h1>
<h2>Install Ocean</h2>
For <b>IDEs installed on your system</b>, run the following terminal command: <code>pip install dwave-ocean-sdk</code>
<br>
<br>
<br>
<div>For <b>Cloud IDEs</b> that support the Development Containers specification (aka “devcontainers”), i.e GitHub Codespaces, your development environment is updated with a recent Ocean SDK if you configure it to use <a href=https://github.com/dwavesystems/ocean-dev-docker>Ocean-Dev Docker Images</a>. Copy the provided sample files into your repository to get started:</div>
<div><ul>
<li><samp>requirements.txt</samp> file</li>
<li><samp>.devcontainer</samp> folder</li>
<li><samp>devcontainer.json</samp> file within the <samp>.devcontainer</samp> folder</li>
</ul></div>
<br>
<h2>Authorize Access to Leap</h2>
<div>The following procedure will authorize the Ocean software to access your Leap account and store the 'Solver API Token' for your <i>active project</i> in your development environment.</div>
<br>
<div>1 - Run the following terminal command: <code>dwave setup --oob</code></div>
<br>
<div>2 - Visit the Leap URL provided and copy the 'authorization code' from the website, then paste it into the terminal.</div>
<br>
<br>
<div><strong>Optionally, you can complete the initial setup manually</strong></div>
<div>1. Login to Leap and copy the 'Solver API Token' from the dashboard</div>
<div>2. In the terminal, run the command <code>dwave setup</code> and paste your 'Solver API Token' when prompted.</div>
  

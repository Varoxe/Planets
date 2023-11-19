<h1>README for "Planetary Simulation"</h1>

<h2>Overview</h2>
<p>This Python project uses the <code>pygame</code> library to simulate a simple planetary system. It includes visual representations of the sun and several planets, each with their own orbital paths based on gravitational forces.</p>

<h2>Features</h2>
<ul>
  <li><strong>Planetary Orbits:</strong> Simulates the orbits of planets around the sun.</li>
  <li><strong>Realistic Scaling:</strong> Uses astronomical units (AU) and real planetary masses for calculations.</li>
  <li><strong>Dynamic Visualization:</strong> Planets move in real-time and leave a trail showing their orbit path.</li>
  <li><strong>Distance Display:</strong> Shows the distance of each planet from the sun.</li>
</ul>

<h2>Requirements</h2>
<ul>
  <li>Python 3.x</li>
  <li>Pygame library</li>
</ul>

<h2>Installation</h2>
<p>To run this simulation, you need to have Python installed on your system. If you don't have Python installed, you can download it from <a href="https://www.python.org/downloads/">python.org</a>.</p>
<p>Additionally, you need to install the Pygame library. This can be done using pip:</p>
<pre><code>pip install pygame</code></pre>

<h2>Usage</h2>
<p>To start the simulation, simply run the script in your Python environment:</p>
<pre><code>python planetary_simulation.py</code></pre>

<h2>How It Works</h2>
<ul>
  <li><strong>Planets Class:</strong> Each planet is an instance of the <code>Planet</code> class, which contains properties like position, velocity, mass, and color.</li>
  <li><strong>Gravitational Attraction:</strong> The simulation calculates the gravitational attraction between each planet and other celestial bodies.</li>
  <li><strong>Motion Update:</strong> The positions of the planets are updated based on their velocities and the calculated gravitational forces.</li>
  <li><strong>Rendering:</strong> The planets and their orbits are rendered on a Pygame window.</li>
</ul>

<h2>Customization</h2>
<p>You can customize the simulation by altering the properties of the planets in the <code>main</code> function. This includes changing the initial position, velocity, radius, and color of each planet.</p>

<h2>Limitations</h2>
<ul>
  <li>This simulation is a simplified model and does not account for factors like planet rotation, moons, or non-elliptical orbits.</li>
  <li>The scale and time step are adjusted for better visualization, not for precise scientific accuracy.</li>
</ul>

<h2>Contributing</h2>
<p>Feel free to fork this project and contribute by adding more features or improving the existing simulation. All contributions are welcome!</p>

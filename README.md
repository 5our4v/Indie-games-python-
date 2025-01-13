

<header>
    <h1>Flappy Bird in Space - README</h1>
    <p><strong>Capstone Project</strong><br>ROLL: 1931026<br>Course: Software Development</p>
</header>

<section>
    <h2>Overview</h2>
    <p>This is a Python implementation of a simple Flappy Bird-inspired game set in space. The player controls a bird using the spacebar, navigating through obstacles while avoiding collisions. The game tracks the player's score and high score, with a starry background for added ambiance.</p>
</section>

<section>
    <h2>Features</h2>
    <ul>
        <li><strong>Bird with Jetpack Animation:</strong> A red bird with a jetpack effect when it jumps.</li>
        <li><strong>Random Obstacles:</strong> Continuous generation of top and bottom obstacles with random gaps.</li>
        <li><strong>Starry Background:</strong> Dynamic stars simulate a space environment.</li>
        <li><strong>Score Tracking:</strong> Displays the current score and high score.</li>
        <li><strong>Restart Option:</strong> Restart the game with the spacebar upon game over.</li>
    </ul>
</section>

<section>
    <h2>Requirements</h2>
    <ul>
        <li>Python 3.6 or later</li>
        <li><a href="https://www.pygame.org/">Pygame</a> library</li>
    </ul>
    <p>Install the Pygame library using pip:</p>
    <pre><code>pip install pygame</code></pre>
</section>

<section>
    <h2>How to Play</h2>
    <ol>
        <li>Run the game by executing the Python script:
            <pre><code>python flappy_bird.py</code></pre>
        </li>
        <li>Control the bird:
            <ul>
                <li>Press the <strong>spacebar</strong> to make the bird jump.</li>
            </ul>
        </li>
        <li>Navigate through the obstacles:
            <ul>
                <li>Avoid colliding with the top or bottom obstacles.</li>
            </ul>
        </li>
        <li>Game Over:
            <ul>
                <li>If you collide with an obstacle, the game ends.</li>
                <li>Press the <strong>spacebar</strong> to restart the game.</li>
            </ul>
        </li>
    </ol>
</section>

<section>
    <h2>File Descriptions</h2>
    <h3>Main Script</h3>
    <p>The main game script includes:</p>
    <ul>
        <li><strong>Classes:</strong>
            <ul>
                <li><code>colors</code>: Defines commonly used colors.</li>
            </ul>
        </li>
        <li><strong>Functions:</strong>
            <ul>
                <li><code>draw_bird</code>: Draws the bird with its components.</li>
                <li><code>draw_obstacles</code>: Draws the obstacles with caps.</li>
                <li><code>check_collision</code>: Checks for collision between the bird and obstacles.</li>
                <li><code>draw_star</code>: Draws and updates the starry background.</li>
            </ul>
        </li>
        <li><strong>Game Logic:</strong>
            <ul>
                <li>Bird physics and gravity.</li>
                <li>Obstacle movement and score tracking.</li>
                <li>Collision detection and game restart mechanics.</li>
            </ul>
        </li>
    </ul>
</section>

<section>
    <h2>Controls</h2>
    <table>
        <thead>
            <tr>
                <th>Key</th>
                <th>Action</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><strong>Spacebar</strong></td>
                <td>Makes the bird jump or restarts the game after a Game Over.</td>
            </tr>
        </tbody>
    </table>
</section>

<section>
    <h2>Future Enhancements</h2>
    <ul>
        <li>Add sound effects for jumping and collisions.</li>
        <li>Include multiple difficulty levels with varying speeds.</li>
        <li>Introduce power-ups for the bird.</li>
    </ul>
</section>

<section>
    <h2>Acknowledgments</h2>
    <p>- Developed as part of the Software Development course.<br>
    - Inspired by the classic <strong>Flappy Bird</strong> game.</p>
</section>

<section>
    <h2>Gameplay</h2>

</section>

</body>
</html>

![Image_Alt](https://github.com/s0ur4v26/Indie-games-python-/blob/main/Screenshot%202025-01-13%20211609.png?raw=true)
![Image_Alt](https://github.com/s0ur4v26/Indie-games-python-/blob/main/Screenshot%202025-01-13%20211627.png?raw=true)


<style>
    @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Montserrat:wght@600&display=swap');

    :root {
        --primary-color: #00a8ff;
        --secondary-color: #00e676;
        --accent-color: #ff3d00;
        --bg-color: #1a1a2e;
        --text-color: #e0e0e0;
    }

    body {
        font-family: 'Roboto', sans-serif;
        line-height: 1.6;
        color: var(--text-color);
        max-width: 800px;
        margin: 0 auto;
        padding: 20px;
        background: var(--bg-color);
        background-image: 
            radial-gradient(circle at 10% 20%, rgba(0, 168, 255, 0.1) 0%, transparent 20%),
            radial-gradient(circle at 90% 80%, rgba(0, 230, 118, 0.1) 0%, transparent 20%);
    }

    h1, h2 {
        font-family: 'Montserrat', sans-serif;
        color: var(--primary-color);
    }

    h1 {
        font-size: 2.5em;
        border-bottom: 3px solid var(--secondary-color);
        padding-bottom: 10px;
        text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
    }

    h2 {
        font-size: 1.8em;
        color: var(--secondary-color);
        margin-top: 30px;
    }

    .content-block {
        background-color: rgba(255, 255, 255, 0.05);
        padding: 20px;
        border-radius: 10px;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        margin-bottom: 20px;
        border: 1px solid rgba(255, 255, 255, 0.1);
        backdrop-filter: blur(5px);
    }

    .highlight {
        background-color: rgba(255, 255, 255, 0.05);
        border-left: 4px solid var(--accent-color);
        padding: 10px;
        margin: 10px 0;
    }

    ul {
        list-style-type: none;
        padding-left: 0;
    }

    ul li:before {
        content: "•";
        color: var(--accent-color);
        font-weight: bold;
        display: inline-block;
        width: 1em;
        margin-left: -1em;
    }

    .audio-player {
        width: 100%;
        margin: 10px 0;
        background-color: rgba(255, 255, 255, 0.1);
        border-radius: 5px;
    }

    strong {
        color: var(--accent-color);
    }

    @keyframes gradient-animation {
        0% {
            background-position: 0% 50%;
        }
        50% {
            background-position: 100% 50%;
        }
        100% {
            background-position: 0% 50%;
        }
    }

    .gradient-text {
        background: linear-gradient(45deg, var(--primary-color), var(--secondary-color), var(--accent-color));
        -webkit-background-clip: text;
        background-clip: text;
        color: transparent;
        animation: gradient-animation 6s ease infinite;
        background-size: 300% 300%;
    }
</style>

<h1 class="gradient-text">Week 2: Understanding Beats in Music Production</h1>

<div class="content-block">
    <h2>Introduction to Beats</h2>
    <p>In music production, a beat serves as the fundamental rhythmic unit. It's the consistent pulse that listeners feel, often emphasized by percussion instruments like drums. Understanding beats is crucial for creating well-structured and rhythmically engaging music.</p>
</div>

<div class="content-block">
    <h2>1. What is a Beat?</h2>
    <p>A beat is a regular, repeating pulse in music that forms the foundation for rhythms, melodies, and harmonies. In most Western music, beats are organized into measures, typically with 4 beats per measure in 4/4 time signature.</p>
    <div class="highlight">
        <p><strong>Key Point:</strong> Beats provide the rhythmic framework for musical compositions.</p>
    </div>
    <audio class="audio-player" controls>
        <source src="audio/simple-beat.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>
</div>

<div class="content-block">
    <h2>2. Types of Beats</h2>
    <p>Music production employs various types of beats, each with its unique characteristics:</p>
    <ul>
        <li><strong>Four on the floor:</strong> A steady beat on every quarter note, common in dance music.</li>
        <li><strong>Backbeat:</strong> Emphasis on the 2nd and 4th beats, typical in rock and pop.</li>
        <li><strong>Syncopated:</strong> Emphasis on off-beats, creating a more complex rhythm.</li>
    </ul>
    <audio class="audio-player" controls>
        <source src="audio/rhythm.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>
</div>

<div class="content-block">
    <h2>3. Importance of Beats in Music Production</h2>
    <p>Beats play a crucial role in music production by:</p>
    <ul>
        <li>Providing a rhythmic foundation for other musical elements</li>
        <li>Setting the tempo and energy of a track</li>
        <li>Creating groove and encouraging physical response (e.g., dancing)</li>
    </ul>
</div>

<div class="content-block">
    <h2>4. Creating Beats</h2>
    <p>Music producers utilize various tools to create beats, including:</p>
    <ul>
        <li>Drum machines</li>
        <li>Samplers</li>
        <li>Digital Audio Workstations (DAWs)</li>
        <li>MIDI controllers</li>
    </ul>
    <audio class="audio-player" controls>
        <source src="audio/time-signature.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>
</div>

<div class="content-block">
    <h2>5. Understanding Sound Waves</h2>
    <p>To fully grasp beats and music production, it's important to understand the nature of sound waves and how they contribute to the overall audio experience.</p>
    <div class="highlight">
        <p><strong>Frequency:</strong> Determines the pitch of a sound.</p>
        <audio class="audio-player" controls>
            <source src="audio/frequency.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>
    </div>
    <div class="highlight">
        <p><strong>Amplitude:</strong> Affects the volume or loudness of a sound.</p>
        <audio class="audio-player" controls>
            <source src="audio/amplitude.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>
    </div>
</div>

<div class="content-block">
    <h2 class="gradient-text">Conclusion</h2>
    <p>Understanding beats is fundamental to music production. By mastering the concepts of rhythm, timing, and sound manipulation, producers can create compelling and engaging musical experiences.</p>
</div>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Zoom Clone by krishna khurana- README</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 0;
      padding: 20px;
      background-color: #f4f4f9;
    }
    h1, h2, h3 {
      color: #333;
    }
    a {
      color: #007bff;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    pre {
      background: #333;
      color: #fff;
      padding: 10px;
      border-radius: 5px;
      overflow-x: auto;
    }
    ul {
      list-style: none;
      padding: 0;
    }
    ul li {
      margin-bottom: 10px;
    }
  </style>
</head>
<body>
  <h1>Zoom Clone by krihna khurana</h1>
  <p>A feature-rich video conferencing application that replicates the core functionalities of Zoom. Built to enable seamless communication, this application includes real-time video, audio, chat, and other collaborative tools.</p>

  <h2>Features</h2>
  <ul>
    <li><strong>Real-Time Video & Audio:</strong> High-quality video and audio streaming for smooth communication.</li>
    <li><strong>Chat Functionality:</strong> Instant messaging during meetings.</li>
    <li><strong>User Authentication:</strong> Secure login and registration system using Clerk API.</li>
    <li><strong>Meeting Rooms:</strong> Create or join meeting rooms with unique IDs.</li>
    <li><strong>Screen Sharing:</strong> Share your screen with other participants.</li>
    <li><strong>Meeting Scheduler:</strong> Schedule meetings with date and time.</li>
    <li><strong>Participant Management:</strong> Host can manage participants (mute/unmute, remove, etc.).</li>
  </ul>

  <h2>Tech Stack</h2>
  <ul>
    <li><strong>Frontend:</strong> HTML, CSS, JavaScript, Bootstrap</li>
    <li><strong>Backend:</strong> Node.js, Express</li>
    <li><strong>Database:</strong> MongoDB/Firebase (or your preferred database)</li>
    <li><strong>Real-Time Communication:</strong> WebRTC, Socket.io, Stream API for chat and live notifications.</li>
  </ul>

  <h2>Installation</h2>
  <ol>
    <li>Clone the repository:
      <pre>git clone https://github.com/your-username/zoom-clone.git
cd zoom-clone</pre>
    </li>
    <li>Install dependencies:
      <pre>npm install</pre>
    </li>
    <li>Set up environment variables:
      <p>Create a <code>.env</code> file in the root directory and add the following:</p>
      <pre>
        NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
        CLERK_SECRET_KEY=
        NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
        NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
        NEXT_PUBLIC_STREAM_API_KEY=
        STREAM_SECRET_KEY=
      </pre>
    </li>
    <li>Start the application:
      <pre>npm start</pre>
    </li>
    <li>Open your browser and navigate to <code>http://localhost:3000</code>.</li>
  </ol>

  <h2>Usage</h2>
  <ol>
    <li>Register and log in to your account.</li>
    <li>Create a new meeting or join an existing one using a meeting ID.</li>
    <li>Use the video, audio, chat, and other features during the meeting.</li>
  </ol>

  <h2>Screenshots</h2>
  <p>Include screenshots of the app interface (e.g., login page, meeting room, chat interface).</p>

  <h2>Contributing</h2>
  <p>Contributions are welcome! Follow these steps:</p>
  <ol>
    <li>Fork the repository.</li>
    <li>Create a new branch: <code>git checkout -b feature-name</code>.</li>
    <li>Commit your changes: <code>git commit -m 'Add new feature'</code>.</li>
    <li>Push to the branch: <code>git push origin feature-name</code>.</li>
    <li>Open a pull request.</li>
  </ol>

  

  <h2>Acknowledgements</h2>
  <ul>
    <li><a href="https://webrtc.org/">WebRTC Documentation</a></li>
    <li><a href="https://socket.io/">Socket.io</a></li>
    <li><a href="https://getbootstrap.com/">Bootstrap</a></li>
    <li><a href="https://clerk.dev/">Clerk API</a></li>
    <li><a href="https://getstream.io/">Stream API</a></li>
  </ul>

  <hr>
  <p>Feel free to contribute or reach out with feedback!</p>

  <h2>Author</h2>
  <p>Developed by <a href="https://krishnakhurana.us.kg">Krishna Khurana</a>. Ui design taken from the project of javascript mastery</p>
</body>
</html>

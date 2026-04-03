<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ProDash README</title>
    <style>
        :root {
            --bg-color: #0d1117;
            --container-bg: #161b22;
            --text-main: #c9d1d9;
            --text-muted: #8b949e;
            --accent: #58a6ff;
            --border-color: #30363d;
            --code-bg: #010409;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-main);
            line-height: 1.6;
            margin: 0;
            padding: 40px 20px;
        }

        .container {
            max-width: 880px;
            margin: 0 auto;
            background-color: var(--container-bg);
            border: 1px solid var(--border-color);
            border-radius: 8px;
            padding: 45px;
            box-shadow: 0 8px 24px rgba(0,0,0,0.5);
        }

        .header {
            text-align: center;
            border-bottom: 1px solid var(--border-color);
            padding-bottom: 20px;
            margin-bottom: 30px;
        }

        h1 { font-size: 2.5rem; margin-bottom: 10px; color: #fff; }
        h2 { font-size: 1.5rem; border-bottom: 1px solid var(--border-color); padding-bottom: 8px; margin-top: 40px; color: #f0f6fc; }
        
        .tagline { font-style: italic; color: var(--text-muted); font-size: 1.2rem; }

        .badges { margin: 20px 0; }
        .badge {
            display: inline-block;
            padding: 4px 12px;
            border-radius: 12px;
            font-size: 12px;
            font-weight: bold;
            margin-right: 5px;
            background: var(--border-color);
        }

        .features-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin-top: 20px;
        }

        .feature-card {
            background: var(--bg-color);
            padding: 20px;
            border-radius: 6px;
            border: 1px solid var(--border-color);
            transition: transform 0.2s;
        }

        .feature-card:hover {
            transform: translateY(-5px);
            border-color: var(--accent);
        }

        .feature-card strong { color: var(--accent); display: block; margin-bottom: 5px; }

        pre {
            background: var(--code-bg);
            padding: 16px;
            border-radius: 6px;
            overflow-x: auto;
            border: 1px solid var(--border-color);
        }

        code { font-family: "SFMono-Regular", Consolas, "Liberation Mono", Menlo, monospace; color: #79c0ff; }

        .btn {
            display: inline-block;
            background-color: #238636;
            color: white;
            padding: 10px 20px;
            border-radius: 6px;
            text-decoration: none;
            font-weight: 600;
            margin-top: 20px;
        }

        .btn:hover { background-color: #2ea043; }

        ul { padding-left: 20px; }
        li { margin-bottom: 10px; }

        @media (max-width: 600px) {
            .features-grid { grid-template-columns: 1fr; }
            .container { padding: 20px; }
        }
    </style>
</head>
<body>

<div class="container">
    <div class="header">
        <h1>✦ ProDash</h1>
        <p class="tagline">Productivity Reimagined. A premium, single-file power suite.</p>
        <div class="badges">
            <span class="badge" style="color: #ffd33d;">License: MIT</span>
            <span class="badge" style="color: #ff7b72;">No Dependencies</span>
            <span class="badge" style="color: #a5d6ff;">Single File</span>
        </div>
    </div>

    <h2>✨ Key Features</h2>
    <div class="features-grid">
        <div class="feature-card">
            <strong>🧱 Kanban Engine</strong>
            Fluid drag-and-drop workflow for managing tasks across status columns.
        </div>
        <div class="feature-card">
            <strong>📝 Markdown Notes</strong>
            Dual-pane editor with live rendering and local storage persistence.
        </div>
        <div class="feature-card">
            <strong>📅 Interactive Calendar</strong>
            Visual schedule management with quick-entry capabilities.
        </div>
        <div class="feature-card">
            <strong>📈 Real-time Analytics</strong>
            Automated visualization of productivity trends and completion rates.
        </div>
    </div>

    <h2>🛠️ Tech Stack</h2>
    <ul>
        <li><strong>Frontend:</strong> Vanilla ES6+ JavaScript, HTML5 Canvas, CSS3.</li>
        <li><strong>Database:</strong> IndexedDB (Local-first architecture).</li>
        <li><strong>Design:</strong> Glassmorphic UI with Grain overlays & Syne Typography.</li>
    </ul>

    <h2>🚀 Getting Started</h2>
    <p>ProDash is designed for extreme portability. To use it:</p>
    <pre><code>1. Download 'prodash-2.html'
2. Open in any modern browser
3. Press Ctrl+K to open the Command Palette</code></pre>

    <h2>⌨️ Shortcuts</h2>
    <ul>
        <li><code>Cmd/Ctrl + K</code> — Global Command Palette</li>
        <li><code>/</code> — Instant Search</li>
        <li><code>Esc</code> — Close UI Overlays</li>
    </ul>

    <div style="text-align: center; margin-top: 40px; border-top: 1px solid var(--border-color); padding-top: 20px;">
        <p style="font-size: 0.9rem; color: var(--text-muted);">
            ProDash © 2024 • Created for high-performance workflows.
        </p>
    </div>
</div>

</body>
</html>

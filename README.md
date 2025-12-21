<!DOCTYPE html>
<html>
<head>
    <style>
        .banner {
            width: 1200px;
            height: 475px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: white;
            font-family: 'Arial', sans-serif;
        }
        .ai-text {
            font-size: 72px;
            font-weight: bold;
            letter-spacing: 2px;
        }
        .milcorx-text {
            font-size: 48px;
            margin: 10px 0;
            font-weight: 600;
        }
        .performance-text {
            font-size: 24px;
            letter-spacing: 1px;
            opacity: 0.9;
        }
    </style>
</head>
<body>
    <div class="banner">
        <div class="ai-text">AI</div>
        <div class="milcorx-text">MILCORX</div>
        <div class="performance-text">e-Xtreme Performance</div>
    </div>
</body>
</html>

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`

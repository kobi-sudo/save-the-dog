# Save the Dog 🐕

AI-powered veterinary clinical cases for vets and vet students.

## Deploy in 5 minutes (free)

### Step 1 — Get your Anthropic API key
1. Go to https://console.anthropic.com
2. Sign up / log in
3. Go to "API Keys" and create a new key
4. Copy it — you'll enter it in the app

### Step 2 — Put these files on GitHub
1. Go to https://github.com and create a free account
2. Click "New repository", name it `save-the-dog`, make it **Public**
3. Upload these files: `index.html`, `manifest.json`, `netlify.toml`

### Step 3 — Deploy to Netlify (free)
1. Go to https://netlify.com and sign up with your GitHub account
2. Click "Add new site" → "Import an existing project"
3. Choose GitHub → select your `save-the-dog` repo
4. Click "Deploy site"
5. Netlify gives you a URL like `https://save-the-dog-abc123.netlify.app`

### Step 4 — Share with your team
Send the URL to your team. On mobile, they can:
- **iPhone**: Open in Safari → Share → "Add to Home Screen"
- **Android**: Open in Chrome → Menu → "Add to Home Screen"

It will appear as a full-screen app on their phones.

## How to play
1. Open the app and enter your Anthropic API key (only once — it's saved in the browser)
2. Choose a specialty and difficulty
3. Tap "Generate case" — a new AI case is created every time
4. Clinical findings are revealed step by step
5. Answer each question, then see explanations and teaching points
6. Complete all 4 phases to save the dog!

## Specialties
- Internal medicine
- Orthopedics
- Oncology
- Dermatology
- Cardiology

## Scoring
- Correct answer: +100 pts
- Acceptable but not ideal: +30 pts (small health penalty)
- Incorrect: no points, -25% dog health
- Triage timeout: -25% dog health

## Tech
- Pure HTML/CSS/JS — no framework, no build step
- Anthropic Claude Sonnet via direct API call
- PWA-ready (installs on phone home screen)
- API key stored in browser localStorage only

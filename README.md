# KBC Torts React App (ready-to-deploy)

This is a KBC-style quiz web app built for a classroom skit (Torts edition).

**Features**
- React app with 25 preloaded questions
- Animated audience poll, working lifelines (50-50, Audience, Phone-a-Friend)
- Admin reveal, timer, auto-next, background music toggles
- Export results as CSV
- Ready for deployment to Netlify, Vercel, or CodeSandbox

**How to run locally**
1. Install Node.js (>=16) and npm.
2. In the project folder, run `npm install`
3. Run `npm start` and open `http://localhost:3000`

**Audio / Assets**
Put royalty-free audio files into `public/assets/`:
- intro.mp3
- lock.mp3
- correct.mp3
- wrong.mp3
- bg.mp3

You can use Mixkit, Pixabay, or Freesound (choose CC0/public domain or attribution-free).

**Deploying online (Netlify)**
1. Create a GitHub repo and push this project.
2. In Netlify, click New site → Import from Git → select the repo.
3. Build command: `npm run build`, Publish directory: `build`.

Or open the project in CodeSandbox and it will run instantly.

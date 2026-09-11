# Dependencies (নির্ভরতা ফোল্ডার)
node_modules/
jspm_packages/

# Production / Build ফোল্ডার (React Vite বা অন্যান্য বিল্ড)
dist/
build/
.next/
out/

# Environment Variables & Secrets (গোপন ফাইল বা এপিআই কি)
.env
.env.local
.env.development.local
.env.production.local

# Logs (লগ ফাইল ও ডেটাবেজ)
npm-debug.log*
yarn-debug.log*
yarn-error.log*
pnpm-debug.log*
logs
*.log

# Runtime data & Temporary Audio files (ফিসার বা অডিও টেম্পোরারি ফাইল)
temp_audio.mp3
temp_edge_audio.mp3
*.wav
*.mp3

# Whisper ও মডেল ফাইল (যেহেতু এগুলো অনেক বড় সাইজের হয়, গিটহাবে আপলোড করার প্রয়োজন নেই)
whisper/whisper.cpp/build/
whisper/whisper.cpp/models/
whisper/whisper.cpp/my_audio.wav

# OS Generated Files (উইন্ডোজের হিডেন ফাইল)
Thumbs.db
ehthumbs.db
Desktop.ini
$RECYCLE.BIN/
.DS_Store

# Editor / IDE settings (VS Code বা অন্যান্য এডিটর কনফিগ)
.vscode/
.idea/
*.suo
*.ntvs*
*.njsproj
*.sln
*.swp
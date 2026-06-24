# fitness-app
SquatForm

Real-time squat form tracking, powered by computer vision — built as a full-stack web app.

Built together by Malcolm and Megan.

What is this?
SquatForm watches you squat through your webcam, scores your form in real time, and tracks your progress over time. It started as a single-file pose-tracking demo and is growing into a full production app: user accounts, a real database, a REST API, video replays, and analytics dashboards.
No wearables. No guesswork. Just your camera and some math.

Features
Live form tracking — pose detection runs right in the browser, no server round-trip needed for the core tracking loop
Rep-by-rep scoring — depth, knee tracking, and faults (like knees caving in) are scored on every single rep
User accounts — register/login with hashed passwords and JWT-based auth
Persistent history — every session and rep gets saved, so progress is never lost
Video recording — record your set and upload it straight to cloud storage for later review
Analytics — trends in form score, best depth, and weekly activity over time

Built by
Malcolm and Megan — figuring out full-stack development one squat at a time. PRs, ideas, and form critiques welcome.

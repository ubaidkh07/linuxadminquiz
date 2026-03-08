Linux Admin Quiz
-----------------
**LinuxAdminQuiz** is an interactive, client-side quiz app for testing Linux system administration skills. Features `index.html` for the UI and `quiz.json` for questions covering commands, permissions, processes, networking, and more. Runs entirely in the browser—no server needed. [docs.github](https://docs.github.com/en/repositories/creating-and-managing-repositories/best-practices-for-repositories)

## Live Demo
Try the hosted version on InfinityFree (free hosting service):  
[https://linuxadminquiz.free.nf/?i=1](https://linuxadminquiz.free.nf/?i=1) [free](https://free.nf)

## Features
- Multiple-choice questions with detailed explanations.
- Real-time score tracking, progress indicator, next/previous navigation.
- Responsive design works on desktop, tablet, and mobile.
- Client-side only: Questions load dynamically from `quiz.json`.

## Quick Start
1. Clone the repo: `git clone https://github.com/ubaidkh07/linuxadminquiz.git`
2. Open `index.html` in any browser.
3. Quiz starts automatically—test your Linux admin knowledge!

For live hosting like the demo, upload to InfinityFree (free PHP/MySQL hosting with no ads). [infinityfree](https://www.infinityfree.com)

## File Structure
| File       | Description |
|------------|-------------|
| `index.html` | Core quiz app (HTML/CSS/JS). [Latest commit](https://github.com/ubaidkh07/linuxadminquiz/commit/21d62762bb5f1d413f808826fd96f424615bedeb). |
| `quiz.json`  | JSON data: questions, options, correct answers, explanations. Edit to customize. |

## Hosting on InfinityFree
- Sign up at [infinityfree.com](https://www.infinityfree.com) (free, unlimited bandwidth, PHP/MySQL support).
- Upload `index.html` and `quiz.json` via File Manager or FTP.
- Access via your `yoursite.free.nf` subdomain, as done for the live demo. [infinityfree](https://www.infinityfree.com)

## Customization
- Edit `quiz.json` to add/remove questions: `{ "question": "...", "options": [...], "correct": 0, "explanation": "..." }`.
- Modify styles/scripts directly in `index.html`.
- Supports unlimited questions with automatic pagination.

## Contributing
Fork, update `quiz.json` with new Linux admin questions, and submit a PR. Ensure accuracy and include explanations. Bug reports welcome via Issues.

## License
MIT License. See [LICENSE](LICENSE) or add one for compliance. [docs.github](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes)

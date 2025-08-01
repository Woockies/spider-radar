# Spider Radar – Strength & Balance App

This repository contains a **pure HTML/JavaScript** implementation of the Strength & Balance application. It was adapted from an earlier React/Firebase component to run entirely in the browser without any build tooling or backend services. The app allows you to:

* Enter personal details (name, sex, age, height and weight in either metric or imperial units).
* Record your one‑rep maxes for seven common lifts (squat, deadlift, bench press, overhead press, barbell row, leg curl and leg extension), plus optional left/right values.
* Record body‑weight exercise repetitions (pull‑ups, push‑ups and dips).
* Calculate strength‑to‑bodyweight ratios, symmetry ratios (push/pull, quad/ham, upper/lower) and left/right differences.
* Visualise your results in a radar (spider) chart.
* Save assessments to the browser’s `localStorage` and reload or delete them later.

## Running locally

Because this is a static web app, you don’t need Node.js or any package manager to run it. Simply open `index.html` in your browser:

1. Clone or download this repository.
2. Open `spider-radar-webapp/index.html` in a modern browser.
3. The app will load immediately. All data is stored locally in your browser.

## Notes

* The app uses [Tailwind CSS](https://tailwindcss.com/), [React](https://react.dev/) and [ReactDOM](https://react.dev/) via CDNs. It also includes the [Babel](https://babeljs.io/) standalone compiler to transform JSX on the fly. No build step is required.
* If you wish to host the app online, you can upload the contents of `spider-radar-webapp` to any static web host (e.g. GitHub Pages, Vercel, Netlify).
* Firebase integration has been removed in this version. If you wish to connect to Firebase for user authentication or cloud storage, you can adapt the code in `index.html` accordingly.

## My Resume

* 原作者 https://github.com/joyeecheung/resume

## Build

1. Run `npm install` to install the dependencies.
2. Fill your resume data in `resume.json`.
3. Run `gulp build` to generate the static web page(`dist/index.html`).
4. Run `gulp server` and visit `http://localhost:8000` if you want to see it hosted locally(make sure the port 8000 is not taken).

## Deploy to GitHub Pages

1. Set up the SSH git remote `origin` for the project.
2. After building the web page, run `gulp deploy`.
3. Everything under `dist` will be pushed to the remote repo's `gh-pages` branch.

## Develop

1. Make sure port 35729(for livereload) and 8000(for the local server) are available.
2. Run `gulp`, then visit `http://localhost:8000`.
3. Start development!

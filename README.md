## How to deploy and run your website with UC script tag

- Clone this repo to your own repo
- Grab your preferred Settings Id script tag
- Replace the current script tag (public/index.html)
- Add data-sandbox=true to it
- Add the domain to your SettingId Configuration
- change package.json "homepage" value to your repository page url
  "homepage": "https://{{repositoryname}}.github.io/{{project-name}}/",
- Replace %PUBLIC_URL%/maga/ with %PUBLIC_URL%/{{project-name}}/
- run: npm i
- run: npm run deploy

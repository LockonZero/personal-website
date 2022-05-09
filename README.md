# azotos.{gr, com} blog

## General Instructions

### For the SASS
>Note to future self: Don't forget to refresh Cloudflare please.

Navigate to the css folder in the theme and run the following command in order to watch for changes:
>rubygem-sass is required
```bash
cd themes/hugo-zero/static/css
scss --no-cache --watch zero.scss
```

Serve the installation locally (for development)
```
hugo server --disableFastRender
```

### Sync files

From project root run: 
```bash
rsync -arvz -e 'ssh -p <port-number>' --progress ./public/ user@remote-server:/remote/folder
```

## TODOLIST
- Add homepage or back button in all pages
- Fix the main text font size (too large atm)
- Convert dates to dd/mon/yy
- Fix hugo warnings
- Dark theme (and control)
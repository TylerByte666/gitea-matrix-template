# Gitea Matrix Template- Turn your gitea arc-green template into the matrix
## Previews:

![preview 1](matrix-preview.png "Preview")

![preview 2](matrix-preview-2.png "Preview")

## For Gitea Version ***1.11.x***

## How to use:
1. Find your gitea custom directory path in ***Site Administration > Configuration > Custom File Root Path***.
2. Create directorys ***templates*** and ***public/css*** if not exist.
3. Copy/Move files from this repo in there counterpart locations.
4. Add folowing lines to your gitea config:
```ini
[ui]
THEMES = gitea,arc-green,matrix
DEFAULT_THEME = matrix
```
7. Restart your Gitea Service and you are ready to go.
### Welcome to the matrix!

8. A user can still change the theme he likes in his settings avterwards

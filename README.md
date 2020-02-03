# Gitea Matrix Template- Turn your gitea arc-green template into the matrix
## Previews:

![preview 1](images/matrix-preview.png "Logo Title Text 1")

![preview 2](images/matrix-preview-2.png "Logo Title Text 1")



## How to use:
1. Find your gitea custom directory path in ***Site Administration > Configuration > Custom File Root Path***.
2. Create a new directory in your custom root path called ***templates***.
3. Create another directory in your custom root path called ***/public/css/***.
4. Clone the repo on your gitea server and move all the files except gitea-matrix-theme.css to the templates directory in your custom root path that you created in step 2.
5. Move the gitea-matrix-theme.css into the public/css/ folder you created earlier.
6. Set the arc-green built-in gitea theme active under ***Settings*** or set is as the default theme by finding your ***Site Administration > Configuration > Configuration File Path*** usually ***/.../gitea/app.ini***. Edit it to add this code to the last part of the file and save it:

`[ui]`

`DEFAULT_THEME = arc-green`

7. Restart your Gitea Service and you are ready to go. 
### Welcome to the matrix!
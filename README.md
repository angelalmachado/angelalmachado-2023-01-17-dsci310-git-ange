# angelalmachado-2023-01-17-dsci310-git-ange Git Demo
Intro Git Demo

- `git clone <URL>`: takes what's on github and does a one time download to your computer
- `git status`: tells you what is going on in the repository
- `git add <FILE>`: add the <FILE> to the staging area
- `git commit`: commit the file to github! (aka snapshot)

but... there is a shortcut 
- `git commit -m "MESSAGE"`: create the git message directly in the command line
- `git push <where> <what>`: will take local commits on <what> and send it to <where>
    - e.g. `git push origin main`
- `git pull <where> <what>`: will take remote commits on <what> and pull it from <where>
    - e.g. `git pull origin main`
    git config --global user.name "ftk1000"
    git config --global user.email "khafizov.farid@gmail.com"
    git config --list



…or create a new repository on the command line

    echo "# st_demo" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/ftk1000/st_demo.git
    git push -u origin main

…or push an existing repository from the command line

    git remote add origin https://github.com/ftk1000/st_demo.git
    git branch -M main
    git push -u origin main


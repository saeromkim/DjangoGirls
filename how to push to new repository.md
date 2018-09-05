
## create a new repository on the command line

>echo "# DjangoGirls" >> README.md
>git init
>git add README.md
>git commit -m "first commit"
>git remote add origin https://github.com/saeromksr247/DjangoGirls.git
>git push -u origin master

## push an existing repository from the command line

>git remote add origin https://github.com/saeromksr247/DjangoGirls.git
>git push -u origin master

## fatal: remote origin already exists ¿À·ù°¡ ¹ß»ýÇÒ ¶§

>1.To remove a remote repository you enter:
>git remote rm origin

>2.if you want to remove the "upstream" remote:
>git remote rm upstream

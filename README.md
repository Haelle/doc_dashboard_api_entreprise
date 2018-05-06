# How to develop
1. Install Python3 livereload `pip intall livereload`
2. `livereload -p 3000`
3. browse localhost:3000/index.dev.html

*WARNING ReDoc fait des erreurs silencieuses* si le fichier de spec est incorrecti et comme il est découpé en plusieurs fichiers il ne passe pas dans editor.swagger.io par exemple...

# Why ?
ReDoc cannot access files via ftp ; in production it is not supposed to... So you need to serve the OpenAPI spec via a webserver.

And this webserver needs livereload to make development easy. As Python is on every Linux...

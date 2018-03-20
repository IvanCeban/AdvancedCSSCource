if the provided code for prefix:css not working, try this command : 
postcss --use autoprefixer -b 'last 10 versions' css/style.concat.css -o css/style.prefix.css
It could work on MacOS or Linux, but doesn't work on windows

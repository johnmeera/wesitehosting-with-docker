index.html file foe website hosting
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>myownwebsite</title>
</head>
<body>
    <h1>johnmeerashaik-chandu</h1>

</body>
</html>
...............................
dockerfile to crete web site

# Use a lightweight web server as a parent image
FROM nginx:alpine

# Copy the HTML file into the nginx document root
COPY index.html /usr/share/nginx/html

# Expose port 80 to the outside world
EXPOSE 80


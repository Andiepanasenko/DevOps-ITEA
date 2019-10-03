#I created a file index.html with text "Hello World!"   inside dir  /home/pai/DockerFile on my local machine.
#Then ran a command $ docker run -v /home/pai/DockerFile:/usr/share/nginx/html -p 8888:80 nginx
#After I opened Internet browser and put local ip address  with port 8888 which I redirected from 80, text "Hello World!" is displayed on the page

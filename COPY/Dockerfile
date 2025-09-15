FROM almalinux:9 
RUN sudo install ngnix -y 
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/index.html 
CMD ["nginx", "-g", "daemon off;"]
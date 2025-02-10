FROM nginx:latest
RUN mkdir /usr/share/nginx/html/airtag
COPY index.html /usr/share/nginx/html/airtag/.
CMD ["nginx", "-g", "daemon off;"]


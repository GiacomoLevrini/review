FROM jupyter/minimal-notebook
RUN pip install redis
COPY index.html /var/www/html/
EXPOSE 80
CMD ["apachectl", "-D", "FOREGROUND"]

FROM alalamin19/mgayle
WORKDIR /app
COPY requirements.txt ./
RUN pip install -r requirements.txt
COPY . .
EXPOSE 8000
EXPOSE 80
CMD ["/usr/sbin/apachectl", "-D",  "FOREGROUND"]

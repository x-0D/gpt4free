FROM hlohaus789/g4f:latest
RUN rm g4f/api/__init__.py
RUN rm /etc/supervisor/conf.d/selenium.conf
COPY docker/supervisor.conf /etc/supervisor/conf.d/selenium.conf
COPY g4f/api/__init__.py g4f/api/__init__.py

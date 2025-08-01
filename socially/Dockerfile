FROM python:3.14-rc-alpine3.20
WORKDIR /app
COPY requirements.txt /app
RUN pip install -r requirements.txt
RUN echo "flag{y0u_d1d_1t}" > /flag
COPY . /app
ENTRYPOINT ["python"]
CMD ["app.py"]

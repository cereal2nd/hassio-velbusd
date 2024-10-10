FROM python:latest

# extract
RUN mkdir /velbus
RUN cd /velbus && git clone https://github.com/velbus/python-velbustcp.git .
RUN cd /velbus && python3 -m venv venv
RUN cd /velbus && /velbus/venv/bin/pip install -e .

# Coppy setings
COPY settings.json /

CMD ["/velbus/venv/bin/python3", "-m", "velbustcp", "--settings", "/settings.json"]

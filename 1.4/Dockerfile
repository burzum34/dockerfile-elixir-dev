FROM elixir:1.4.2

RUN git clone git://github.com/rebar/rebar.git /rebar && \
	cd /rebar && \
	./bootstrap && \
	cp ./rebar /usr/bin/rebar && \
	rm -rf /rebar

RUN git clone https://github.com/hexpm/hex /hex && \
	cd /hex && \
	mix install

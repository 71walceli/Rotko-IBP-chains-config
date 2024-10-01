FROM ubuntu:24.04


RUN apt-get update && apt-get install -y wget jq

WORKDIR /App/
#RUN wget https://github.com/paritytech/polkadot-sdk/releases/download/polkadot-stable2409/polkadot
RUN wget https://github.com/paritytech/polkadot-sdk/releases/download/polkadot-stable2409/polkadot
RUN wget https://github.com/paritytech/polkadot-sdk/releases/download/polkadot-stable2409/polkadot-execute-worker
RUN wget https://github.com/paritytech/polkadot-sdk/releases/download/polkadot-stable2409/polkadot-prepare-worker
RUN wget https://github.com/paritytech/polkadot-sdk/releases/download/polkadot-stable2409/polkadot-parachain
RUN chmod +x *

ENV PATH=/App:${PATH}



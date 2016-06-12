FROM haskell:7.10.3

RUN stack --resolver lts-6.2 install werewolf-slack-1.0.1.3 werewolf-1.3.0.0
ENTRYPOINT ["werewolf-slack"]

EXPOSE 80

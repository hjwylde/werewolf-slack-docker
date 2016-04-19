FROM haskell:7.10.3

RUN stack --resolver lts-5.12 install werewolf-slack-1.0.0.0 werewolf-1.0.1.0
ENTRYPOINT ["werewolf-slack"]

EXPOSE 8080

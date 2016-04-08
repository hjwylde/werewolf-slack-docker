FROM haskell:7.10.3

RUN stack --resolver lts-5.11 install werewolf-slack-0.4.0.0 werewolf-0.5.3.0
ENTRYPOINT ["werewolf-slack"]

EXPOSE 8080

FROM haskell:7.10.3

RUN stack --resolver lts-5.10 install werewolf-slack-0.3.0.2 werewolf-0.5.3.0
ENTRYPOINT ["werewolf-slack"]

EXPOSE 8080

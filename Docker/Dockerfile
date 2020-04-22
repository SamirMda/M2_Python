FROM docker/whalesay
RUN apt-get update && apt-get install -y figlet fortune
CMD figlet "Hey Samir" | cowsay -n && /usr/games/fortune -a | cosway

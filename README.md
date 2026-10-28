# moja-apka

![CI](https://github.com/bartekjawien/moja-apka/actions/workflows/ci.yml/badge.svg)

Prosta aplikacja Flask uruchamiana w kontenerze Docker, z CI w GitHub Actions.

## Uruchomienie

    docker build -t moja-apka .
    docker run -d -p 5001:5000 --name moja-apka moja-apka
    curl http://localhost:5001/health

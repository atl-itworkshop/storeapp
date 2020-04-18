# Containerize the Store App
Wrapper project to containerize the Store app

## Setup

1. Clone this repo and `cd storeapp`
2. Copy the `MyNodeJsProject` and the `basic-react-project` to the `storeapp` folder

## Build

To build the app after making changes:

```
docker-compose up -d --build
```

## Run

To run the app:

```
docker-compose up -d
```

## List containers

To list containers for the app:

```
docker-compose ps
```

## Shutdown

To shutdown the app:

```
docker-compose down
```

## Slides

[Why Containerize?](https://speakerdeck.com/rupakg/why-containerize)

# Book Fetcher CLI

A CLI tool to fetch books from different APIs and websites.

## Build

```
./gradlew build --no-configuration-cache
```

## Run

```

// generate the executable
./gradlew installDist

// run the executable
./app/build/install/app/bin/app --book-title=fleurs --book-author=baudelaire --book-language=fr   

// run the application using the run task
./gradlew run --args="--book-title=fleurs --book-author=baudelaire --book-language=fr"
```

# ...Of the Day APP

## Description
This is a simple little SPA that I made consisting of various APIs that provide anything from random facts about cats to a live tracker for Bitcoin. Since this app is an entirely static personal project, I am limited to the number of APIs available that are both free and don't require CORS.

This app is a PWA (Progressive Web App) and, thus, can be installed on mobile and desktop in addition to being used in the browser. Due to the app's current dependency on third-party APIs, offline use has not been setup at this time.

## APIs
- Random
    - Cat facts
    - Geek jokes (mostly Chuck Norris ones)
    - Scripture (5x)
- Of the Day
    - NASA astronomy photo/video with text
        -  Each day's item is saved into IndexedDB with a unique index on the date to prevent duplicates
        -  Previous items are automatically added into the DOM when the page is loaded
- Cryptocurrency Ticker
    - Can track the price of several cryptocurriences by utilizing the Canvas and WebSocket API
    - Can cycle between different coin tickers, updating and clearing the canvas each time

## Features
- Japanese eLearning
    - Definition Practice
        - select the word out of a list of 6 that matches the definition
        - toggle hiragana on/off above the kanji
    - Hiragana Practice
        - type the correct hiragana for each given word
    - Japanese Practice
        - type the correct hiragana for each given word
    - Word List

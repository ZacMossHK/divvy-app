# Divvy

Divvy is a mobile bill-splitting app for calculating group meal costs in restaurants developed as a group project at Makers Academy. Users can take a photo of a receipt and the app will turn itemise the meals on the app. These meals can then be assigned to friends and a totals screen will show the cost breakdown. Charge alterations or additions (tips, service charges, taxes, discounts) can be added and this cost will be reflected.

[Click here to see a recording of using Divvy.](https://vimeo.com/765971766)

Divvy uses the following tech stack:

- Javascript & React Native: We wanted to build on our Javascript knowledge throughout the course and were keen to explore React. Since we decided on a mobile app we chose React Native.
- Expo: For ease of deployment to simulators and to devices
- Realm: Offline-first NoSQL database system that does not require an internet connection.
- Taggun: OCR API for itemsing receipts.
- Node.js
- CSS

Divvy was designed as an iOS app and may not run properly on Android or Windows.

To install:

```
npm i
```

To run:
```
expo run:ios -d
```
When asked for the bundle identifier (this can be anything it is arbitrary)
```
i
```
then hit enter

```
select simulator: Iphone SE 3rd generation.
```
Then to run
```
npm start
```
---

[![License: MIT](https://img.shields.io/badge/License-MIT-A31F34.svg)](https://opensource.org/licenses/MIT)

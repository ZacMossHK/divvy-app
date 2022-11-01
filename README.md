# Divvy

#### Divvy is a mobile bill-splitting app for calculating group meal costs in restaurants developed as a group project at Makers Academy.

Users can take a photo of a receipt and the app will turn itemise the meals on the app. These meals can then be assigned to friends and a totals screen will show the cost breakdown. Charge alterations or additions (tips, service charges, taxes, discounts) can be added and this cost will be reflected.

Although an internet connection is required to itemise receipts, Divvy is otherwise designed to work without an internet connection in situations where the user has poor receiption such as inside a building. 

<div style= "display:inline-block;">
<img src="https://user-images.githubusercontent.com/63399205/199167498-62f5fd97-1900-4030-96c7-28c701e87f8f.png" width="20%"/>
<img src="https://user-images.githubusercontent.com/63399205/199167523-a486478a-4774-4dc1-b1c0-84368648ae42.png" width="20%"/>
<img src="https://user-images.githubusercontent.com/63399205/199167540-fd8ee095-2405-4839-b435-aa7742b1b13a.png" width="20%"/>
<img src="https://user-images.githubusercontent.com/63399205/199167555-c51bd8ea-2d1f-40c1-85cf-59f6c56264e6.png" width="20%"/>
</div>

## Tech

Divvy uses the following tech stack:

- Javascript & React Native: We wanted to build on our Javascript knowledge throughout the course and were keen to explore React. Since we decided on a mobile app we chose React Native.
- Expo: For ease of deployment to simulators and to devices
- Realm: Offline-first NoSQL database system that does not require an internet connection.
- Taggun: OCR API for itemsing receipts.
- Node.js
- CSS

Divvy was designed as an iOS app and may not run properly on Android or Windows.

As part of integrating Realm into Divvy I wrote [this README](https://github.com/ZacMossHK/realm-how-to) on how to install it, as well as further documentation on how to use Realm.

## Installation

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

## Recordings

A complete user flow using Divvy:

https://user-images.githubusercontent.com/63399205/199172078-338f7cce-bb3d-4b96-9aed-c7eeccaefd64.mp4

[Click here to see a recording of Divvy running on an iPhone.](https://vimeo.com/765974989)

[Click here to see us present Divvy as part of our final group project at Makers.](https://youtu.be/zRn2Lerc43c?t=946)

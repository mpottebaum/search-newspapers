# Search Newspapers

Description

[Full Demo](https://www.youtube.com/watch?v=SFXISEKAEYI)

![Search Newspapers demo](https://j.gifs.com/WLy7JW.gif)

Tech Specs

## Installing Search Newspapers

The Xcode iOS simulator is required to run this app.

To install Search Newspapers, follow these steps:

1. Clone the full contents of this repo and its submodules

```
git clone --recurse-submodules git@github.com:mpottebaum/search-newspapers.git
```

2. Install gems in the back end directory:

```
cd search-newspapers-api
bundle
```

3. Install dependencies in the front end directory:

```
cd SearchNewspapers
npm install
```

## Using Search Newspapers

To use Search Newspapers, follow these steps:

1. From the search-newspapers-api directory, start the API server.

```
rails s
```

2. From the SearchNewspapers directory, start the iOS simulator.

```
npx react-native run-ios
```

## Contact

If you want to contact me you can reach me at mpottebaum@gmail.com.
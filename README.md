# Search Newspapers

Search Newspapers allows iOS users to search [Chronicling America's API](https://chroniclingamerica.loc.gov/about/api/) of historic newspapers and save their favorite pages.

[Full Demo](https://www.youtube.com/watch?v=SFXISEKAEYI)

![Search Newspapers demo](https://j.gifs.com/WLy7JW.gif)

I built this app using React Native with Redux and Redux Thunk to manage state. I styled the components using only custom style. I tested the components with unit and snapshot tests using Jest with React Renderer and Redux Mock Store.

I built my own API using Rails to allow users to save interesting newspaper pages they find. I then utilized AsyncStorage in React Native to store user info client-side and allow user login to be persisted between sessions.

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
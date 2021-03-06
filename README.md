demo [here](https://live-newsapi.floriansr.vercel.app/)

## Specs 

- [x] This webapp displays the last 4 results available on [NewsAPI](https://newsapi.org/)
- [x] Each result is displayed as: One image + title.
- [x] When you click on a news, the description of the news appears in full-page (the other news are displayed in transparency behind). 
- [x] Clicking anywhere returns to the previous state. 
- [x] There is no "refresh" button on the webapp: the webapp refreshes its news by itself (it's up to you to see how you want to manage it).

## Local installation

```
git clone https://github.com/floriansr/live-newsapi.git
```

```
touch .env.local
```

```
NEXT_PUBLIC_NEWSAPI_KEY = <APINEWSKEY>
```

```
yarn && yarn build && yarn dev
```

## Author

-   **@floriansr** - [GitHub](https://github.com/floriansr)
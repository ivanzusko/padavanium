# List Show More

## Task
You will create a list of items(e.g. news) with this requirements:
- List should be responsive
- Show only 3 items at first (and 3 items each time when necessary to show more)
- Add possibility for user (add button 'Show more') to see more items
- Add possibility for user to enable/disable infinite scroll (when user scrolls all the way down the new items appear - 3 items each time)
- Add possibility to scroll all the way up (add button 'Scroll Top' with easing animation)

## The flow
First you will need local server (in order to be able to make request to `src/items.json`). This one is pretty simple: [http-server](https://www.npmjs.com/package/http-server)

First, install it globally:
```sh
npm i http-server -g
```
or if you are using __Yarn__ :
```sh
yarn global add http-server
```
Than clone this repo:
```sh
git clone https://github.com/ivanzusko/padavanium/list-show-more.git
```
and go inside the cloned folder:
```sh
cd list-show-more
```
After that you will need to create `index.html`.
Than run (if `index.html` stores in the same level with `src` folder):
```sh
http-server
```
or if you create `index.html` inside `src` folder:
```sh
cd src
http-server
```
After that go to `http://localhost:8080` and you will see your page.
Please, use `items.json` as a mock of remote server response. There are only three items, so every time user click "show more" button just show new items which are in fact just the same items were shown before.
Please, ensure that your `scroll to top` animation is working on all major browsers (IE11, Edge, last version of FireFox, Opera and Chrome).

And please... no __jQuery__ :)

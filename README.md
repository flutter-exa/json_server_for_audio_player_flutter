# Server for Apple Music / Tidal Style Audio Player for Flutter Project

- [Deploy to Heroku](#deploy-to-heroku)
- [Get Images](#get-images)
- [Get Audio](#get-audio)
- [FAQ](#faq)

## Deploy to Heroku

1 . [Create your database](#create-your-database)

2 . Create an account on <br/>[https://heroku.com](https://heroku.com)

3 . Install the Heroku CLI on your computer: <br/>[https://devcenter.heroku.com/articles/heroku-cli](https://devcenter.heroku.com/articles/heroku-cli)

4 . Connect the Heroku CLI to your account by writing the following command in your terminal and follow the instructions on the command line:

```bash
heroku login
```

5 . Then create a remote heroku project, kinda like creating a git repository on GitHub. This will create a project on Heroku with a random name. If you want to name your app you have to supply your own name like `heroku create project-name`:

```bash
heroku create my-cool-project
```

6 . Push your app to **Heroku** (you will see a wall of code)

```bash
git push heroku master
```

7 . Visit your newly create app by opening it via heroku:

```bash
heroku open
```

8 . For debugging if something went wrong:

```bash
heroku logs --tail
```

## Get Images

```txt
http://localhost:4000/assets/images/1.png

https://api-flutter-audio-player.herokuapp.com/assets/images/5.png

```

## Get Audio

```txt
http://localhost:4000/assets/audio/bensound-erf.mp3

https://api-flutter-audio-player.herokuapp.com/assets/audio/bensound-erf.mp3
```

Get DB

```txt
http://localhost:4000/db
```

## FAQ

Read more: [https://github.com/typicode/json-server](https://github.com/typicode/json-server)

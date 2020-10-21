Forked from https://github.com/heroku/button-sample.

## Breakage and mitigation tests

HTML Button (broken):

<a href="https://heroku.com/deploy" referrerpolicy="no-referrer-when-downgrade"><img src="https://www.herokucdn.com/deploy/button.png" alt="Run on Google Cloud"></a>

Markdown Button (broken):

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Referrer-Policy test - cross-origin image

<img src="https://i.imgur.com/XArLydn.jpg" width=140 height=140 />

## Referrer-Policy test - navigation

<a href="https://example.com">Click me!</a>

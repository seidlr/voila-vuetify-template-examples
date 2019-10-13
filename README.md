# voila-vuetify-template-examples
Try it directly on Binder.
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/seidlr/voila-vuetify-template-examples/master?urlpath=voila%2Frender%2Fvoila-vuetify-examples.ipynb)

This repository shows how you can create complex vuetify components using `ipyvuetify` templates.

## Usage

```
voila voila-vuetify-examples.ipynb --template=vuetify-baseline
```

Or for the dark theme:

```
voila voila-vuetify-examples.ipynb --template=vuetify-baseline --theme=dark
```

## Deployment on Heroku
You can easily deploy the notebook to Heroku following these steps: 
First, follow the setup steps on Heroku: [here](https://devcenter.heroku.com/articles/getting-started-with-python)
Then run
```bash
heroku create
git push heroku master
```


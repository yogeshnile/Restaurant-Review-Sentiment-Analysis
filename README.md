# Restaurant Review Sentiment Analysis :notebook: &nbsp;[![](https://camo.githubusercontent.com/17fa56d1fbad7bb4082c9711a77b984b85e79446/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f507974686f6e2d332e362d627269676874677265656e2e737667)](https://python.org)
In this repo i have develop a Sentiment Analysis of Restaurant Reviews project in machine learning using NLP, and i am using [nltk](https://pypi.org/project/nltk/) Library for NLP. Deployed in [heroku](https://www.heroku.com/).

 - [[Jupyter Notebook]](https://github.com/yogeshnile/Sentiment-Analysis-of-Restaurant-Reviews)
 - [[Live Demo]](https://restaurant-review-analysis.herokuapp.com)

[![](https://camo.githubusercontent.com/2fb0723ef80f8d87a51218680e209c66f213edf8/68747470733a2f2f666f7274686562616467652e636f6d2f696d616765732f6261646765732f6d6164652d776974682d707974686f6e2e737667)](https://python.org)

# Motivation :monocle_face:
  - Nowadays we all eat food in most of the restaurants, so it is necessary that we find the best restaurants, or the restaurant owner has to analysis the reviews of his customers that they are positive and negative. To know this, I have developed this project
  
# How to run the project? :thinking:
**1).** Run all command manually
  - Clone github repository in your local system  `git clone https://github.com/yogeshnile/Restaurant-Review-Sentiment-Analysis.git`
  - Move in Restaurant-Review-Sentiment-Analysis repository  `cd Restaurant-Review-Sentiment-Analysis`
  - Create new virtual python environment  `python3 -m venv venv`
  - Activate virtual python environment  `source venv/bin/activate`
  - Install all the libraries mentioned in [requirements.txt](https://github.com/yogeshnile/Restaurant-Review-Sentiment-Analysis/blob/master/requirements.txt)  using  `pip install -r requirements.txt`
  - Run FlaskApp file  `python app.py`
  - Go to your browser and type http://127.0.0.1:5000/ in the address bar.
  - Hurray! That's it. <br>


**2).** Run Shell Script
  - Clone github repository in your local system  `git clone https://github.com/yogeshnile/unix.git`
  - Give execute permission to [Restaurant-review-sentiment-analysis.sh](https://github.com/yogeshnile/unix/blob/master/Restaurant-review-sentiment-analysis.sh) file via  `chmod +x Restaurant-review-sentiment-analysis.sh`
  - Run Restaurant-review-sentiment-analysis.sh file using `./Restaurant-review-sentiment-analysis.sh`
  - Go to your browser and type http://127.0.0.1:5000/ in the address bar.
  - Finished...

# Directory Tree :cactus:
```bash
.
├── app.py
├── corpus.pkl
├── Images
│   ├── 1.png
│   ├── 2.png
│   ├── 3.png
│   └── 4.png
├── LICENSE
├── nltk.txt
├── Procfile
├── README.md
├── requirements.txt
├── Restaurant-reviews-model.pkl
├── Restaurant_Reviews.tsv
├── Sentiment Analysis of Restaurant Reviews.py
├── static
│   ├── css
│   │   └── main.css
│   ├── fonts
│   │   ├── font-awesome-4.7.0
│   │   │   ├── css
│   │   │   │   ├── font-awesome.css
│   │   │   │   └── font-awesome.min.css
│   │   │   ├── fonts
│   │   │   │   ├── FontAwesome.otf
│   │   │   │   ├── fontawesome-webfont.eot
│   │   │   │   ├── fontawesome-webfont.svg
│   │   │   │   ├── fontawesome-webfont.ttf
│   │   │   │   ├── fontawesome-webfont.woff
│   │   │   │   └── fontawesome-webfont.woff2
│   │   │   ├── HELP-US-OUT.txt
│   │   │   ├── less
│   │   │   │   ├── animated.less
│   │   │   │   ├── bordered-pulled.less
│   │   │   │   ├── core.less
│   │   │   │   ├── fixed-width.less
│   │   │   │   ├── font-awesome.less
│   │   │   │   ├── icons.less
│   │   │   │   ├── larger.less
│   │   │   │   ├── list.less
│   │   │   │   ├── mixins.less
│   │   │   │   ├── path.less
│   │   │   │   ├── rotated-flipped.less
│   │   │   │   ├── screen-reader.less
│   │   │   │   ├── stacked.less
│   │   │   │   └── variables.less
│   │   │   └── scss
│   │   │       ├── _animated.scss
│   │   │       ├── _bordered-pulled.scss
│   │   │       ├── _core.scss
│   │   │       ├── _fixed-width.scss
│   │   │       ├── font-awesome.scss
│   │   │       ├── _icons.scss
│   │   │       ├── _larger.scss
│   │   │       ├── _list.scss
│   │   │       ├── _mixins.scss
│   │   │       ├── _path.scss
│   │   │       ├── _rotated-flipped.scss
│   │   │       ├── _screen-reader.scss
│   │   │       ├── _stacked.scss
│   │   │       └── _variables.scss
│   │   ├── Linearicons-Free-v1.0.0
│   │   │   ├── icon-font.min.css
│   │   │   └── WebFont
│   │   │       ├── Linearicons-Free.eot
│   │   │       ├── Linearicons-Free.svg
│   │   │       ├── Linearicons-Free.ttf
│   │   │       ├── Linearicons-Free.woff
│   │   │       └── Linearicons-Free.woff2
│   │   └── OpenSans
│   │       ├── OpenSans-BoldItalic.ttf
│   │       ├── OpenSans-Bold.ttf
│   │       ├── OpenSans-ExtraBoldItalic.ttf
│   │       ├── OpenSans-ExtraBold.ttf
│   │       ├── OpenSans-Italic.ttf
│   │       ├── OpenSans-LightItalic.ttf
│   │       ├── OpenSans-Light.ttf
│   │       ├── OpenSans-Regular.otf
│   │       ├── OpenSans-Regular.ttf
│   │       ├── OpenSans-SemiBoldItalic.ttf
│   │       └── OpenSans-SemiBold.ttf
│   ├── images
│   │   └── icons
│   │       ├── favicon.ico
│   │       └── symbol-01.png
│   └── js
│       └── main.js
└── templates
    └── index.html

16 directories, 73 files
```
# Technology used in Project :hotsprings:
<img target="_blank" src="https://github.com/yogeshnile/technology/blob/master/Heroku.png" width="200">  <img target="_blank" src="https://github.com/yogeshnile/technology/blob/master/pandas.png" width="300">    <img target="_blank" src="https://github.com/yogeshnile/technology/blob/master/numpy.png" width="200">     <img target="_blank" src="https://github.com/yogeshnile/technology/blob/master/sklearn.png" width="200">    <img target="_blank" src="https://github.com/yogeshnile/technology/blob/master/Flask.png" width="300">    <img target="_blank" src="https://github.com/yogeshnile/technology/blob/master/python_nltk.png" width="190">

## ScreenShot :camera_flash:
![](https://github.com/yogeshnile/Restaurant-Review-Sentiment-Analysis/blob/master/Images/1.png)
![](https://github.com/yogeshnile/Restaurant-Review-Sentiment-Analysis/blob/master/Images/2.png)
![](https://github.com/yogeshnile/Restaurant-Review-Sentiment-Analysis/blob/master/Images/3.png)
![](https://github.com/yogeshnile/Restaurant-Review-Sentiment-Analysis/blob/master/Images/4.png)


## Bug / Feature Request :man_technologist:
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/yogeshnile/Restaurant-Review-Sentiment-Analysis/issues/new) by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/yogeshnile/Restaurant-Review-Sentiment-Analysis/issues/new). Please include sample queries and their corresponding results.


## Connect with me! 🌐
Known on internet as **Yogesh Nile**

[<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/linkedin.png" title="LinkedIn">](https://bit.ly/2Ky3ho6)  [<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/github.png" title="Github">](https://bit.ly/2yoggit) [<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/twitter.png" title="Twitter">](https://bit.ly/3dbLJLC) [<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/telegram-app.png" title="Telegram"/>](https://t.me/yogeshnile) [<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/instagram-new.png" title="Instagram">](https://bit.ly/3b9Qeo4)  [<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/instagram.png" title="Instagram Personal">](https://bit.ly/32SXHV0)

## Email Me :e-mail:

[<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/secured-letter.png" title="Mail me">](mailto:yogeshnile.work4u@gmail.com)

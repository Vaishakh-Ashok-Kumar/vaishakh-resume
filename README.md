<a href="https://jekyll-themes.com">
<img src="https://img.shields.io/badge/featured%20on-JT-red.svg" height="20" alt="Jekyll Themes Shield" >
</a>

> This theme is designed by Xiaoying Riley at [3rd Wave Media](http://themes.3rdwavemedia.com/).
> Visit [her website](http://themes.3rdwavemedia.com/) for more themes.

I have made this into a Jekyll Theme. Checkout the live demo [here](https://vaishakh-ashok-kumar.github.io/vaishakh-resume/).

## Installation

* [Fork](https://github.com/Vaishakh-Ashok-Kumar/vaishakh-resume/fork) the repository; 
* Go to settings and set master branch as Github Pages source;
* Your new site should be ready at `https://<username>.github.io/vaishakh-resume/`;
Change all the details from one place: `_data/data.yml`.

### To preview/edit locally with docker

```sh
docker-compose up
```

*docker-compose.yml* file is used to create a container that is reachable under <http://localhost:4000>.
Changes *_data/data.yml* will be visible after a while.

### Local machine

* Get the repo into your machine 

```bash
git clone https://github.com/Vaishakh-Ashok-Kumar/vaishakh-resume.git
```

* Install required ruby gems

```bash
bundle install
```

* Serve the site locally

```bash
bundle exec jekyll serve
```

* Navigate to `http://localhost:4000`




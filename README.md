# Setup

There are two parts to the setup:
1. Bookmark the [course page](https://github.com/knathanieltucker/data-science-foundations), and star/follow the repository
2. Either follow the instructions on the course page or the ones below:

Download the repo, and install the virtual env

```bash
git clone https://github.com/knathanieltucker/data-science-foundations.git
cd data-science-foundations
virtualenv env
source env/bin/activate
pip install -r requirements.txt
```

# Updates

Before each lesson make sure to update the repo by running the following commands:

```bash
git fetch origin
git rebase origin/master
```

# Slideshow

`jupyter nbconvert mynotebook.ipynb --to slides --post serve`

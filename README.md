# Henry Lab

We use Jekyll to run our Github page. This page is adopted and customized from [Kording lab page](http://kordinglab.com/).

## Run the page locally using Jekyll

To run locally, follow instruction [here](https://jekyllrb.com/) to install Jekyll then run `jekyll serve` to see in `localhost:4000`. Here is a brief install guidelines.

```bash
sudo gem install jekyll
sudo gem install rouge
jekyll serve
```

## Editing the lab website

Below, we explain how to edit the lab webpage

<!--### Add posts -->

<!--It's very easy to add post. All the posts are located in `_posts` folder. It arrangement is based on
date. Each post can be written in markdown format. You just have to state headers before writing: `title`, `description` and `categories`. `description` will be shown when you share on social media like Facebook or twitter. See the following headers: -->

<!--``` markdown -->
<!----- -->
<!--title: XXX workshop -->
<!--description: A robotics workshop -->
<!--categories: discussion-->
<!----- -->
<!--```-->

<!--We have 4 categories: `scientists`, `students`, `discussion`, `blog` you can choose and this will be rendered to different location.-->

<!--### How to add posts--> <!--Reserved this part in case we need a post section in the future! -->

<!-- - **Directly edit on Github**, you can simply go to `_posts` and click `New file` then put some markdown file e.g. `2016-02-03-post-name.md` and start writing blog post. Github also allows you to preview it so it's nice for people who don't want to clone the repo. -->

<!-- - **Clone the repository**, kind of the same as directly add post on Github. You just have to clone the repository. Then add new post file, commit and push to the repo.-->

<!-- The changes will take approximately half a minute to render. You can see the new posts or changes on the [website](http://henrychulab.github.io/)! -->


### Add yourself

You can add yourself to the page in `_people` folder just create file name `<firstname>_<lastname>.md` in the folder. We require few line of header before you start writing your own page. See the following for the header

``` markdown
---
name: Donald J. Trump
position: postdoc
avatar: trump.jpg
twitter:
joined: 2016
---
```

If you don't have information, just leave it blank. The avatar will bring photo from `images/people` folder and display it on people page. 
For lab position, you can choose position from several classes including `postdoc`, `phd`, `msc`, `visiting`, `ug`, `alumni`, and `others`. Position will put you into section that you choose.

### Add new publications

All publications from the lab are located in `publications.md`. Please upload new publication on your own with the unified format!

### Add news

All news presented in the front page by editing `_data/news.yml`. There are some symbol that cannot be used directly e.g. `:`, be careful

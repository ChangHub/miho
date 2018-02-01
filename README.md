# hexo-theme-miho

MiHo is a single and responsive design theme for [Hexo](//hexo.io).
MiHo requires Hexo 3.0 and above, Compatible with mobile browsing; Theme DEMO:[MinHow's Blog](http://blog.minhow.com/).
中文文档请[查看](http://blog.minhow.com/2017/08/01/blog/installation-configuration/).

### Installation Theme
``` bash
$ git clone https://github.com/WongMinHo/hexo-theme-miho.git themes/miho
```

### Update
``` bash
cd themes/miho
git pull
```

### Dependency installation
#### Json-content
Generate site articles static data for in-site search; detailed configuration please check [hexo-generator-json-content](https://github.com/alexbruno/hexo-generator-json-content).
``` bash
npm install hexo-generator-json-content --save
```

### Theme Config
Change theme field in Hexo root's `_config.yml` file.
``` bash
theme: miho
```

## Configuration
Modify settings in `themes/miho/_config.yml`，Please use it as needed.

#### Article cover picture
Article default cover picture，size：350*150, When the article configuration does not have cover_picture display.
``` bash
cover_picture: images/banner.jpg
```

#### Background particles
Whether to open background particles.
``` bash
open_bg_particle: true
```

#### Homepage and head animation
Whether to open homepage and head animation.
``` bash
open_animation: true
```

#### Analytics
Google analytics, Baidu analytics and cnzz analytics are supported.
``` bash
# 站长分析，输入站点id
cnzz_analytics: false
# 百度分析，输入key值
baidu_analytics: false
# google analytics | google分析
google_analytics: false
```

#### Comments
This theme support both Disqus and Changyan as the third party discussion system.
``` bash
# 畅言，输入appid和appkey
changyan_appid: false
changyan_appkey: false
# 友言，输入id
youyan_id: false
# disqus
disqus: false
```

### Article configuration example
``` bash
---
title: Hello World
date: 2017-06-18
categories: First
tags:
    - First
    - Second
cover_picture: /images/banner.jpg
---
 MinHow-This is a summary
<!-- more -->
```

## Contributing
All kinds of contributions (enhancements, new features, documentation & code improvements, issues & bugs reporting) are welcome.

## License
Open sourced under the GPL v3.0 license.



---
layout: page
homepage: true
---

# Will Liu

我是一個很大腦思考型的人物，也是為什麼我用 **「左腦諮商師」** 陳述我自己，曾經困惑、不敢相信身心靈工具以及所有神秘學的力量可能成真，直到親身體驗過才發現，不管是要用右腦的體驗方式，還是想要用左腦慢慢的思考因過關係，身、心、靈都是可以完整被詮釋，也能夠以不同的方式理解。

我相信每一個人都是自已生命的主人！因為自己跌倒過、受傷過也才有機會使用不同的工具走過，想透過自己的經驗融合各種工具的優點，幫助到每個人能夠在卡關的時候跨越障礙，看到不同的人生面貌以及找到自己內心真實渴望的方向。 希望幫助每一個人看清自己的問題；拿回自己的力量；完成屬於自己的渴望。

# 經歷

Add this line to your Jekyll site's Gemfile:

```ruby
gem "jekyll-docs-theme"
```

And add this line to your Jekyll site's _config.yml:

```yaml
theme: jekyll-docs-theme
```

And then execute:

```
$ bundle
```

Or install it yourself as:

```
$ gem install jekyll-docs-theme
```

<div class="alert alert-warning" markdown="1">
療癒工具僅是作為支持性使用，不具備任何醫療特性以及效用，因此無法取代正統醫療。若有需求，請務必要尋求專業醫師之協助。
</div>

# Configuration Options

A sample [`_config.yml`](https://github.com/allejo/jekyll-docs-theme/blob/master/docs/_config.yml) file is available with all of the available fields; documentation and more information for each of those fields is available below.

## Project

The project object can be specified with information related to the software this; this information will appear on the homepage's jumbotron area.

```yaml
project:
  version: 1.0.0
  download_url: https://github.com/USER/PROJECT/releases
```

{:.table}
| field | description |
| ----- | ----------- |
| `version` | The current version of the software |
| `download_url` | The URL to the current download |

## Licenses

The license object accepts four fields regarding information about the licensing of your software and documentation.

```yaml
license:
  software: MIT License
  software_url: http://opensource.org/licenses/MIT

  docs: CC BY 3.0
  docs_url: http://creativecommons.org/licenses/by/3.0/
```

{:.table}
| field | description |
| ----- | ----------- |
| `software` | The license the software is distributed under |
| `software_url` | A URL to the license text for the license specified in `software` |
| `docs` | The license this documentation is distributed under |
| `docs_url` | A URL to the license text for the license specified in `docs` |

## Links

The links object has two subobjects, `header` and `footer`; both of these objects accept an array of elements with a `title` and `url`. The links defined in the `header` object will appear in the navigation of the website and the links in the `footer` will appear at the bottom of the website.

```yaml
links:
  header:
    - title: GitHub
      url: https://github.com/allejo/jekyll-docs-theme
  footer:
    - title: GitHub
      url: https://github.com/allejo/jekyll-docs-theme
    - title: Issues
      url: https://github.com/allejo/jekyll-docs-theme/issues?state=open
```

{:.table}
| field | description |
| ----- | ----------- |
| `title` | The textual representation of the URL |
| `url` | The URL of the link |

## UI

The ui object will contain all the settings in regards to the aesthetics of the website

```yaml
ui:
  header:
    color1: "#080331"
    color2: "#673051"
    trianglify: true
```

{:.table}
| field | description |
| ----- | ----------- |
| `color1` & `color2` | The two colors that will create the gradient of the page header |
| `trianglify` | When set to true, the page header will be a generated triangular pattern |

## Analytics

```yaml
analytics:
    google: UA-123456-1
```

{:.table}
| field | description |
| ----- | ----------- |
| `google` | The unique identifier for Google Analytics; typically looks like `U-123456-1`

## Social

Options for configuring buttons to "like", "tweet" or "star" this site with the respective social media websites.

```yaml
social:
  github:
    user: allejo
    repo: jekyll-docs-theme
  twitter:
    enabled: false
    via:
    hash:
    account:
  facebook:
    enabled: false
    profileUrl:
```

# [Minimal Mistakes Jekyll theme](https://mmistakes.github.io/minimal-mistakes/)

[![LICENSE](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://raw.githubusercontent.com/mmistakes/minimal-mistakes/master/LICENSE)
[![Jekyll](https://img.shields.io/badge/jekyll-%3E%3D%203.7-blue.svg)](https://jekyllrb.com/)
[![Ruby gem](https://img.shields.io/gem/v/minimal-mistakes-jekyll.svg)](https://rubygems.org/gems/minimal-mistakes-jekyll)
[![Tip Me via PayPal](https://img.shields.io/badge/PayPal-tip%20me-green.svg?logo=paypal)](https://www.paypal.me/mmistakes)

Minimal Mistakes is a flexible two-column Jekyll theme, perfect for building personal sites, blogs, and portfolios. As the name implies, styling is purposely minimalistic to be enhanced and customized by you :smile:.

:sparkles: See what's new in the [CHANGELOG](CHANGELOG.md).

**If you enjoy this theme, please consider [supporting me](https://www.paypal.me/mmistakes) to continue developing and maintaining it.**

[![Support via PayPal](https://cdn.jsdelivr.net/gh/twolfson/paypal-github-button@1.0.0/dist/button.svg)](https://www.paypal.me/mmistakes)

**Note:** The theme uses the [jekyll-include-cache](https://github.com/benbalter/jekyll-include-cache) plugin which will need to be installed in your `Gemfile` and added to the `plugins` array of `_config.yml`. Otherwise you'll encounter `Unknown tag 'include_cached'` errors at build.

[![Minimal Mistakes live preview][2]][1]

[1]: https://mmistakes.github.io/minimal-mistakes/
[2]: screenshot.png (live preview)

![layout examples](screenshot-layouts.png)

## Notable features

- Bundled as a "theme gem" for easier installation/upgrading.
- Compatible with GitHub Pages.
- Support for Jekyll's built-in Sass/SCSS preprocessor.
- Nine different skins (color variations).
- Several responsive layout options (single, archive index, search, splash, and paginated home page).
- Optimized for search engines with support for [Twitter Cards](https://dev.twitter.com/cards/overview) and [Open Graph](http://ogp.me/) data.
- Optional [header images](https://mmistakes.github.io/minimal-mistakes/docs/layouts/#headers), [custom sidebars](https://mmistakes.github.io/minimal-mistakes/docs/layouts/#sidebars), [table of contents](https://mmistakes.github.io/minimal-mistakes/docs/helpers/#table-of-contents), [galleries](https://mmistakes.github.io/minimal-mistakes/docs/helpers/#gallery), related posts, [breadcrumb links](https://mmistakes.github.io/minimal-mistakes/docs/configuration/#breadcrumb-navigation-beta), [navigation lists](https://mmistakes.github.io/minimal-mistakes/docs/helpers/#navigation-list), and more.
- Commenting support (powered by [Disqus](https://disqus.com/), [Facebook](https://developers.facebook.com/docs/plugins/comments), Google+, [Discourse](https://www.discourse.org/), static-based via [Staticman](https://staticman.net/), and [utterances](https://utteranc.es/)).
- [Google Analytics](https://www.google.com/analytics/) support.
- UI localized text in English (default), Brazilian Portuguese (Português brasileiro), Catalan, Chinese, Danish, Dutch, Finnish, French (Français), German (Deutsch), Greek, Hebrew, Hindi (हिंदी), Hungarian, Indonesian, Irish (Gaeilge), Italian (Italiano), Japanese, Korean, Malayalam, Myanmar (Burmese), Nepali (Nepalese), Norwegian (Norsk), Persian (فارسی), Polish, Punjabi (ਪੰਜਾਬੀ), Romanian, Russian, Slovak, Spanish (Español), Swedish, Thai, Turkish (Türkçe), and Vietnamese.

## Skins (color variations)

This theme comes in nine different skins (in addition to the default one).

| `air` | `contrast` | `dark` |
| --- | --- | --- |
| [![air skin](https://mmistakes.github.io/minimal-mistakes/assets/images/air-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/air-skin-archive-large.png) | [![contrast skin](https://mmistakes.github.io/minimal-mistakes/assets/images/contrast-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/contrast-skin-archive-large.png) | [![dark skin](https://mmistakes.github.io/minimal-mistakes/assets/images/dark-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/dark-skin-archive-large.png) |

| `dirt` | `mint` | `sunrise` |
| --- | --- | --- |
| [![dirt skin](https://mmistakes.github.io/minimal-mistakes/assets/images/dirt-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/dirt-skin-archive-large.png) | [![mint skin](https://mmistakes.github.io/minimal-mistakes/assets/images/mint-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/mint-skin-archive-large.png) | [![sunrise skin](https://mmistakes.github.io/minimal-mistakes/assets/images/sunrise-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/sunrise-skin-archive-large.png) |

| `aqua` | `neon` | `plum` |
| --- | --- | --- |
| [![aqua skin](https://mmistakes.github.io/minimal-mistakes/assets/images/aqua-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/aqua-skin-archive-large.png) | [![neon skin](https://mmistakes.github.io/minimal-mistakes/assets/images/neon-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/neon-skin-archive-large.png) | [![plum skin](https://mmistakes.github.io/minimal-mistakes/assets/images/plum-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/plum-skin-archive-large.png) |

## Demo pages

| Name                                        | Description                                           |
| ------------------------------------------- | ----------------------------------------------------- |
| [Post with Header Image][header-image-post] | A post with a large header image. |
| [HTML Tags and Formatting Post][html-tags-post] | A variety of common markup showing how the theme styles them. |
| [Syntax Highlighting Post][syntax-post] | Post displaying highlighted code. |
| [Post with a Gallery][gallery-post] | A post showing several images wrapped in `<figure>` elements. |
| [Sample Collection Page][sample-collection] | Single page from a collection. |
| [Categories Archive][categories-archive] | Posts grouped by category. |
| [Tags Archive][tags-archive] | Posts grouped by tag. |

Additional sample posts are available under [posts archive][year-archive] on the demo site. Source files for these (and the entire demo site) can be found in [`/docs`](docs).

[header-image-post]: https://mmistakes.github.io/minimal-mistakes/layout-header-image-text-readability/
[gallery-post]: https://mmistakes.github.io/minimal-mistakes/post%20formats/post-gallery/
[html-tags-post]: https://mmistakes.github.io/minimal-mistakes/markup/markup-html-tags-and-formatting/
[syntax-post]: https://mmistakes.github.io/minimal-mistakes/markup-syntax-highlighting/
[sample-collection]: https://mmistakes.github.io/minimal-mistakes/recipes/chocolate-chip-cookies/
[categories-archive]: https://mmistakes.github.io/minimal-mistakes/categories/
[tags-archive]: https://mmistakes.github.io/minimal-mistakes/tags/
[year-archive]: https://mmistakes.github.io/minimal-mistakes/year-archive/

## Installation

There are three ways to install: as a [gem-based theme](https://jekyllrb.com/docs/themes/#understanding-gem-based-themes), as a [remote theme](https://blog.github.com/2017-11-29-use-any-theme-with-github-pages/) (GitHub Pages compatible), or forking/directly copying all of the theme files into your project.

### Gem-based method

With Gem-based themes, directories such as the `assets`, `_layouts`, `_includes`, and `_sass` are stored in the theme’s gem, hidden from your immediate view. Yet all of the necessary directories will be read and processed during Jekyll’s build process.

This allows for easier installation and updating as you don't have to manage any of the theme files. To install:

1. Add the following to your `Gemfile`:

   ```ruby
   gem "minimal-mistakes-jekyll"
   ```

2. Fetch and update bundled gems by running the following [Bundler](http://bundler.io/) command:

   ```bash
   bundle
   ```

3. Set the `theme` in your project's Jekyll `_config.yml` file:

   ```yaml
   theme: minimal-mistakes-jekyll
   ```

To update the theme run `bundle update`.

### Remote theme method

Remote themes are similar to Gem-based themes, but do not require `Gemfile` changes or whitelisting making them ideal for sites hosted with GitHub Pages.

To install:

1. Create/replace the contents of your `Gemfile` with the following:

   ```ruby
   source "https://rubygems.org"

   gem "github-pages", group: :jekyll_plugins
   gem "jekyll-include-cache", group: :jekyll_plugins
   ```

2. Add `jekyll-include-cache` to the `plugins` array of your `_config.yml`.

3. Fetch and update bundled gems by running the following [Bundler](http://bundler.io/) command:

   ```bash
   bundle
   ```

4. Add `remote_theme: "mmistakes/minimal-mistakes@4.22.0"` to your `_config.yml` file. Remove any other `theme:` or `remote_theme:` entry.

**Looking for an example?** Use the [Minimal Mistakes remote theme starter](https://github.com/mmistakes/mm-github-pages-starter/generate) for the quickest method of getting a GitHub Pages hosted site up and running. Generate a new repository from the starter, replace sample content with your own, and configure as needed.

## Usage

For detailed instructions on how to configure, customize, add/migrate content, and more read the [theme's documentation](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/).

---

## Contributing

Found a typo in the documentation or interested in [fixing a bug](https://github.com/mmistakes/minimal-mistakes/issues)? Then by all means [submit an issue](https://github.com/mmistakes/minimal-mistakes/issues/new) or [pull request](https://help.github.com/articles/using-pull-requests/). If this is your first pull request, it may be helpful to read up on the [GitHub Flow](https://guides.github.com/introduction/flow/) first.

For help with using the theme or general Jekyll support questions, please use the [Jekyll Talk forums](https://talk.jekyllrb.com/).

### Pull Requests

When submitting a pull request:

1. Clone the repo.
2. Create a branch off of `master` and give it a meaningful name (e.g. `my-awesome-new-feature`).
3. Open a pull request on GitHub and describe the feature or fix.

Theme documentation and demo pages can be found in the [`/docs`](docs) if submitting improvements, typo corrections, etc.

## Development

To set up your environment to develop this theme, run `bundle install`.

To test the theme, run `bundle exec rake preview` and open your browser at `http://localhost:4000/test/`. This starts a Jekyll server using content in the `test/` directory. As modifications are made to the theme and test site, it will regenerate and you should see the changes in the browser after a refresh.

---

## Credits

### Creator

**Michael Rose**

- <https://mademistakes.com>
- <https://twitter.com/mmistakes>
- <https://github.com/mmistakes>

### Icons + Demo Images:

- [The Noun Project](https://thenounproject.com) -- Garrett Knoll, Arthur Shlain, and [tracy tam](https://thenounproject.com/tracytam)
- [Font Awesome](http://fontawesome.io/)
- [Unsplash](https://unsplash.com/)

### Other:

- [Jekyll](http://jekyllrb.com/)
- [jQuery](http://jquery.com/)
- [Susy](http://susy.oddbird.net/)
- [Breakpoint](http://breakpoint-sass.com/)
- [Magnific Popup](http://dimsemenov.com/plugins/magnific-popup/)
- [FitVids.JS](http://fitvidsjs.com/)
- [GreedyNav.js](https://github.com/lukejacksonn/GreedyNav)
- [Smooth Scroll](https://github.com/cferdinandi/smooth-scroll)
- [Gumshoe](https://github.com/cferdinandi/gumshoe)
- [jQuery throttle / debounce](http://benalman.com/projects/jquery-throttle-debounce-plugin/)
- [Lunr](http://lunrjs.com)

---

## License

The MIT License (MIT)

Copyright (c) 2013-2020 Michael Rose and contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Minimal Mistakes incorporates icons from [The Noun Project](https://thenounproject.com/) 
creators Garrett Knoll, Arthur Shlain, and tracy tam.
Icons are distributed under Creative Commons Attribution 3.0 United States (CC BY 3.0 US).

Minimal Mistakes incorporates [Font Awesome](http://fontawesome.io/),
Copyright (c) 2017 Dave Gandy.
Font Awesome is distributed under the terms of the [SIL OFL 1.1](http://scripts.sil.org/OFL) 
and [MIT License](http://opensource.org/licenses/MIT).

Minimal Mistakes incorporates photographs from [Unsplash](https://unsplash.com).

Minimal Mistakes incorporates [Susy](http://susy.oddbird.net/),
Copyright (c) 2017, Miriam Eric Suzanne.
Susy is distributed under the terms of the [BSD 3-clause "New" or "Revised" License](https://opensource.org/licenses/BSD-3-Clause).

Minimal Mistakes incorporates [Breakpoint](http://breakpoint-sass.com/).
Breakpoint is distributed under the terms of the [MIT/GPL Licenses](http://opensource.org/licenses/MIT).

Minimal Mistakes incorporates [FitVids.js](https://github.com/davatron5000/FitVids.js/),
Copyright (c) 2013 Dave Rubert and Chris Coyier.
FitVids is distributed under the terms of the [WTFPL License](http://www.wtfpl.net/).

Minimal Mistakes incorporates [Magnific Popup](http://dimsemenov.com/plugins/magnific-popup/),
Copyright (c) 2014-2016 Dmitry Semenov, http://dimsemenov.com.
Magnific Popup is distributed under the terms of the MIT License.

Minimal Mistakes incorporates [Smooth Scroll](http://github.com/cferdinandi/smooth-scroll),
Copyright (c) 2019 Chris Ferdinandi.
Smooth Scroll is distributed under the terms of the [MIT License](http://opensource.org/licenses/MIT).

Minimal Mistakes incorporates [Gumshoejs](http://github.com/cferdinandi/gumshoe),
Copyright (c) 2019 Chris Ferdinandi.
Smooth Scroll is distributed under the terms of the [MIT License](http://opensource.org/licenses/MIT).

Minimal Mistakes incorporates [jQuery throttle / debounce](http://benalman.com/projects/jquery-throttle-debounce-plugin/),
Copyright (c) 2010 "Cowboy" Ben Alman.
jQuery throttle / debounce is distributed under the terms of the [MIT License](http://opensource.org/licenses/MIT).

Minimal Mistakes incorporates [GreedyNav.js](https://github.com/lukejacksonn/GreedyNav),
Copyright (c) 2015 Luke Jackson.
GreedyNav.js is distributed under the terms of the [MIT License](http://opensource.org/licenses/MIT).

Minimal Mistakes incorporates [Jekyll Group-By-Array](https://github.com/mushishi78/jekyll-group-by-array),
Copyright (c) 2015 Max White <mushishi78@gmail.com>.
Jekyll Group-By-Array is distributed under the terms of the [MIT License](http://opensource.org/licenses/MIT).

Minimal Mistakes incorporates [@allejo's Pure Liquid Jekyll Table of Contents](https://allejo.io/blog/a-jekyll-toc-in-liquid-only/),
Copyright (c) 2017 Vladimir Jimenez.
Pure Liquid Jekyll Table of Contents is distributed under the terms of the [MIT License](http://opensource.org/licenses/MIT).

Minimal Mistakes incorporates [Lunr](http://lunrjs.com),
Copyright (c) 2018 Oliver Nightingale.
Lunr is distributed under the terms of the [MIT License](http://opensource.org/licenses/MIT).

# Mun Jihyeon (A.k.a Moonji)

> "배는 항구에 정박할 때 가장 안전하지만 그것은 배의 존재 이유가 아니다"

스타트업을 발전시켜나가는 스타트업 개발자를 꿈꾸는 문지현입니다.

저는 학창시절 **"스티브잡스 평전", 영화 "소셜 네트워크"** ,등으로 
**스타트업->스케일업->스테일러->유티콘->데카콘**으로 성장시켜가는 창업가를 꿈꿨으며,

모진 상황과 역경 속에서도 위대한 성공과 성과를 이뤄낸 한인들을 다룬 KBS 다큐멘터리 **"글로벌 성공시대"**를 보며, 
한인으로서 성공하는 기업가가 되고 싶었습니다. 

저의 모교를 사랑했고 이를 알리고 싶었기에, 
대학교 1학년, UNIST 학교 홍보대사인 **UNI**라는 단체에서 홍보대사를 하였으며,
(200회에 이르는 캠퍼스 투어, 의전,입학식,졸업식 등을 포함하는 각종 학교행사, 등을 진행하며,
많은 역량을 강화할 수 있었습니다. )

사회적 기업가로서 사회적 가치에 대해 궁금해서 2013년에는 **Enactus UNIST**를 활동하며
2014년(01~08월)에는 회장을 하였습니다. 

그 이후 군대에 입대하고 전역한 뒤,
학생 사회에 대해서 혁신이 필요하다고 판단하고, 
**전기전자컴퓨터공학부 학생회**에서 각종 TF 팀장을 도맡으며 
교수, 학생, 행정팀을 사이에서 중재자 역할을 맡으며, 
학사 등의 문제등을 해결하고 학부의 행사에 대한 전반적인 기획 및 운영을 진행하면서 왔습니다. 

이와 함께, 학교의 각종 행사
(**울산시 드림캠프, 울주군 이공계 대탐험, Explorer @ Unist, UNIST 오리엔테이션, 인문학 페스티벌**, 등)에서 
멘토(생활멘토장), 스태프 총괄, 등을 맡으며, 행사 관리자의 역할을 하며, 시스템을 잘 기획한 뒤에, 
혹시나 문제(에러)가 발생하면, 적극적으로 개입해가면서 
**시스템 문제, 의견충돌, 멘토-멘티 갈등 등을 조율**해가는 역할을 해왔습니다. 

이렇게 학교 생활에 대해서 장황하게 말씀드리는 이유는, 이러한 체험과 경험들이 저를 만드는 근간이 되었기 때문입니다. 

####1) 시스템을 체험해보고, 
####2) 시스템의 문제를 파악하고, 
####3) 시스템의 관리자가 되어 시스템을 설계 및 구현하고
####4) 시스템의 오작동을 파악하여 실제로 수정해나가고,
####5) 꾸준히 유지/보수를 진행하며, 피드백을 받고,

이러한 프로세스가 너무도 좋았고, 
동일한 성향을 띄는 것이 `프로그래밍 그리고 스타트업`이란 것도 알고 있었습니다. 

하지만, 
1학년 당시만 하더라도, `Engineering Programming`이라는 수업을 들으며,
매주 살벌한 진도와 (너무나도 어렵다고 느껴졌던)실습들이 막연하게 다가왔고,
어린 나이였기에 
>"나와는 맞지 않아, 나는 스타트업을 컴퓨터공학보다는 전기전자공학으로 가는 게 취업이든 창업이든 두마리 토끼를 다 잡을 수 있을거야! "

라고 생각하며, 컴퓨터공학과가 아닌 전자공학과를 선택하게 되었습니다. 

하지만, 이렇게 현실에 타협한 저의 선택들은 항상 저에게 후회를 안겼습니다. 

회로, 소자, 통신, RF/EMC, 신호처리, 제어 등에 관한 과목등을 들으며, 
시스템을 설계하고 구현하는 것을 좋아하던 저에게 전자공학과의 대부분의 과목들이나
연구분야는 부품 개발로 다가오곤 했습니다. 부품 자체도 어떻게 보면 시스템일 수 있겠지만, 

유저의 피드백을 살펴보며, 계속해서 발전해가는 시스템이 훨씬 더 매력적이고, 
전자공학과 자체는 우리나라의 기성 대기업에 취직하기는 쉬울지 몰라도, 

제가 필요하다고 느꼈던, 불편하다고 느꼈지만 그러한 불편이 당연하다고 여겨졌던 부분을
개선해나가고 발전시켜나가면서 이를 수익이 갖는 사업 모델 성장시켜나가는 스타트업씬에 대한 
확신에 찬 기대가 있었기에, 

코로나 & 경제 불황 등으로 취직이 어려운 2020년 12월보다 아주 좋은 분위기였던 
2018년 하반기인 2018년 6월경 대기업보다는 **기술 창업을 위한 저의 전문성**을 갖추기 위해서
UNIST 석박통합과정으로 통신 시스템 설계를 위해서 **안테나**를 연구하게 되었습니다.

하지만, 
1. 국내 학계는 과제에 치중된 연구, 
2. 부품개발에 편중된 과제 비중, 
3. (적성에 맞지도 않았고, 전망도 불확실한) 바이오 센서 연구 분야, 
4. 나와는 맞지 않을 방산 분야 등 복합적인 이유 등으로 인해서
6년으로 예상되어 있던 석박 통합과정 생활에서 1년 반 동안의 시기를 보낸 뒤 쉼표를 찍었습니다. 

이후, 
>"당신이 할 수 있거나 할 수 있다고 꿈꾸는 그 모든 일을 시작하라. 새로운 일을 시작하는 용기속에 당신의 천재성과 능력, 그리고 기적이 모두 숨어 있다. - 괴테" 

라는 말처럼 저의 용기를 발판 삼아서, **Python, Java, Spring, MySQL, OPENCV, Aduino, 인공지능 웹개발** 등을 복합적으로 배우며, 이 중 저에게 맞는 포지션은 무엇인지, 내가 잘하고 좋아하고 적성에 맞는 것인지 찾아갈 수 있도록 하기 위해 
2020년 10월~2021년 04월까지 **"영상처리를 위한 인공지능 SW 개발자 양성과정"**(주관 : 플레이 데이터)을 이수하고 있습니다. 

이 시기 동안 제가 부족하다고 여겨졌던, 앞으로 필요하다고 느껴질 것 같은,
그리고 국내 IT 대기업에 들어가기 위한 코딩테스트(알고리즘 & 과제), 기술 면접(컴퓨터 공학 5대 과목), 포트폴리오 등을 전반적으로 준비해나가고 있습니다. 

이를 통해서 어릴적부터 제가 꿈꿔왔던 **개발자+기획자+디자이너**가 될 수 있도록 
도메인 지식 측면에서는 각종 커뮤니티에 가입하여 **T자형 인재**가 되면서,
업무 역량 측면에서는 
1. 실제 업무 투입이 가능할 정도로 많은 경험과 이해를 갖춰 나가고,
2. 새로운 업무가 주어져도, 아는 것과 모르는 것의 경계를 명확히 구분하여, 
모르는 부분은 최대한 검색하거나 물어보며 내 것으로 만들면서
모르는 것을 아는 것으로 전이시켜 나가며,
3. 모두와 원만한 관계를 유지하여 개발자, 기획자, 디자이너, 마케티, 등과도 원활한 소통이 가능하여,
떄로는 조언을 받고, 때로는 조언을 해주기도 하는 관계로 성장시켜 나가며,
4. 회사의 비전, 미션, 방향성을 생각하며, 큰그림을 그리고, 더 높게 성장할 수 있도록 하는
제안을 할 수 있는 아이디어 뱅커, 행동가, 혁신 경영가로서 
성장해나가고 싶습니다.  

>세상엔 어쩌면 편리와 불편 둘 중에 하나인 거 같습니다.

>불편한 것에 대해서 불평을 갖지 않고 참고 견디는 것이 사회의 미덕이었지만,
우리에게 불편한 것이 당연하다고 여겨졌던 것들이 편리해지는 과정에서
모두에게 유익한 가치를 선사하고, 모두의 효율성을 증대시키고,
그 과정에서 사업 모델이 된다는 것이 발견된다는 것 만으로도
이 개발자 씬은 너무도 매력적인 것 같습니다. 
현재는, 정말 아무것도 없는 주니어 개발자에 불과하지만,
더 높게 더크게 성장할 수 있는 발판이 될 수 있도록 달려나가겠습니다.

**연락은 jhmoon1994@gmail.com**

- [Github](https://github.com/jihyeonmun)

## 기술 스택
- 



## Education

- **PLAYDATA 영상처리를 위한 인공지능 SW 개발자 양성과정** 2020.10 ~ 2021.04(진행중)
- **UNIST 정보바이오융합대학  전기전자공학과  석박통합과정** 2019 ~ 2020(휴학중)
- **UNIST 전기전자컴퓨터공학부 전기전자/제어설계 트랙융합전공** 2013 ~ 2018
- **광주동신고등학교**, 2011 ~ 2013
- **광주고려중학교**, 2008 ~ 2010
- **광주광덕중학교**, 2007 ~ 2008

## Military Service
- **육군 제3군수지원사령부 1급양대 재정회계병(인사,동원,급양, 정보, 교육, 작전) 병장 만기 전역** 2014.09 ~ 2016.06

## Experience

- **UNIST 학생홍보대사 UNI 정식홍보대사** 2013.03 ~ 2014.06
- **UNIST 오티준비위원회 준비위원** 2014.01 ~ 2014.03
- **Enactus UNIST** 2013.03 ~ 2014.08
- **Enactus UNIST 회장** 2014.02 ~ 2014.06
- **UNIST 전기전자컴퓨터공학부 학사커리큘럼/행사 TF 팀장** 2016.09 ~ 2017.12
- **UNIST 인문학페스티벌 조장** (2013(스태프),2017(조장))
- **UNIST Explorer @ UNIST** (2013 하계(조장), 2017하계(조장), 2018 하계(스태프 총괄))
- **UNST 주관 울산시 드림캠프 생활멘토** (2016 하계, 2017동계, 2018 동계(멘토장))
- **UNIST 주관 이공계 대탐험 운영멘토** (2016, 2017)
- **UNIST 대학원총학생회 생활복지부장** 2020.01 ~ 2020.12
- **UNIST Antenna Technology Lab Chief** 2018.06 ~ 2019.12
- **UNIST 전자회로실험 TA Chief** 2019 Fall

## Certificate
- **데이터분석 준전문가 자격증 획득(ADsP)** 2020.11

## Awards

- 2020 한국전자파학회 하계 학술대회 **우수논문상** 수상
- 2019 한국전자파학회 추계학술대회  **우수논문상** 수상

## Current Interest
- Future Career Position
  - `Web Fullstack Developement`
  - `Data Engineering & Analyst`
  - `Server Engineering`

## Previoius or Current Project

|프로젝트명|프로젝트 기간|Github|서비스주소|
|:--:|:--:|:--:|:--:|
|코린이 커뮤니티|21.02~21.04|[Github](https://github.com/playdata-finalproject/teamproject_final)|[코린이대피소](http://13.209.116.217:8080/main)|
|(잠정서비스중단)유니스트 동문회 커뮤니티|20.11~20..12|[Github](https://github.com/jihyeonmun/UNIST_Homepages)|[유니스트 동문회 커뮤니티](http://)


### Community
- [UNIST 개발자 커뮤니티 ] **운영진**, 2020~ (100+)


## Press
- [서경덕 "욱일기=나치기, 세계에 알리자"](http://www.xportsnews.com/?ac=article_view&entry_id=1165829)
![욱일기](http://image.xportsnews.com/contents/images/upload/article/2019/0906/1567755311784303.jpg)


> 제가 구상한 "욱일기=나치기"인식 디자인이 실제 서경식 교수님이 채택하셔서 각종 기사가 올라왔던 경험이 있습니다.

## Contact

- Email

  - jhmoon1994@gmail.com

- Facebook : [문지현](https://www.facebook.com/jihyeon.moon.31)

- Github : [jihyeonmun](https://github.com/jihyeonmun)

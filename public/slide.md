---
marp: true
theme: custom
header: '**header**'
footer: '__footer__'
paginate: true
---

<!-- _class: invert -->

# 見出し

# 見出し 1

## 見出し 2

### 見出し 3

#### 見出し 4

##### 見出し 5

###### 見出し 6

---

# 太字/斜体

太字+斜体
**_text_**

太字
**text**

斜体
_text_

通常
text

---

# 箇条書き(順序なし)

- リスト 1
  - ネスト リスト 1_1
    - ネスト リスト 1_1_1
    - ネスト リスト 1_1_2
  - ネスト リスト 1_2
- リスト 2
- リスト 3

---

# 箇条書き(順序付き)

1. 番号付きリスト 1
   1. 番号付きリスト 1_1
   1. 番号付きリスト 1_2
1. 番号付きリスト 2
1. 番号付きリスト 3

---

# 数式

$$I_{xx}=\int\int_Ry^2f(x,y)\cdot{}dydx$$

$
\begin{aligned}
   a&=b+c \\
   d+e&=f
\end{aligned}
$

---

# 引用

> お世話になります。xxx です。
>
> ご連絡いただいた、バグの件ですが、仕様です。
>
> > お世話になります。 yyy です。
> >
> > あの新機能バグってるっすね

---

# pre 記法(スペース 4 or タブ)

    // Tab
    class Hoge
        def hoge
            print 'hoge'
        end
    end

    // space
    class Hoge
      def hoge
        print 'hoge'
      end
    end

---

# code 記法

インストールコマンドは `gem install hoge` です

# リンク

[Google 先生](https://www.google.co.jp/)

[こっちから google][google]
その他の文章
[こっちからも google][google]

[google]: https://www.google.co.jp/

https://www.google.co.jp/

---

# 取り消し線

~~取り消し線~~

# 表組み

| header1    |     header2 |   header3    |
| :--------- | ----------: | :----------: |
| align left | align right | align center |
| a          |           b |      c       |

---

# pre 記法(シンタックスハイライト)

Ruby

```ruby
　class Hoge
　  def hoge
　    print 'hoge'
　  end
　end
```

---

Javascript

```js
module.exports = {
  //...
  plugins: [require('daisyui')],
};
```

Typescript

```ts
import type { IncomingMessage, ServerResponse } from 'http';

function hello(name: string): void {
  console.log('Hello ' + name + '!');
}
let your_name: string = 'Yamada';
hello(your_name);
```

---

<!-- _class: invert -->

JSON

```json
{
  "browsers": {
    "firefox": {
      "name": "Firefox",
      "pref_url": "about:config",
      "releases": {
        "1": {
          "release_date": "2004-11-09",
          "status": "retired",
          "engine": "Gecko",
          "engine_version": "1.7"
        }
      }
    }
  }
}
```

---

# 背景画像

## bg contain britness:.8 sepia:50%

![bg contain brightness:.8 sepia:50%](https://picsum.photos/1920?random)

---

<!--_class: top-->

## bg brightness:.6 blur:10px

![bg brightness:.6 blur:10px](https://picsum.photos/1920?random)

---

<!--_class: top-->

## 背景横並び

![bg brightness:.6](https://picsum.photos/480?random=1)
![bg brightness:.6](https://picsum.photos/480?random=2)
![bg brightness:.6](https://picsum.photos/480?random=3)

---

<!--_class: top-->

## 背景縦並び

![bg brightness:.6 vertical](https://picsum.photos/480?random=1)
![bg brightness:.6](https://picsum.photos/480?random=2)
![bg brightness:.6](https://picsum.photos/480?random=3)

---

## 背景分割

スライドサイズの半分で分割される

![bg right w:600 h:600](./images/foo.drawio.svg)

---

## 背景画像+背景色

<!--_class: top-->

![bg opacity:0.5](https://picsum.photos/1920?random)
![bg](green)

---

# 参考記事

[【VS Code + Marp】Markdown から爆速・自由自在なデザインで、プレゼンスライドを作る](https://qiita.com/tomo_makes/items/aafae4021986553ae1d8)

[Marp(Marpit)](https://qiita.com/takeshisakuma/items/5a61e6eac123d28602fb)

[Markdown 記法 サンプル集](https://qiita.com/tbpgr/items/989c6badefff69377da7)

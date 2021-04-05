プロジェクト・タイトル
======================
ここにプロジェクトの概要を書きます。
行末にスペースを2つ入れると  
改行されます。

段落を分けるには、[空行](http://example.com/) を入れます。

使い方
------
### インライン ###
インラインのコードは、**バッククォート** (`` ` ``) で囲みます。

### ブロックレベル ###
    <script type="text/javascript" src="jquery.min.js"></script>
    <script type="text/javascript">
    $(function() {
        alert($); /* 先頭に4文字のスペース、
                     もしくはタブを挿入します */
    });
    </script>

パラメータの解説
----------------
リストの間に空行を挟むと、それぞれのリストに `<p>` タグが挿入され、行間が
広くなります。

    def MyFunction(param1, param2, ...)

+   `param1` :  
    _パラメータ1_ の説明

+   `param2` :  
    _パラメータ2_ の説明

関連情報
--------
### リンク、ネストしたリスト
1. [リンク1](http://google.com/ "リンクのタイトル")
    * ![画像1](あhttp://i.imgur.com/Jjwsc.jpg "画像のタイトル")
2. [リンク2][link]
    - [![画像2][image]](https://github.com/)

  [link]: http://fanuc.co.jp/ "インデックス型のリンク"
  [image]: あhttp://i.imgur.com/Jjwsc.jpg "インデックス型の画像"

### 画像の表示
以下のように記述すると画像が表示できる。  

    ![エビフライトライアングル](http://i.imgur.com/Jjwsc.jpg "サンプル")

+ **example**

![エビフライトライアングル](http://i.imgur.com/Jjwsc.jpg "サンプル")

ただし上記では画像の表示サイズを指定できないので `<img>` タグを用いる必要がある。  

    <img src="https://raw.github.com/github/media/master/octocats/octocat.png" alt="Github mascot Octcat" title="Octcat" width="200" height="200" />

+ **example**

<img src="https://raw.github.com/github/media/master/octocats/octocat.png" alt="Github mascot Octcat" title="Octcat" width="200" height="200" />

GitHubのリポジトリ内にある画像も同様に表示可能

    <img src="https://github.com/Guccisan/How-to/tree/master/imgs/makunoshita.png" title="マクノシタ" />

+ **example**

<img src="https://github.com/Guccisan/How-to/blob/master/imgs/makunoshita.png" title="マクノシタ" />

### シンタックスハイライト
ソースコードが色付けされて見やすくなる。 ` ```(言語名) ` のように記述する。  

C言語  

    ```c
    #include <stdio.h>
    int main()
    {
        printf("Hello, world!\n");
        return 0;
    }
    ```

Java  

    ``` java
    public class HelloWorld{
        public static void main(String[] args){
            System.out.println("Hello World");
        }
    }
    ```

+ **example**

```c
#include <stdio.h>
int main()
{
    printf("Hello, world!\n");
    return 0;
}
```

``` java
public class HelloWorld{
    public static void main(String[] args){
        System.out.println("Hello World");
    }
}
```

### 引用、ネストした引用
> これは引用です。
> 
> > スペースを挟んで `>` を重ねると、引用の中で引用ができますが、
> > GitHubの場合、1行前に空の引用が無いと、正しくマークアップされません。

ライセンス
----------
Copyright &copy; 2011 xxxxxx  
Licensed under the [Apache License, Version 2.0][Apache]  
Distributed under the [MIT License][mit].  
Dual licensed under the [MIT license][MIT] and [GPL license][GPL].

[Apache]: http://www.apache.org/licenses/LICENSE-2.0
[MIT]: http://www.opensource.org/licenses/mit-license.php
[GPL]: http://www.gnu.org/licenses/gpl.html

[前のページへ戻る]: ./index.md

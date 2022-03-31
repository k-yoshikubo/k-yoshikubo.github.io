# サンプル

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Command

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/         # The site built by mkdocs.
    src/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

!!! Note
    これはノートです。

!!! Tip
    ヒントです。

!!! Warning
    これは警告です

!!! Danger
    これは危険です。

!!! Success
    これは成功です。

!!! Failure
    これは失敗です。

!!! Bug
    これはバグです。

!!! summary
    これは概要です。


<label for="name">名前</label>
<input type="text" name="name" id="name" placeholder="名前"><br />
<label><input type="radio" name="sex" value="male">男</label>
<label><input type="radio" name="sex" value="female">女</label><br />
<label for="food">好きな食べ物</label>
<select name="food" id="food">
    <option value="meat">肉</option>
    <option value="fish">魚</option>
    <option value="vegetable">野菜</option>
    <option value="other">それ以外</option>
</select>
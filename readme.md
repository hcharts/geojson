# geojson

Geojson 中文文档，是对 [http://geojson.org](http://geojson.org) 的翻译，并发布在 [http://geojosn.hcharts.cn](http://geojosn.hcharts.cn) 上。


### 欢迎大家贡献翻译

请 Fork 本仓库，在本地更改后提交 pull request。

[https://github.com/hcharts/geojon](https://github.com/hcharts/geojson)



### 运行环境


静态文件由 [Jekyll](http://jekyllrb.com/) 转换生成，所以必须安装 Jekyll。

    gem install jekyll

Any pages with the `.md` extension are rendered as `.html` with [rdiscount](https://github.com/davidfstr/rdiscount) (Jekyll's default Markdown parser [doesn't do nested lists](https://github.com/bhollis/maruku/issues/55)).  So in addition to installing Jekyll, you'll want to install rdiscount.

    gem install jekyll rdiscount

After installing Jekyll, run the following in the root of the repository to start the development server.

    jekyll serve --watch --safe

then http://127.0.0.1:4000
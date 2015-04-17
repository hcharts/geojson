---
layout: home
title: GeoJSON
---

# <span class="fkin">G</span>eo<span class="fkin">J</span>SON <span class="fsmall">-- by [hcharts.cn](http://www.hcharts.cn)</span>

GeoJSON 是一种对各种地理数据结构进行编码的格式，基于 Javascript 对象 （JavaScript Object Notation）表示法的地理空间信息数据交换格式。

{% highlight javascript %}
{
  "type": "Feature",
  "geometry": {
    "type": "Point",
    "coordinates": [125.6, 10.1]
  },
  "properties": {
    "name": "Dinagat Islands"
  }
}
{% endhighlight %}

GeoJSON 对象可以表示几何、特征或者特征集合。GeoJSON支持下面几何类型：点、线、面、多点、多线、多面和几何集合。GeoJSON 里的特征包含一个几何对象和其他属性，特征集合表示一系列特征。

## Learn More

[点击查看完整文档](geojson-spec.html)。

## Github

[http://github.com/hcharts/geojson](http://github.com/hcharts/geojson)

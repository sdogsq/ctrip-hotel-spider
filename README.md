# ctrip hotel spider and data analysis

Click **demo.ipynb** to preview result.

## Feature

爬取选择地标附近所有三星即以上酒店的：名字、评分、地标距离、评论数、满意度、最低价格。并简单地对数据进行了部分可视化。

## Output

- `hotel.csv` 爬取的酒店的数据

- `Rpie.jpg` 爬取酒店星级比例饼状图

- `DvP.jpg` 酒店距离与价格折线图

- `Pdensity.jpg` 酒店价格分布图

- `Sbox.jpg` 酒店评价箱型图

**demo** 中有预览。

## Others

python + selenium with chromedriver (or any other supported webdriver)

由于携程有加密，破解麻烦，所以选择selenium直接爬取。

默认搜索香港某地标 `place` 附近酒店，其他地区直接修改 `url` 即可。或者简单修改代码即可做到任何城市任何区域搜索。

要实现其他附加搜索条件（指定日期、价位区间…），直接使用selenium模拟点击相应控件。
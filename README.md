# AutoXuexiQiangGuo
> 学习强国，坚持四个自信
Python自动化代码

**PS：代码已经更新，有需要一起交流。**
 
# 2019年3月23日更新版本
## 1 配置运行
- python版本
安装python3.5版本
- pip包
pip install -v selenium==3.141
pip install -v urlib3==1.24.1
pip install -v pymongo==3.7.2
- chrome
本版本安装的为最新稳定版（73.0.3683.86）
- chromedriver版本
根据chrome进行选择，访问[chromedriver官网](http://chromedriver.chromium.org/downloads)。
- MongoDB版本
本版本安装的为最新版（4.0.6），访问[Mongodb官网](https://www.mongodb.com/download-center/community)

## 2 目前版本 new_interface.py
1. 本版本更为稳定，每次运行基本保证能拿每日网页端最高分（31分）。
2. 每天最多可学习31分（登录1分，阅读文章14分，视频观看16分），运行完程序预计需要1个半小时。 √
3. 将文章数据和视频数据添加到mongodb数据库中。 √   （get_link.py）
4. 可手工扫码登录或使用cookies登录（由于Cookies只能保持6小时，所以主版本暂时使用扫码登录） √
5. 通过获取数据库中的数据，对文章进行阅读和对视频进行观看，让每次阅读和观看都有效。 (new_interface.py) √

## 3 接下来版本
1. 自动模拟登录开发成本与时间不成正比，未来一段时间不会往这部分开发。
2. 多线程运行，提升效率，目前运行完一次大概需要1个半小时，下个版本将减少这部分时间。
3. 打包该文件，直接运行exe文件即可进行学习。

# 3月15日版本
## 1 配置运行
- python版本
安装python3.5版本
- pip包
pip install -v selenium=3.141
pip install -v urlib3=1.24.1
- chrome 版本
- chromedriver版本
根据chrome进行选择，访问[chromedriver官网](http://chromedriver.chromium.org/downloads)。

## 2 目前版本  interface.py
1. 视频观看 √
2. 文章阅读 √
3. 获取总积分和今日积分 √
4. 可手工扫码登录或使用cookies登录（由于Cookies只能保持6小时，所以主版本暂时使用扫码登录） √
5. 每天最多可学习31分（登录1分，阅读文章14分，视频观看16分）。 √

## 3 接下来版本
1. 将视频链接和文章链接放入数据库，查重之后每天更新。
2. 每天播放不同的短视频和阅读不同的文章。（PS：获取积分判断有些迷，貌似是24小时内阅读的文章是算做同一篇文章，所以阅读不算积分，还在测试）
3. 模拟自动登录（可参考微信网页版登录方式进行测试）。


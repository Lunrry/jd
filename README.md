* 1、签到领现金-助力
* 2、极速版 旺财乐园
* 3、明月寒大佬的 京喜财富岛-娱乐中心-抽奖
* 4、汪汪乐园开工位
* 5、半点京豆雨
* 6、整点京豆雨
* 7、点点券二代目
* 8、赚京豆
* 9、欧洲杯
* 10、全民运动会互助
* 11、汪汪乐园每日助力
* 12、燃动夏季（先运行解密 再运行脚本）
* 13、签到图形验证
* 14、宠汪汪二代目（需要安装npm依赖）
* 15、来客有礼&送豆得豆
* 16、早起福利
* 17、QQ星系牧场
* 18、抢京豆
* 19、签到领现金兑换
* 20、百元守卫战助力
* 21、京东试用
* 22、修复宠汪汪积分兑换（需要安装canvas依赖）
* 23、柠檬推一推
* 24、京东众筹许愿池
* 25、修复了多合一签到脚本
* 26、京东到家果园任务
* 27、愤怒的锦鲤（需添加环境变量export kois="pt_pin1@pt_pin2"）
* 28、天天优惠大乐透
* 29、新版财富岛（需要安装依赖）（cron已自动设置）
* 30、新版财富岛热气球（cron已自动设置）
* 31、宠汪汪偷好友积分助力
* 32、特物Z|万物皆可国创
* 33、京东到家果园水车
* 34、京东到家鲜豆任务
* 35、京东到家鲜豆庄园
* 36、京东到家庄园领水滴
* 37、粉丝互动
* 38、京享值PK
* 39、燃动夏季下注、百元守护
* 40、京喜工厂，京喜工厂内部团
* 41、愤怒的现金（默认助力前9账号）
* 42、泡泡大战
* 43、柠檬惊喜工厂抢茅台（需要设置变量）
* 44、京东零食街
* 45、柠檬砍价系列（需设置邀请码变量）
* 46、发财大赢家 翻翻乐
* 47、发财大赢家获取邀请码
* 48、发财大赢家助力
* 49、柠檬一次性开卡



【Faker集合仓库】
ql repo https://ghproxy.com/https://github.com/Lunrry/jd.git "jd_|jx_|getJDCookie" "activity|backUp" "^jd[^_]|USER|ZooFaker_Necklace|JDJRValidator_Pure"

【财富岛依赖安装命令】
docker exec -it QL bash -c "npm install axios date-fns"

【DOCKER npm依赖安装命令】

docker exec -it QL bash -c "cd scripts && npm i -S png-js"

【canvas 依赖安装命令】
docker exec -it QL bash -c "apk add --no-cache build-base g++ cairo-dev pango-dev giflib-dev && cd scripts && npm install canvas --build-from-source"

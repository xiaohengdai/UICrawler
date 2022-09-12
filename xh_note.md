java -jar /Users/xiaoheng/Downloads/code/UICrawler/target/UICrawler-2.4.0.jar -u 00008020-000509D4266A002E -f config_pdd.yml
查看maven版本:mvn -v

maven打jar包：
进入到有pom.xml文件的目录中：
输入：mvn clean package

在此项目中即:
mvn clean package


IDEA中maven自动更新pom文件的任何变更：https://blog.csdn.net/qq_65054783/article/details/126371671

log中日志配置:src/main/resources/logback.xml

待办:
- io.appium7.6.0提示不安全，需要升级io.appium版本
- 需要加自动处理关闭弹窗的配置(GENERAL)
- 自定义页面指定操作配置（custom_page_action）
- clickElement中排除掉对当前可见屏幕外的元素截图、点击等操作（done）
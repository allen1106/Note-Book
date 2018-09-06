## 项目颜色列表：
  * background    gray    #EDEDED
  * background    deep gray    #D4D4D4
  * color         gray    #A6A6A6
## 项目中遇到的问题：
  * ### idea中无法热部署的问题：
    * 导入项目的时候是直接open的idea mudule，未按照正常流程(import project)导入项目，所以并未识别是一个maven集成项目，正常导入后就ok了。
  * ### idea中console乱码的问题：
    * 无论使用哪一种编码格式解码字符串在console输出的时候都是乱码，解决办法是在pom.xml中指定一下spring-boot-maven插件的jvm编码为UTF-8

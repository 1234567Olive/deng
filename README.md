# deng
实验三UI组件的第一个实验
实验截图https://github.com/1234567Olive/deng/blob/master/3.1.JPG
Android ListView的用法，利用SimpleAdapter实现
首先 继承activity 重新里面的onCreate方法
然后初始化一个listLiew，声明simpleadapter 
第三，在res/layout文件夹下 ，创建simple_adapter.xml文件，先写布局文件，需要ImageView,把需要的图片直接放进res/drawable-hdpi文件夹，会在R文件自动生成文件
第四，然后要TextView,要设好样式 TextView如下,设置完以后，要在adapter中引入，from和to先声明好不报错
第五，设置一个list，一个images 一个names,方便以后用方法来运用
第六，针对数据源进行初始化
最后，设置from和to了，注意 from和to参数一一对应，然后设置适配器



# android-SwipeLinearLayout
自定义侧滑布局，继承LinearLayout

##效果##
可以单独使用，也可以在ListView等可滑动的父组件中使用。以在ListView中使用为demo:  
<img src="https://github.com/lankton/android-SwipeLinearLayout/blob/master/pictures/swipelinearlayout.gif?raw=true" width="260px"/>  
解决了item和ListView的滑动冲突， 同时每个item及其上面的控件可以正常点击。

代码比较简单，就不上传到JCenter了。 控件本身就只有一个文件: SwipeLinearLayout.java, 有需要可以直接复制或者修改。

##使用##
和普通LinearLayout一样使用，内部包含2个子元素即可。
示例:
```
<cn.lankton.swipelinearlayout.lib.SwipeLinearLayout
  xxxx>
  <LinearLayout
    android:layout-width="match_parent"
    xxxx
    xxxx>
    ... ...
  </LinearLayout>
  <LinearLayout
    android:layout-width="30dp"
    xxxx>
    ... ...
  </LinearLayout>
</cn.lankton.swipelinearlayout.lib.SwipeLinearLayout>
```
SwipeLinearLayout的orientation随便设置，反正都会当成horizontal处理。 

##相关博文##

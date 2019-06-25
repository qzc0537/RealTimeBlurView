# RealTimeBlurView
高斯模糊遮罩

[![](https://jitpack.io/v/qzc0537/RealTimeBlurView.svg)](https://jitpack.io/#qzc0537/RealTimeBlurView)


使用
--
1.project build.gradle下添加：
maven { url 'https://jitpack.io' }

如下：

```
allprojects {
    repositories {
        maven { url "https://jitpack.io" }
    }
}
```

2.app build.gradle下添加依赖 ：

```
implementation 'com.github.qzc0537:RealTimeBlurView:1.0.1'
```

3.愉快的使用：
```
<com.qzc.realtimeblurview.RealTimeBlurView
    android:layout_width="200dp"
    android:layout_height="100dp"
    android:layout_marginTop="10dp"
    app:realTimeBlurRadius="2"
    app:realTimeOverlayColor="#4fff"
    app:layout_constraintTop_toTopOf="parent"
    app:layout_constraintLeft_toLeftOf="parent"
    app:layout_constraintRight_toRightOf="parent"/>

<com.qzc.realtimeblurview.RoundCornerBlurView
    android:layout_width="200dp"
    android:layout_height="100dp"
    app:realTimeBlurRadius="2"
    app:realTimeOverlayColor="#4000"
    app:realTimeBlurRoundCornerRadius="6dp"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintTop_toTopOf="parent"
    app:layout_constraintLeft_toLeftOf="parent"
    app:layout_constraintRight_toRightOf="parent"/>

<com.qzc.realtimeblurview.RoundBlurView
    android:layout_width="100dp"
    android:layout_height="100dp"
    android:layout_marginBottom="10dp"
    app:realTimeOverlayColor="#4000"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintLeft_toLeftOf="parent"
    app:layout_constraintRight_toRightOf="parent"/>

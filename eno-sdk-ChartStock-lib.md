# ENO sdk  


####f时线Chart 
*页面调用

```java
  ENO_FS_View ENOFsView =(ENO_FS_View) findViewById(R.id.fs_View);
              
  Eno_FsView_Presenter eno_fsView_control=new Eno_FsView_Presenter(ENOFsView,this);
```

*布局文件

```
     <!-- <com.eno.sdk.view.chart.mvp.v.ENO_FS_ViewView-->
        <!--xmlns:chartView="http://schemas.android.com/apk/res/com.eno.sdk.view.eno_chart"-->
        <!--android:id="@+id/fs_View"-->
        <!--android:layout_width="match_parent"-->
        <!--android:layout_height="200dip"-->
        <!--/>-->
```



####K线Chart 
*页面调用

```
 ENO_KX_View ENOKxView =(ENO_KX_View) findViewById(R.id.kx_View);
              
Eno_KxView_Presenter eno_kxView_control=new Eno_KxView_Presenter(ENOKxView,this);
```

*布局文件

```
  <com.eno.sdk.view.chart.view.ENO_KX_View
        xmlns:chartView="http://schemas.android.com/apk/res/com.demo.net.eno.app.eno_sdk"
        android:id="@+id/kx_View"
        android:layout_width="match_parent"
        android:layout_height="500dip"
        chartView:chart_x_textSize="10dip"
        chartView:chart_y_textSize="10dip"
        chartView:chart_show_textSize="10dip"
        />
```
这是图片：![][avatar]

[avatar]: https://raw.githubusercontent.com/xmf483/ENO_APP_SDK/master/gp.jpg

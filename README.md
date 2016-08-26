# BottomNavigationBar
# 特色底部导航栏

/**
 * .setInActiveColor("#2196f3")//未被选中时图标和文字的颜色(BACKGROUND_STYLE_RIPPLE、BACKGROUND_STYLE_STATIC(选中时自身的颜色))
 * .setBarBackgroundColor("#FF0000")//导航栏背景颜色(BACKGROUND_STYLE_RIPPLE模式下表示所有图标的默认颜色、(BACKGROUND_STYLE_STATIC))
 * .initialise();
 *
 * bottomNavigationBar.setBackgroundStyle(BottomNavigationBar.BACKGROUND_STYLE_DEFAULT);
 * setInActiveColor("#2196f3")//未被选中时图标和文字的颜色
 * setBarBackgroundColor("#FF0000")//导航栏背景颜色
 * 并携带选中是的自身设置的颜色
 *
 *
 * bottomNavigationBar.setBackgroundStyle(BottomNavigationBar.BACKGROUND_STYLE_RIPPLE);
 * setActiveColorResource(R.color.orange)//导航栏背景颜色
 * setInActiveColorResource(R.color.blue)//未被选中时的文字和图标的颜色
 *
 *
 * bottomNavigationBar.setBackgroundStyle(BottomNavigationBar.BACKGROUND_STYLE_STATIC);
 * setActiveColorResource(R.color.orange)//被选中时的文字和图标的颜色
 * setInActiveColorResource(R.color.blue)//未被选中时的文字和图标的颜色
 */

 MODE_FIXED+BACKGROUND_STYLE_STATIC效果
 ![effect_1]()

 MODE_FIXED+BACKGROUND_STYLE_RIPPLE效果
 ![effect_2]()

 MODE_SHIFTING+BACKGROUND_STYLE_STATIC效果
 ![effect_3]()

 MODE_SHIFTING+BACKGROUND_STYLE_RIPPLE效果
 ![effect_4]()

# 添加依赖
  compile 'com.ashokvarma.android:bottom-navigation-bar:1.2.0'
Creating Apps with Material Design - 创建材料设计的应用
====

### Material Theme - 材料(设计)主题

The new material theme provides:

- System widgets that let you set their color palette
- Touch feedback animations for the system widgets
- Activity transition animations

新材料主题将提供：

- 可设置调色板的系统组件
- 系统组件的触摸反馈动画
- 操作行为（这里的Activity指的不仅是Android component-Activity）转换动画

You can customize the look of the material theme according to your brand identity with a color palette you control. You can tint the action bar and the status bar using theme attributes.

您可使用您所控制的配色工具，按照您的品牌形象定制材料主题的外观。 您可使用主题属性为操作栏和状态栏着色。（下图既调色板颜色默认命名）<span id="color">[详见附录](#color-footer)</span>

<img src="http://oo8db6bor.bkt.clouddn.com/ThemeColors.png" width="220dp"/>

The system widgets have a new design and touch feedback animations. You can customize the color palette, the touch feedback animations, and the activity transitions for your app.

系统组件拥有全新的设计与触摸反馈动画。您可为您的应用定制配色工具、触摸反馈动画以及操作行为转换。

The material theme is defined as:

- @android:style/Theme.Material (dark version)
- @android:style/Theme.Material.Light (light version)
- @android:style/Theme.Material.Light.DarkActionBar

材料主题的定义为：

- @android:style/Theme.Material（深色版本）
- @android:style/Theme.Material.Light（浅色版本）
- @android:style/Theme.Material.Light.DarkActionBar

<img src="http://oo8db6bor.bkt.clouddn.com/MaterialDark.png" width="220dp"/><img src="http://oo8db6bor.bkt.clouddn.com/MaterialLight.png" width="220dp"/>

> Note: The material theme is only available in Android 5.0 (API level 21) and above. The v7 Support Libraries provide themes with material design styles for some widgets and support for customizing the color palette.

> 注意：材料主题仅在 Android 5.0（API 级别 21）及更高版本中提供。 v7 支持内容库为一些小组件提供附带 Material Design 风格的主题，同时为配色工具定制提供支持。[^]

### <span id="color-footer">Appendix</span>  [↩](#color)

|item|名称|
|:---:|:---:|
|colorPrimary|主颜色|
|colorAccent|强调色|

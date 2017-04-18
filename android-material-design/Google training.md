# Material Theme - 材料(设计)主题

The new material theme provides:

- System widgets that let you set their color palette
- Touch feedback animations for the system widgets
- Activity transition animations

新材料主题将提供：

- 可设置调色板的系统组件
- 系统组件的触摸反馈动画
- 操作行为（这里的Activity指的不仅是Android component-Activity）转换动画

You can customize the look of the material theme according to your brand identity with a color palette you control. You can tint the action bar and the status bar using theme attributes.<a id="color"></a>[[Palette Appendix]](#color-footer)

你可使用你所控制的配色工具，按照你的品牌形象定制材料主题的外观。 你可使用主题属性为操作栏和状态栏着色。[[调色板附录]](#color-footer)

<img src="http://oo8db6bor.bkt.clouddn.com/ThemeColors.png" width="220dp"/>

The system widgets have a new design and touch feedback animations. You can customize the color palette, the touch feedback animations, and the activity transitions for your app.

系统组件拥有全新的设计与触摸反馈动画。你可为你的应用定制配色工具、触摸反馈动画以及操作行为转换。

The material theme is defined as:

- @android:style/Theme.Material (dark version)
- @android:style/Theme.Material.Light (light version)
- @android:style/Theme.Material.Light.DarkActionBar

材料主题的定义为：

- @android:style/Theme.Material（深色版本）
- @android:style/Theme.Material.Light（浅色版本）
- @android:style/Theme.Material.Light.DarkActionBar

<img src="http://oo8db6bor.bkt.clouddn.com/MaterialDark.png" width="220dp"/><img src="http://oo8db6bor.bkt.clouddn.com/MaterialLight.png" width="220dp"/>

> Note: The material theme is only available in Android 5.0 (API level 21) and above. The v7 Support Libraries provide themes with material design styles for some widgets and support for customizing the color palette.<a id="compatibility"></a>[[Compatibility Appendix]](#compatibility-appendix)

> 注意：材料主题仅在 Android 5.0（API 级别 21）及更高版本中提供。 v7 支持内容库为一些小组件提供附带 Material Design 风格的主题，同时为配色工具定制提供支持。[[兼容性附录]](#compatibility-appendix)


## <a id="color-footer"></a>Palette Appendix - 调色板附录  [:leftwards_arrow_with_hook:](#color)

|item|名称|
|:---:|:---:|
|colorPrimary|主颜色|
|colorAccent|强调色|

## <a id="compatibility-appendix"></a>Compatibility Appendix - 兼容性附录  [:leftwards_arrow_with_hook:](#compatibility)

有些 Material Design 功能（例如材料主题和定制操作行为转换）仅在 Android 5.0（API 21）及更高版本中提供。 不过，您可为您的应用进行设计，使应用在支持 Material Design 的设备上运行时可使用这些功能，且同时能够与运行早期版本 Android 的设备兼容。

### 定义拓展样式

1. 定义一个从 res/values/styles.xml 中的早期版本主题（例如 Holo）继承的主题。
2. 定义一个从 res/values-v21/styles.xml 中的材料主题继承且拥有相同名称的主题。
3. 在清单文件中将此主题设置为您的应用主题。

> 注意：如果您的应用使用材料主题，但没有以这方式提供备用主题，您的应用将无法在 Android 5.0 之前的 Android 版本上运行。

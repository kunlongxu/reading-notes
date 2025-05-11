# Jetpack Compose Modifier 常用方法速查表

| 分类       | 方法                                     | 说明                       |
|------------|------------------------------------------|----------------------------|
| 尺寸与布局 | fillMaxSize()                            | 占满父布局全部空间         |
| 尺寸与布局 | fillMaxWidth() / fillMaxHeight()         | 横向或纵向填满父布局       |
| 尺寸与布局 | wrapContentSize()                        | 内容决定自身大小           |
| 尺寸与布局 | width() / height()                       | 固定宽高                   |
| 尺寸与布局 | size()                                   | 设置宽高一致               |
| 尺寸与布局 | requiredSize()                           | 强制设置尺寸，不能被约束   |
| 边距与间距 | padding()                                | 设置内边距                 |
| 边距与间距 | absolutePadding()                        | 设置上下左右方向的 padding |
| 边距与间距 | offset()                                 | 位移偏移组件位置           |
| 背景与外观 | background()                             | 设置背景颜色或形状         |
| 背景与外观 | border()                                 | 设置边框                   |
| 背景与外观 | clip()                                   | 裁剪组件为指定形状         |
| 背景与外观 | alpha()                                  | 设置透明度                 |
| 背景与外观 | graphicsLayer()                          | 设置旋转、缩放等效果       |
| 对齐与排列 | align()                                  | 设置在父组件中的对齐方式   |
| 对齐与排列 | wrapContentWidth() / wrapContentHeight() | 自动包裹内容宽/高          |
| 点击与交互 | clickable()                              | 添加点击事件               |
| 点击与交互 | combinedClickable()                      | 组合点击和长按事件         |
| 点击与交互 | pointerInput()                           | 添加手势识别               |
| 点击与交互 | draggable() / scrollable()               | 可拖拽或滚动行为           |
| 测试与辅助 | testTag()                                | 设置测试标记               |
| 测试与辅助 | semantics()                              | 设置无障碍语义             |
# rust-orbtk-GUI-learning
rust orbtk GUI learning

- with_bounds(mut self, bounds: Rect):设置窗口大小和位置
- with_title<S: Into<String>>(mut self, title: S)：设置窗口标题
- with_theme(mut self, theme: Theme)：设置css样式，theme实际上是一个包含css样式的字符串
- with_root(mut self, root: Template)：设置窗口的根控件，orbtk的所有控件(button,combox等)都是Template
- with_debug_flag(mut self, debug: bool)：设置是否为debug模式，debug为true时，会在命令行控制台显示调试信息

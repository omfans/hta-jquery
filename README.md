HTA (MS HtmlApplication) + jQuery 实现快速桌面应用开发 (仅限Win)

一、基本原理
-----
*	HTA属于高权限Script宿主(相对webBroswer)
*	常规使用非常方便如 文件管理、网络通信、数据库操作 等 直接创建对象调用即可
*	比如，Mail、Mysql、MSSQL，当然前提是系统有相应组件和驱动
*	脚本支持: VBScript / JScript / Javascript
*	界面设计: 完整支持 HTML + CSS

二、优缺点 与 适用环境
-----
*	易于开发、调试、界面设计
*	无基础库依赖 目前主流Win系统全支持
*	缺点是底层调用不支持，比如硬件操作。
*	日常环境中的OA：半自动辅助工具等结合Office、VBS 十分便利，
*	开发工具丰富 加上jQuery丰富的插件，做界面效果可以更方便
*	script放在服务器端，每次更新直接更新主script库即可，客户端无需更新
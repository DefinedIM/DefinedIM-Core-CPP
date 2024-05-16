|文件|描述|
|main.cpp|主程序（当生成动态库时使用）|
|core.hpp|核心之头文件，声明所有暴露的方法（内嵌socket网络插件、AES加密插件和GPG插件）|
|plugin.hpp|声明插件类，包括作者，描述，gpg签名等|
|plugin-network.hpp|继承插件类并声明网络插件类|
|plugin-crypto.hpp|继承插件类并声明加密插件类|

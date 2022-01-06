# THREES about
three.js
使用vue创建three动画的相关练习

//引入three
import * as THREE from "three";
import { OrbitControls } from "three/examples/jsm/controls/OrbitControls";


解决vue-cli4打包成dist后打开空白的问题:
在项目根目录创建vue.config.js文件，记得是根目录，内容为：

module.exports = {
 publicPath: process.env.NODE_ENV === 'production'
    ? './'
    : '/'
}

重新运行npm run build命令重新打包

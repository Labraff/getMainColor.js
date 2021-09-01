# getMainColor.js
   * easyColor.js 根据 GitHub 上 Ele-Peng/miniprogram-pallet 项目所封装。
   * 适配于微信小程序，用于取图片主色调的工具。
   * 更新仓库地址：https://github.com/Labraff/getMainColor.js.git
   * 
   * 基本参数
   * @imgPath 图片路径
   * @res canvas上下文
   * 
   * 使用方法
   * promise回调
   * mainGetColor(res,imgPath).then((res) =>{ // do anything })
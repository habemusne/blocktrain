# 安装

1. `git clone`这份代码
2. `cd express`
3. `npm i` (如果没有npm, 请安装)
4. `cp env.template .env`
5. 在`.env`替换掉那些变量。可以问客户要，或者我私下给你
6. （可选项）我使用pm2来运行代码，你可以用`npm i -g pm2`来安装

# 运行

1. 如果你安装了`pm2`那么可以运行`PORT=3000 pm2 start npm --name "blocktrain" -- run dev`。接下来网站会运行在端口3000。通过`pm2 logs 0`可以看日志。
2. 如果你没有安装pm2的话那么就用其他方法把网站运行在背景进程，比如说用`screen`. 运行的指令是`npm run dev`

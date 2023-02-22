1. react 绘制一个矩形

    ```html
        <svg viewBox="0 0 500 800"  xmlns="http://www.w3.org/2000/svg">
            <defs>
                <linearGradient id="Gradient01">
                    <stop offset="20%" stop-color="#39F" />
                    <stop offset="90%" stop-color="#F3F" />
                </linearGradient>
            </defs>
            <rect x="0" y="0" width="360" height="50"   fill="url(#Gradient01)" />
            <rect x="0" y="60" width="360" height="50"  fill="url(#Gradient01)" />
            <rect x="20" y="120" width="360" height="50" fill="url(#Gradient01)" />
        </svg>
    ```

    
2. 属性

+ x: 左上角x 轴坐标

+ y: 左上角y 轴坐标

   > x , y 定义了react 的起点

+ width: 矩形的宽度

+ height: 矩形的高度

+ fill: 填充矩形背景颜色，可以rgb,亦可以是linearGradient 渐变

+ stroke-width：边框宽度

+ stroke: 边框颜色

    <code>
        <html>
        <svg width="100" height="100">
            <circle cx="50" cy="50" r="40" stroke="green" stroke-width="10" fill="yellow" />
            Sorry, your browser does not support inline SVG.
        </svg> 
        </html>
    </code>

    ```html
        <svg width="100" height="100">
            <circle cx="50" cy="50" r="40" stroke="green" stroke-width="10" fill="yellow" />
            Sorry, your browser does not support inline SVG.
        </svg> 
    ```

+ style: 样式

    ```html
        <svg width="400" height="110">
            <rect width="300" height="100" style="fill:rgb(0,0,255);stroke-width:3;stroke:rgb(0,0,0)" />

            <rect width="300" height="100" style="fill:blue;stroke:pink;stroke-width:5;fill-opacity:0.1;stroke-opacity:0.9" />
        </svg>

    ```

    > opacity:0.5 整体透明度

+ rx 和 ry 产生圆角

    <code>
        <svg width="400" height="180">
        <rect x="50" y="20" rx="10" ry="10" width="150"     height="150" style="fill:red;stroke:black;        stroke-width:5;opacity:0.5" />
        Sorry, your browser does not support inline SVG.
        </svg>
    </code>

    ``` html
        <svg width="400" height="180">
            <rect x="50" y="20" rx="10" ry="10" width="150" height="150" style="fill:red;stroke:black;stroke-width:5;opacity:0.5" />
            Sorry, your browser does not support inline SVG.
        </svg>
    ```



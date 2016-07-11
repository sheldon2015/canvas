#  学习canvas的一些基础知识，构建知识体系

## day01

    1. getContext('2d')  api,获取2d上下文

    2. canvas跟其他标签一样，也可以通过css来定义样式。但这里需要注意的是：canvas的默认宽高为300px * 150px,在

       css中为canvas定义宽高，实际上把宽高为300px * 150px的画布进行了拉伸，如果在这样的情况下进行canvas绘图，

       你得到的图形可能就是变形的效果。所以，在canvas绘图时，应该在canvas标签里直接定义宽高.

       (见screenshot中的heigh_and_width.png中两种设置的的异同)

## day02

    1. 画直线 beginPath() closePath() strokeStyle属性 fillStyle属性 lineWidth属性

    2. 画矩形 strokeRect()  fillRect() clearRect();

    3. linecap 和linejoin 的几个属性值

    4. canvas图形(矩阵)变换 transform rotate scale，图形变换过程中状态函数 save()保存当前状态，restore()恢复之前的状态
## day03

    1. 画弧度  ctx.arc(x, y, radius, startAngle, endAngle, anticlockwise)，startAngle, endAngle为弧度

    2. arTo(x1,y1,x2,y2,radius)    当前端点不是弧线起点(x1,y1)，arcTo()方法还将添加一条当前端点到弧线起点的直线线段。


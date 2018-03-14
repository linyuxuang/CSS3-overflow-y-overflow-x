# CSS3-overflow-y-overflow-x
裁剪 元素中内容的左/右边缘 - 如果溢出元素的内容区域



定义和用法
      overflow-y 属性规定是否对内容的上/下边缘进行裁剪 - 如果溢出元素内容区域的话。
      overflow-x 属性来确定对左/右边缘的裁剪。
      
      
 语法
    overflow-y: visible|hidden|scroll|auto|no-display|no-content;
    
    
    
    visible	不裁剪内容，可能会显示在内容框之外。
    hidden	裁剪内容 - 不提供滚动机制。	
    scroll	裁剪内容 - 提供滚动机制。	
    auto	如果溢出框，则应该提供滚动机制。
    no-display	如果内容不适合内容框，则删除整个框。	
    no-content	如果内容不适合内容框，则隐藏整个内容



 例子：
 
  
              <style> 
                  div
                  {
                  width:110px;
                  height:110px;
                  border:thin solid black;
                  overflow-y:auto;
                  }
                  </style>

                  <div><p style="width:140px">
                     这是一个段落。这是一个段落。这是一个段落。这是一个段落。
                     这是一个段落。这是一个段落。这是一个段落。这是一个段落。
                    </p>
                  </div>

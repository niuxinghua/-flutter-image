flutter Image.asset加载图片解码的时机与render process的关系，谁推动png格式图片解码后mmap到用户空间？
 final RenderAbstractViewport viewport =
        RenderAbstractViewport.of(renderBox);
    final revealedOffset = viewport.getOffsetToReveal(renderBox, alignment);
    
上面代码的坐标系是如何转换的，如何在不同坐标系空间进行坐标定位？

writing中........

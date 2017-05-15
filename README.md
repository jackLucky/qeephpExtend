# QeePhp框架扩展
  QeePhp架构灵活，除了可以使用框架已提供的插件和扩展，也可以自己定义，这里提供一些写好的插件供大家下载使用。

## 控件
   控件在control目录下

### Pagination(分页控件)
    使用方式：
    
    把pagination.php复制到app/control/目录下面，然后在视图中直接调用
    
   ‘’‘php
   <?php $this->_control('pagination', 'my-pagination', array('pagination' => $pagination)); ?>
   '''

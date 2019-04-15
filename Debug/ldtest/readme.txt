l_cahnbutton.txt文件初始值设置为0，表示一开始处于不改变编码帧序号状态
l_frameqp.txt初始值设置为20.0，表示只对第一帧改变基准帧级qp，看帧级基准帧级qp不同对于失真传递的影响
l_markerframenum.txt初始值设置为0，表示从第零帧开始梯度改变量化参数
l_qpgradient.txt初始值设置为1.0，每次减小0.2，减到-1为止
l_firstqpgadient.txt初始值设置为1.0，使第一帧的qp每次减小0.2，减到-1为止

LJ人模调整

版本：1.1.0
本mod适配原版0.4.6.7，含以下功能，不兼容其他更改Renderer.CanvasModels["main"]或修改函数genlayer_clothing_back_img/genlayer_clothing_armgenlayer_clothing_arm_acc的mod

一，增加手臂束缚时图像，双手素体图像为img/body下armboundleft.png、armboundright.png
二，增加束缚时衣物图像，放在对应的img/clothesx内对应服装文件夹中，图像名直接在right/left后加“_bound”，
      例如：	left_bound.png
	left_bound_gray.png
	left_bound_acc.png
	left_bound_acc_gray.png
	right_bound.png
	right_bound_gray.png
	right_bound_acc.png
	right_bound_acc_gray.png  等
三，和调整束缚时和正常垂下时手臂图层层次，素体及衣物图层均会置于基础身体图层下侧
四，新增属性LJ_Rarmup，当upper/under_upper/over_upper的该属性为时会前置右臂常时素体、衣物显示
五，原版新增合身衣物的左右偏移数值减半，更适合1x1像素的图片。相应删除了衣物袖子合身调整的图层，建议束缚和常时手臂图片绘制时直接适配最小体型。

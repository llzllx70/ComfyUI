
# ComfyUI

- http://172.16.2.xx:8188/

# Hunyuan3D

- 在线生成: https://3d.hunyuan.tencent.com/
- 用的是v3.0, 效果比较好, 可能比开放出来的最高v2.1好
![alt text](image-6.png)
![alt text](image-5.png)

- 调用生成3D白膜，一次20积分，2元

# TripoSR

- 由Stability AI 发布
- 网站中也要收费

# Trellis-3D


# 在ComfyUI 中使用Hunyuan3D

- 参考其中的说明: https://docs.comfy.org/tutorials/3d/hunyuan3D-2
- download 图片 -> ComfyUI -> workflow -> open -> 加载图片 -> 生成工作流
- wget "https://huggingface.co/tencent/Hunyuan3D-2mv/resolve/main/hunyuan3d-dit-v2-mv/model.fp16.safetensors?download=true" -O ~/vsproject/ComfyUI/models/checkpoints/hunyuan3d-dit-v2-mv.safetensors  

- 工作流位于: /home/double/vsproject/ComfyUI/user/default/workflows

# 问题：

1. multi-view 生成的不光滑

![alt text](image-4.png)



# 流程

![alt text](image.png)


# 文件类型

- .GLB 或 .FBX：它们可以将贴图、材质、网格一起打包到单一文件中（更方便传输与共享）
- .OBJ 更像是一个“组合包”，要和 .MTL 与 .PNG 一起才能显示完整效果
- .stl 文件只保存了模型的几何信息（即三维形状表面三角面片），不包含颜色、贴图或材质信息。 所以常见的桌面 FDM 打印机读取 .stl 时，只能打印单一颜色的塑料丝（PLA、ABS 等）。

# 彩色打印

![alt text](image-1.png)

![alt text](image-3.png)


# Unique3D

# 结论

- 照片 -> Q图，效果比较好

# 基于python+Spire.PDF实现的批量修改pdf文件代码

### 缺点
- 有水印
<br>可使用```python_batch_remove_text```项目去批量去掉水印
<br>也可以手动删除
- 页数限制
<br>免费版对页数有限制（只能处理10页）

### 使用方法：
1.  设置输入目录
2. 设置输出目录
3. 设置背景颜色

### 工作流程：

1.  **创建虚拟环境**：在项目目录下执行 `python -m venv .venv`。
2.  **激活虚拟环境**：
    -   **Linux/macOS**：`source .venv/bin/activate`
    -   **Windows**：`.venv\Scripts\activate`
3.  **安装依赖**：激活环境后，使用 `pip install <package_name>` 安装包。
4.  **导出依赖列表**：使用 `pip freeze > requirements.txt` 将当前环境中所有包及其精确版本导出到 `requirements.txt` 文件。


```
# 创建虚拟环境
python -m venv venv

# 激活虚拟环境
source venv/bin/activate

# 在虚拟环境中安装 Spire.PDF
pip install spire.pdf

# 运行代码
python ./src/main.py
```


## Spire.PDF 所有 Color.get_*() 预设颜色列表
### 基础色系
#### 白色系：
Color.get_White()
Color.get_WhiteSmoke()
Color.get_GhostWhite()
Color.get_Ivory()
Color.get_Honeydew()
Color.get_Azure()
Color.get_AliceBlue()
Color.get_Snow()
Color.get_Seashell()
Color.get_MintCream()
Color.get_Linen()
Color.get_OldLace()
Color.get_FloralWhite()
Color.get_Beige()
Color.get_Cornsilk()
Color.get_LavenderBlush()
Color.get_SeaShell()
#### 黑色 / 灰色系：
Color.get_Black()
Color.get_Gray()
Color.get_DarkGray()
Color.get_DimGray()
Color.get_LightGray()
Color.get_Silver()
Color.get_Gainsboro()
#### 红色 / 粉色系
Color.get_Red()
Color.get_LightCoral()
Color.get_IndianRed()
Color.get_Crimson()
Color.get_FireBrick()
Color.get_DarkRed()
Color.get_Tomato()
Color.get_Salmon()
Color.get_LightSalmon()
Color.get_Coral()
Color.get_OrangeRed()
Color.get_HotPink()
Color.get_DeepPink()
Color.get_Pink()
Color.get_LightPink()
Color.get_PaleVioletRed()
Color.get_MediumVioletRed()
#### 橙色 / 黄色系
Color.get_Orange()
Color.get_DarkOrange()
Color.get_Coral()
Color.get_Gold()
Color.get_Yellow()
Color.get_LightYellow()
Color.get_LemonChiffon()
Color.get_LightGoldenrodYellow()
Color.get_PapayaWhip()
Color.get_Moccasin()
Color.get_PeachPuff()
Color.get_PaleGoldenrod()
Color.get_Khaki()
Color.get_DarkKhaki()
Color.get_Goldenrod()
Color.get_DarkGoldenrod()
#### 绿色系
Color.get_Green()
Color.get_Lime()
Color.get_LimeGreen()
Color.get_LightGreen()
Color.get_PaleGreen()
Color.get_MediumSpringGreen()
Color.get_SpringGreen()
Color.get_MediumSeaGreen()
Color.get_SeaGreen()
Color.get_ForestGreen()
Color.get_GreenYellow()
Color.get_Chartreuse()
Color.get_LawnGreen()
Color.get_OliveDrab()
Color.get_Olive()
Color.get_YellowGreen()
Color.get_DarkOliveGreen()
Color.get_MediumAquamarine()
Color.get_DarkSeaGreen()
Color.get_LightSeaGreen()
Color.get_DarkCyan()
Color.get_Teal()
#### 蓝色 / 青色系
Color.get_Blue()
Color.get_LightBlue()
Color.get_SkyBlue()
Color.get_LightSkyBlue()
Color.get_DeepSkyBlue()
Color.get_DodgerBlue()
Color.get_CornflowerBlue()
Color.get_SteelBlue()
Color.get_RoyalBlue()
Color.get_MediumBlue()
Color.get_DarkBlue()
Color.get_Navy()
Color.get_MidnightBlue()
Color.get_Cyan()
Color.get_LightCyan()
Color.get_Aqua()
Color.get_Turquoise()
Color.get_MediumTurquoise()
Color.get_DarkTurquoise()
Color.get_PaleTurquoise()
#### 紫色 / 品红色系
Color.get_Purple()
Color.get_Indigo()
Color.get_DarkViolet()
Color.get_DarkOrchid()
Color.get_DarkMagenta()
Color.get_MediumOrchid()
Color.get_MediumPurple()
Color.get_Orchid()
Color.get_Plum()
Color.get_Thistle()
Color.get_Lavender()
Color.get_Violet()
Color.get_Magenta()
Color.get_Fuchsia()
Color.get_Orchid()
Color.get_BlueViolet()
Color.get_SlateBlue()
Color.get_DarkSlateBlue()
Color.get_MediumSlateBlue()
#### 棕色系
Color.get_Brown()
Color.get_SaddleBrown()
Color.get_Sienna()
Color.get_Chocolate()
Color.get_Peru()
Color.get_SandyBrown()
Color.get_Tan()
Color.get_RosyBrown()
Color.get_BurlyWood()
Color.get_Wheat()
Color.get_NavajoWhite()
Color.get_Bisque()
Color.get_BlanchedAlmond()
Color.get_NavajoWhite()
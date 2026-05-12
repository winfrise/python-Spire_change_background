# 基于python+Spire.PDF实现的批量修改pdf文件代码
> 设置输入目录
> 设置输出目录

### 有水印
- 使用```python_batch_remove_text```项目去批量去掉水印
- 也可以手动删除

缺点：免费版对页数有限制（只能处理10页）

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
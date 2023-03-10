# myd2l
# 资源
官网：https://zh.d2l.ai/chapter_preface/index.html \
GitHub：https://github.com/d2l-ai/d2l-zh \
pdf资源：https://zh-v2.d2l.ai/d2l-zh-pytorch.pdf \
视频课程：https://courses.d2l.ai/zh-v2/

# 环境搭建
```bash
conda create --name myd2l python=3.9 -y
conda activate myd2l
conda install pytorch torchvision torchaudio cpuonly -c pytorch
pip install d2l==0.17.6
# jupyter notebook 绑定 conda env
conda install -c conda-forge ipykernel
python -m ipykernel install --user --name=myd2l # 绑定环境myd2l
# 启动jupyter
jupyter notebook # 点击new笔记本会多一个环境选择

# 如果jupyter要移除环境
jupyter kernelspec remove myd2l
```
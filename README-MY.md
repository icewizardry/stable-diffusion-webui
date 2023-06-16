
# 安装依赖版本调整
- 如果只用CPU
torch==1.13.0+cpu
torchvision==0.14.0+cpu

- 可以用GPU
torch==1.13.0+cu117
torchvision==0.14.0+cu117

pip install torchvision==1.13.0+cpu -f https://download.pytorch.org/whl/torch_stable.html
pip install torchvision==0.14.0+cpu -f https://download.pytorch.org/whl/torch_stable.html

# 安装必要库
sudo apt-get install libgl1-mesa-dev

# 启动
- 如果只用CPU
python3 launch.py --skip-torch-cuda-test
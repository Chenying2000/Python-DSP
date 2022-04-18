# 基于python的信号处理工具箱开发（py—SPT）
[![Python](https://img.shields.io/badge/python-3.9-blue)](https://docs.python.org/zh-cn/3.9/)
[Jupyter Notebook](https://jupyter.org/)

使用python完成信号产生、信号时域采样与内插恢复、信号变换域分析、滤波器设计等内容，实现基于python的Signal Processing Toolbox开发


## [信号产生](https://github.com/Chenying2000/py-SPT/tree/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E4%BF%A1%E5%8F%B7%E4%BA%A7%E7%94%9F)

- [波形生成：时间向量和正弦波](https://colab.research.google.com/drive/1B4s01fqxhfup-1TqbeTVeRfkmaesIzBS)

- [脉冲函数、阶跃函数和斜坡函数](https://colab.research.google.com/drive/1qTqbF-BOaeUFhmWJ-5FIFz-gO2Ldxzkq)

- [常见的周期波形：锯齿波、三角波、方波](https://colab.research.google.com/drive/1vin5Wl02Mi8DUPxsw8uHVh3RY5sUPw90)

- [非周期波形：三角脉冲、矩形脉冲](https://colab.research.google.com/drive/1xe2b6IjROY2aWtEvE5dz0vfuvp6pMAaf)

- [正弦函数sinc、迪利克雷函数Dlrichlet](https://colab.research.google.com/drive/1gFE-SGN01Nh7qGYFgRcpRhCeESLCqM3r)



## [信号时域采样与内插恢复](https://github.com/Chenying2000/py-SPT/tree/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E4%BF%A1%E5%8F%B7%E9%87%87%E6%A0%B7%E4%B8%8E%E6%81%A2%E5%A4%8D%EF%BC%88%E6%97%B6%E5%9F%9F%E5%88%86%E6%9E%90%EF%BC%89)
- 采样定理及奈奎斯特率验证

- 信号恢复：取样内插恢复

## [信号变换域分析](https://github.com/Chenying2000/py-SPT/tree/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E4%BF%A1%E5%8F%B7%E5%8F%98%E6%8D%A2%EF%BC%88%E5%8F%98%E6%8D%A2%E5%9F%9F%E5%88%86%E6%9E%90%EF%BC%89)
- 离散时间傅里叶变换DTFT
- 离散傅里叶变换DFT（IDFT）
- Z变换(IchripZ)
- 系统函数的频率响应
- 线性卷积和圆周卷积

## [滤波器设计](https://github.com/Chenying2000/py-SPT/tree/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1)
### [模拟滤波器设计](https://github.com/Chenying2000/py-SPT/tree/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1/%E6%A8%A1%E6%8B%9F%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1)
- 巴特沃斯滤波器设计
- 切比雪夫滤波器设计
### [窗函数](https://github.com/Chenying2000/py-SPT/tree/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1/%E6%95%B0%E5%AD%97%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1/%E7%AA%97%E5%87%BD%E6%95%B0)
- 矩形窗、三角形窗、汉宁窗、海明窗、布莱克曼窗、高斯窗、凯塞尔窗

### [数字滤波器设计](https://github.com/Chenying2000/py-SPT/tree/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1/%E6%95%B0%E5%AD%97%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1)
#### 无限长单位冲击响应滤波器（IIR）
- 脉冲响应不变法
- 双线性变换法
#### 有限长单位冲激响应滤波器设计（FIR）
- 窗函数设计法
- 频率取样设计法

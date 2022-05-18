# 基于python的信号处理工具箱开发（python—DSP）
[![Python](https://img.shields.io/badge/python-3.9-blue)](https://docs.python.org/zh-cn/3.9/)
[Jupyter Notebook](https://jupyter.org/)

使用python完成信号产生、信号时域采样与内插恢复、信号变换域分析、滤波器设计等内容，实现基于python的Digital Signal Processing Toolbox开发


## 信号产生

- 波形生成：时间向量和正弦波
  ([Colab Link ](https://colab.research.google.com/drive/1WrB8Z21WtpIRplLLE5osj0cxzDq0qMQE)|[Jupyter Notebook File](https://github.com/Chenying2000/Python-DSP/blob/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E4%BF%A1%E5%8F%B7%E4%BA%A7%E7%94%9F/%E6%B3%A2%E5%BD%A2%E7%94%9F%E6%88%90%EF%BC%9A%E6%97%B6%E9%97%B4%E5%90%91%E9%87%8F%E5%92%8C%E6%AD%A3%E5%BC%A6%E6%B3%A2.ipynb))

- 脉冲函数、阶跃函数和斜坡函数  ([Colab Link](https://colab.research.google.com/drive/1_YvBOIoGfMVOzNXjvkMjc1AGRdpkDyCs)|[Jupyter Notebook File](https://github.com/Chenying2000/Python-DSP/blob/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E4%BF%A1%E5%8F%B7%E4%BA%A7%E7%94%9F/%E8%84%89%E5%86%B2%E5%87%BD%E6%95%B0%E3%80%81%E9%98%B6%E8%B7%83%E5%87%BD%E6%95%B0%E5%92%8C%E6%96%9C%E5%9D%A1%E5%87%BD%E6%95%B0.ipynb))

- 常见的周期波形：锯齿波、三角波、方波  ([Colab Link](https://colab.research.google.com/drive/1REM-jvJX7dDC2SlKk02q8tDhxjB6iCcZ)|[Jupyter Notebook File](https://github.com/Chenying2000/Python-DSP/blob/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E4%BF%A1%E5%8F%B7%E4%BA%A7%E7%94%9F/%E5%B8%B8%E8%A7%81%E7%9A%84%E5%91%A8%E6%9C%9F%E6%B3%A2%E5%BD%A2%EF%BC%9A%E9%94%AF%E9%BD%BF%E6%B3%A2%E3%80%81%E4%B8%89%E8%A7%92%E6%B3%A2%E3%80%81%E6%96%B9%E6%B3%A2.ipynb))


- 非周期波形：三角脉冲、矩形脉冲  ([Colab Link](https://colab.research.google.com/drive/1BYAiuRWjbPADVC9HL_zGoAnZX1PbNnJG)|[Jupyter Notebook File](https://github.com/Chenying2000/Python-DSP/blob/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E4%BF%A1%E5%8F%B7%E4%BA%A7%E7%94%9F/%E9%9D%9E%E5%91%A8%E6%9C%9F%E6%B3%A2%E5%BD%A2%EF%BC%9A%E4%B8%89%E8%A7%92%E8%84%89%E5%86%B2%E3%80%81%E7%9F%A9%E5%BD%A2%E8%84%89%E5%86%B2.ipynb))

- 正弦函数sinc、迪利克雷函数Dlrichlet  ([Colab Link](https://colab.research.google.com/drive/1rVdnpADW4rtRZCUDdrEfF1E2NJ1p71-d)|[Jupyter Notebook File](https://github.com/Chenying2000/Python-DSP/blob/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E4%BF%A1%E5%8F%B7%E4%BA%A7%E7%94%9F/%E6%AD%A3%E5%BC%A6%E5%87%BD%E6%95%B0sinc%E5%92%8C%E8%BF%AA%E5%88%A9%E5%85%8B%E9%9B%B7%E5%87%BD%E6%95%B0Dirichlet.ipynb)




## [信号时域采样与内插恢复]

- [采样定理及奈奎斯特率验证](https://colab.research.google.com/drive/1aqBYTxth4f6p_fdO9u7Q5pAC-tUibOZQ)

- [信号恢复：取样内插恢复](https://colab.research.google.com/drive/1yvTHvSn19ehKHSEgqbXtayND12Z16_ly)

## [信号变换域分析](https://github.com/Chenying2000/py-SPT/tree/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E4%BF%A1%E5%8F%B7%E5%8F%98%E6%8D%A2%EF%BC%88%E5%8F%98%E6%8D%A2%E5%9F%9F%E5%88%86%E6%9E%90%EF%BC%89)
- [离散时间傅里叶变换DTFT](https://colab.research.google.com/drive/1CG7tDezBkdp7i_KBDCIEE3WfcHiD7Iy7)
- [离散傅里叶变换DFT（IDFT）](https://colab.research.google.com/drive/12Z6dlpTVzCDeSrnzGlIMmO0mi7-r2PSL)
- [Z变换(IchripZ)](https://colab.research.google.com/drive/1C5fRYTJo6RHVzJLHxy0tvwRkjpUnRVCw)
- [系统函数的频率响应](https://colab.research.google.com/drive/1TJFGBktSFd0dqXjlnMNSvr3bYN94nQUY)
- [线性卷积](https://colab.research.google.com/drive/18MqCcezyvaNN8f6qTQKvBPm4RapDMsqy)和[圆周卷积](https://colab.research.google.com/drive/1V5fITlGZHOMKf6yrxTLJPix6PIDfm-en)

## [滤波器设计](https://github.com/Chenying2000/py-SPT/tree/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1)
### [模拟滤波器设计](https://github.com/Chenying2000/py-SPT/tree/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1/%E6%A8%A1%E6%8B%9F%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1)
- [巴特沃斯滤波器设计](https://colab.research.google.com/drive/1AMf6PnVRs5bHV0l2GT_J3iZl900sZprY)
- [切比雪夫滤波器设计](https://colab.research.google.com/drive/1qqMFAirp0GTGAJ4g_YVQSYhPyab7V1Zp)
### [窗函数](https://github.com/Chenying2000/py-SPT/tree/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1/%E6%95%B0%E5%AD%97%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1/%E7%AA%97%E5%87%BD%E6%95%B0)
- [矩形窗、三角形窗、汉宁窗、海明窗、布莱克曼窗、高斯窗、凯塞尔窗](https://colab.research.google.com/drive/1nYaQVr5uI6W5XvlmAzspMouJjmXiVgjv)

### [数字滤波器设计](https://github.com/Chenying2000/py-SPT/tree/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1/%E6%95%B0%E5%AD%97%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1)
#### 无限长单位冲击响应滤波器（IIR）
- [脉冲响应不变法](https://colab.research.google.com/drive/1IKOSMxJTo-4fjCI27WyqkgJnxx685lH1)
- [双线性变换法](https://colab.research.google.com/drive/1cRhLZYzBSnvIIefoRusrPBGp3X4lRCPe)
#### 有限长单位冲激响应滤波器设计（FIR）
- [窗函数设计法](https://colab.research.google.com/drive/1KB_4UDbMw_jK4WrUgpFYQIvt1uZgjXtw)
- [频率取样设计法](https://colab.research.google.com/drive/1anBwfNl9frMVSsszHvm3ofsJevwwn22d)

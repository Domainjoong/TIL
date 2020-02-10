# Jupyter Setting


## 0. Setup Jupyter
- `pip install jupyter`
- Then, `Python3` available in Jupyter

## 1. add Kernels
- 현재 커널 확인: `jupyter kernelspec list`

### 1-1 add Java
#### Requirements
- Java JDK >= 9

#### Install pre-built binary from IJava
1. Download the release from: https://github.com/SpencerPark/IJava/releases
2. Unzip it into a temporary location
3. `python3 install.py`
4. Check that it installed with `jupyter kernelspec list` which should contain `Java`.



## Reference
- 주피터(Jupyter)의 다중 커널 기능: https://www.44bits.io/ko/post/understanding-jupyter-multiple-kernel-using-python2-and-python3-kernel
- IJava: https://github.com/SpencerPark/IJava


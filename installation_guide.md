
As oringinal develop recommend, tensorflow 1.4.0-rc0 is suggested. If user would like to use tensorflow 2.0.0 or above, tensorflow verison 2 behaviour should be disabled.

## Procedures:

use conda to install related dependencies

```shell
conda create --name spaceinvader

conda activate spaceinvader

conda install pygame (version 2 is recommended)

conda install tensorflow==1.4.0-rc0

cd hand_detection_spaceinvader

python3 spaceinvader.py
```
We have also test Unbuntu 18.04. If user encounters camera opening problem, you may try followings instructions:

```shell
sudo vim /etc/environment
QT_X11_NO_MITSHM=1
source /etc/environment
```

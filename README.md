# my_pyqt_setups
## Install qt designer
[Site](https://oswaltgottfried.wordpress.com/2018/05/13/%D1%83%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0-pyqt-designer/comment-page-1/)

## Setup project
Update pip to last version.
```
pip install invoke autoflake flake8 isort black mypy PySide2 PyQt5 
```

## If errors will raise
```
ldd /path_to_env/lib/python3.7/site-packages/PySide2/Qt/plugins/platforms/libqxcb.so | grep "not found"
```
Then, install not found packages

## Redis
[Site](https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-redis-on-ubuntu-16-04)

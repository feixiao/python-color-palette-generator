# Video frame color palette generator

A Python based program, which consists of a VLC player instance, that can generate color palettes for a specified number of video frames and ultimately combine them into a final color palette group image. (See the visual example below)



##### Example of the result image
![Screenshot](https://gauracs.me/wp-content/uploads/2020/12/color_palette_generator.jpg)

### Prerequisites

In order to run this program, several Python packages must be installed first using pip and Homebrew:

```shell
brew install cartr/qt4/pyqt@4
brew install cask/sip

conda activate py38
pip install python-vlc

pip install matplotlib
pip install numpy
pip install scikit-learn
pip install opencv-python
```

**Note:** This project is using the 4th version of PyQt - PyQt4, because this project is built on top of the existing [PyQt VLC player instance example](https://github.com/oaubert/python-vlc/blob/master/examples/qtvlc.py), which uses PyQt4 specifically.

### Run the program

```
python3 main.py
```

## License

MIT

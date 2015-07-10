# play-with-google-deep-dream

- to see my results, visit <http://copyfun.blogspot.tw/2015/07/play-with-google-deep-dream.html>

## setup.sh
- build caffe in <http://datasciencetoolbox.org/> enviroment.
- It maybe works for ubuntu, too.

## deepdream.py
- it's just a copy of <https://github.com/google/deepdream/blob/master/dream.ipynb>
- modified few lines in order to accept arguments

  `python deepdream.py source.jpg caffe/models/bvlc_googlenet/ 0.0 30`

## generateVideo.py
- using opencv to generate video shows the transformation of deep dream frames.
- you need to build opencv by your own
  - to build opencv, you can ref: http://drumrick.blogspot.tw/2015/06/build-opencv-300-bate-for-python.html

  `python generateVideo.py source.jpg frames/`

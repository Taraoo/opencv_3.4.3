・tensorflow
  -I/opt/tmp/include
  -L/opt/tmp/lib/tensorflow
  -llibtensorflow_cc
  
・opencv
  pkg-configを書き換え
  -L/opt/tmp/lib/opencv
  
  バージョン確認
  pkg-config --modversion opencv
  
  
  

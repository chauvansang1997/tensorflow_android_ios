bazel build -c opt --cxxopt=--std=c++11 --config=android_x86  --cpu=x86 \
  //tensorflow/lite/c:libtensorflowlite_c.so

bazel build -c opt --cxxopt=--std=c++11 --config=  --cpu=x86 \
  //tensorflow/lite/c:libtensorflowlite_c.so


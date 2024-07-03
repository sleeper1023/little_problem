# 超大txt大文件分割
使用linux或者git bash

# 按行分割
split -l 10000000 -d --additional-suffix=.txt Top2Billion-source.txt split-
#  -l 行数 --additional-suffix=分割后的后缀名  源文件  分割后的文件名前缀

# 按文件大小分割
split -b 10m -d --additional-suffix=.txt Top2Billion-source.txt split-
# -b 分割的单文件大小

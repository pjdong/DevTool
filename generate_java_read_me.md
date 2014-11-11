
根据web接口或含有Json字符串的文件 自动生成javabean

generate_java.py --h
usage: generate_java.py [-h] [--url URL] [--className CLASSNAME]
                        [--outPath OUTPATH] [--package PACKAGE]
                        [--outType OUTTYPE]

optional arguments:  
  -h, --help            show this help message and exit  
  --inpath              json data file   
  --url URL             parsed json url  
  --className CLASSNAME specify root class name
  --outPath OUTPATH     Automatic generation of storage file path ,default  
                        current path.  
  --package PACKAGE     Generating the .java file class package name  
  --outType OUTTYPE     1: parser 2:Gson  
  
实例：  
```
generate_java.py --url "url" --className Test  
generate_java.py --inpath "D:/json/mvs.txt" --className Text
```

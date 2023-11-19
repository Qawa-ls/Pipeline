# Flat Markdown Site
Simple single file site generated from a markdown content. 

## Prerequisites
Install pandoc using the appropriate package manager for your OS. For example, from ubuntu :
```
sudo apt update -y
sudo apt install -y pandoc
```

## Generate site
The site can be built with :
```
pandoc -s index.md --template _template_.html -o index.html
```

The downloadable docx file can be generated using :
```
pandoc -s index.md -o index.docx
```

## Result


![image](https://github.com/Qawa-ls/Pipeline/assets/95877116/10e0cbd0-c036-472b-8d2c-727d5fc78dec)

## Authors
Guillaume R.
Hugo C.

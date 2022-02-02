# hugo_for_duke
This is sample Hugo Website for Duke Class

1. Infrastructure as a Service - IAAS - 
2. Serverless - AWS host websites globally scalable - 
3. s3 Bucket - Object storage - Hugo will be running in s3 bucket. 
4. 99% reliable - 

Source: https://github.com/gohugoio/hugo

# STEPS
IN virtual TERMINAL
1. In environment, type ```wget https://github.com/gohugoio/hugo/releases/download/v0.92.1/hugo_0.92.1_Linux-64bit.tar.gz```
2. ```tar zxvf hugo_0.92.1_Linux-64bit.tar.gz``` # unzips tar file
3. Make directory to store hugo ```mkdir -p ~/bin```
4. mv hugo ~/bin

CHECK IF IT'S BEEN INSTALLED
1. in terminal type ```hugo version```
2. Find out where it's installed ```which hugo```

In terminal, type
1. ```hugo new site quickstart``` #creates new site and name it "quickstart"
2. ```mv quickstart/ hugo_for_duke/``` #move quickstart into ```hugo_for_duke``` folder


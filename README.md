# scapyInstallDependents

http://www.dongcoder.com/detail-622451.html  

python -V  
Python 2.7.10  

virtualenv venv 创建虚拟环境的目录，名为venv，它包含了Python可执行文件和拷贝过来的pip 库,能安装需要的包到虚拟环境   
source venv/bin/activate 激活刚才创建的虚拟环境  
deactivate 关闭虚拟环境  

## PyX-0.10
tar -zxvf pyx-0.10.tar.gz    
python setup.py install  
  
  
## pypcap-1.1.4  
tar -zxvf pypcap-1.1.4.tar.gz  
python setup.py install  
  
  
## gnuplot-py-1.8  
pip install numpy  
python setup.py install  
  
  
## dnet (libdnet-1.12)  
tar zxvf libdnet-1.12.tgz  
chmod a+x configure  
./configure && make  
make install  
  
cd python   
python setup.py install  
确认下 lib/python2.7/site-packages/下是否有dnet-1.12-py2.7.egg-info    dnet.so两个文件  
  
## scapy-2.3.1  
python setup.py install  

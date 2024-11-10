## 下载安装
### 从github下载
sudo apt install git -y && \
sudo rm -rf /tmp/1panelApps && \
git clone  https://github.com/sorchk/1panelApps /tmp/1panelApps && \
sudo rm -rf /datadisk/1panel/resource/apps/local/* && \
sudo cp -r /tmp/1panelApps/* /datadisk/1panel/resource/apps/local/

### 从gitee下载
sudo apt install git -y && \
sudo rm -rf /tmp/1panelApps && \
git clone https://gitee.com/sorc/1panelApps /tmp/1panelApps && \
sudo rm -rf /datadisk/1panel/resource/apps/local/* && \
sudo cp -r /tmp/1panelApps/* /datadisk/1panel/resource/apps/local/



### 添加1panel自动更新任务  自动更新本地应用仓库
sudo rm -rf /tmp/1panelApps && \
git clone https://gitee.com/sorc/1panelApps /tmp/1panelApps && \
sudo rm -rf /datadisk/1panel/resource/apps/local/* && \
sudo cp -r /tmp/1panelApps/* /datadisk/1panel/resource/apps/local/

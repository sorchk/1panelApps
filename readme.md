## 下载安装
### 从github下载
sudo apt install git -y && \
git clone  https://github.com/sorchk/1panelApps /tmp/1panelApps && \
sudo mv /tmp/1panelApps/* /datadisk/1panel/resource/apps/local/

### 从gitee下载
sudo apt install git -y && \
git clone https://gitee.com/sorc/1panelApps /tmp/1panelApps && \
sudo rm -rf /datadisk/1panel/resource/apps/local/* && \
sudo mv /tmp/1panelApps/* /datadisk/1panel/resource/apps/local/


### 添加1panel自动更新任务

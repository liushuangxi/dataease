<p align="center"><a href="https://dataease.io"><img src="https://dataease.oss-cn-hangzhou.aliyuncs.com/img/dataease-logo.png" alt="DataEase" width="300" /></a></p>
<h3 align="center">人人可用的开源数据可视化分析工具</h3>
<p align="center">
  <a href="https://www.gnu.org/licenses/old-licenses/gpl-3.0"><img src="https://img.shields.io/github/license/dataease/dataease?color=%231890FF" alt="License: GPL v3"></a>
  <a href="https://app.codacy.com/gh/dataease/dataease?utm_source=github.com&utm_medium=referral&utm_content=dataease/dataease&utm_campaign=Badge_Grade_Dashboard"><img src="https://app.codacy.com/project/badge/Grade/da67574fd82b473992781d1386b937ef" alt="Codacy"></a>
  <a href="https://github.com/dataease/dataease/releases/latest"><img src="https://img.shields.io/github/v/release/dataease/dataease" alt="Latest release"></a>
  <a href="https://github.com/dataease/dataease"><img src="https://img.shields.io/github/stars/dataease/dataease?color=%231890FF&style=flat-square" alt="Stars"></a>
  <a href="https://github.com/dataease/dataease/releases/latest"><img src="https://img.shields.io/github/downloads/dataease/dataease/total" alt="Downloads"></a>
</p>
<hr/>

# FIX
## 程序
### Excel上传只能显示100行

## MySQL 
docker run --name dataease-mysql -p3306:3306 -e MYSQL_ROOT_PASSWORD=891223 -d mysql:5.7.37 mysqld --lower_case_table_names=1 --group_concat_max_len=102400
### 忽略表名大小写
兼容 spring quartz

lower_case_table_names: 1 
### 修复 GROUP_CONCAT 截断
group_concat_max_len: 102400


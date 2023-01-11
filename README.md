# <span style="color:#2E86C1 ">*A manual for new starters in our group `ayanglab`*</span>

<br>


## <span style="color:#2E86C1 ">*Q&A*</span>
If you have any questions, <span style="color:red; font-size:1em">*please post it on issues*</span>, or find answers in  [FAQ](FAQ/FAQ.md).

### <span style="color:#2E86C1 ">*How to raise questions?*</span>
1. raise an issue in this [repository](https://github.com/XiaodanXing/Guide4Yanglab/issues)
2. email anyone you think can help with this issue and CC Dr Guang Yang

### <span style="color:#2E86C1 ">*How to propose suggestions?*</span>
1. raise an issue in this [repository](https://github.com/XiaodanXing/Guide4Yanglab/issues)
2. provide your suggestions and solutions in the issue
3. email anyone you think can help with this issue and CC Dr Guang Yang

---
<br>
<br>


## <span style="color:#2E86C1 ">*Computational Resources in `ayanglab`*</span>
---
### <span style="color:#2E86C1 ">*Local Workstations*</span>

|Name|Administrator|Email|
| :--- | :---: | ---: |
|yanglab0|Shiyi Wang <br> Zeyu Tang| s.wang22@imperial.ac.uk <br> zeyu.tang19@imperial.ac.uk |
|yanglab |Jiahao Huang| j.huang21@imperial.ac.uk |
|yanglab1|Ming Li| ming.li@imperial.ac.uk |
|yanglab2|Yang Nan| y.nan20@imperial.ac.uk |
|yanglab3|Xiaodan Xing| x.xing@imperial.ac.uk |
|yanglab4|Yingying Fang| y.fang@imperial.ac.uk |
|yanglab5|Ming Li| ming.li@imperial.ac.uk |
|yanglab6|Ming Li| ming.li@imperial.ac.uk |
|yanglab7|Yinzhe Wu| yinzhe.wu18@imperial.ac.uk |
|yanglab8|Fanwen Wang| fanwen.wang@imperial.ac.uk |

* check workstation IP in `Teams` (Path: Files/Workstation Information)
* ask Dr Guang Yang for `Teams` permission
---
<br>

### <span style="color:#2E86C1 ">*JADE2*</span>
* For more instructions on how to use JADE2, please check [JADE tutorial](JADE2_Tutorial.md).
---
<br>

### <span style="color:#2E86C1 ">*Colab*</span>
* For more instructions on how to set up on Google Colab, please check [Set up Google Colab](boilerplate_code/Colab.md).
---
<br>

### <span style="color:#2E86C1 ">*Dataset storage - NAS*</span>

|Name|NAS mount path on local workstation|Administrator|Email|
| :--- | :---: | :---: | ---: |
|NAS00| /media/NAS00 |Ming Li| ming.li@imperial.ac.uk |
|NAS01| /media/NAS01 <br> /media/NAS02 |Ming Li| ming.li@imperial.ac.uk |
|NAS02| /media/NAS03 |Ming Li| ming.li@imperial.ac.uk |
|NAS03| /media/NAS04 |Ming Li| ming.li@imperial.ac.uk |


* `Attention`: 
  * we are not running a company, we are just a research lab, we do not have any IT or Operation & Maintenance engineers
  * our NASs are not Enterprise Data Warehouse and we do not have disaster recovery backup
  * <span style="color:red; font-size:1em">*please do not load data to gpus from /media/NAS\* directly*</span>
  * when you train models, please transfer data to corresponding workstations, every workstation has large local HHD or SSD
  * <span style="color:red; font-size:1em">*only use NAS for dataset/models/projects backup*</span>
---
<br>

### <span style="color:#2E86C1 ">*SSH access to local workstations*</span>

1. install [zerotier](https://www.zerotier.com/download/)
2. ask Dr Guang Yang for oral zerotier access permission
3. email Ming Li (CC Dr Guang Yang) to authorize your zerotier connection
   (provide your zerotier address e.g., 530c509607)
4. login workstation (ask corresponding administrator	to help your set new account)

---
<br>
<br>

## <span style="color:#2E86C1 ">*Deep learning hands on tutorial*</span>
* please refer to [hands-on-tutorial](hands_on_tutorial.md)


---
<br>
<br>









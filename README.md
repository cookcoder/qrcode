Fork From https://github.com/itxstcom/qrcode
上面版本存在幾個問題：
1.數據庫
直接使用作者安裝版本裡面的DB替換
2.frBuild.cs
161行，  修改 whhere 為 where
3.frBuild.cs
103行，修改ctrParameters1為ctrParameters2
4.frBuild.cs
114行，修改Comm.Func.HasData(ds) == false為Comm.Func.HasData(ds) == true
5.frBuild.cs
59行，加上初始化語句_Rule = new Datas.Rules();
基本這樣就可以運行了，不可以的話，下面是全部完整的下載地址，要是有問題，歡迎找原作者。

链接：https://pan.baidu.com/s/12nDCG8mpWKSTz8f2-s59yQ 
提取码：wfja 

我這邊使用的是VS2017
=========================================================================================
原文

# qrcode
批量二维码生成工具
开源免费的二维码批量生成工具，可以按自己需要的规则批量生成二维码，比如数字自增二维码、随机生成二维码、按日期批量生成二维码。同时软件不仅免费还开源，永久不收费。
http://www.itxst.com/qrcode/

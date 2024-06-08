---
permalink: /
excerpt: "About me"
author_profile: true
redirect_frm: 
  - /about/
  - /about.html
---
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
北京大学工学院力学与工程科学系助理教授、研究员、博士生导师。2013年在中国科学技术大学近代力学系获得学士学位，2016年在中科院力学所获得硕士学位，2020年在德克萨斯大学奥斯汀分校工程力学系获得博士学位，同年入选玛丽居里学者在牛津大学数学所开展博后研究，2022年3月加入北京大学。

我的研究方向是固体力学，感兴趣与表界面、纳米材料、细长结构相关的力学问题(见<a href="https://zhaohedai.github.io/research/" style="text-decoration:none;color:indianred;">研究</a>)。目前已发表SCI论文60余篇（见<a href="https://zhaohedai.github.io/publications/" style="text-decoration:none;color:indianred;">论文</a>），授权中国发明专利3项。论文引用4000余次。其中以第一/通讯作者在力学、物理、材料等领域顶级期刊发表18篇，包括 JMPS、PRL、PNAS、Adv. Mater.、Nat. Commun.、Nano Lett. 等。曾入选欧盟玛丽居里学者、国家级人才计划（青年）等项目。


<p style="color:indianred;">每年招收机械硕士和（直/普）博士研究生；目前有博士后空缺，训练性课题支持本科生参与科研活动，欢迎<a href="mailto:daizh@pku.edu.cn" style="text-decoration:none;color:indianred;"><i class="fas fa-fw fa-envelope" style="color:indianred"></i>邮件</a>或前往<a href="https://map.baidu.com/poi/%E5%8C%97%E4%BA%AC%E5%A4%A7%E5%AD%A6%E5%B7%A5%E5%AD%A6%E9%99%A2-%E8%A5%BF%E9%97%A8/@12949105.3,4838235.03,19z?uid=4001ffab9513ef5ed23ce386&ugc_type=3&ugc_ver=1&device_ratio=1&compat=1&pcevaname=pc4.1&querytype=detailConInfo&da_src=shareurl" style="text-decoration:none;color:indianred;"><i class="fa fa-fw fa-map-marker" style="color:indianred"></i>新奥工学大楼420</a>讨论。</p>


My name is Zhaohe Dai, and I am an Assistant Professor in the Department of Mechanics and Engineering Science at the College of Engineering, Peking University (PKU). I received my B.Sc. degree in Theoretical and Applied Mechanics from the University of Science and Technology of China in 2013, my M.S. degree in Solid Mechanics from the Institute of Mechanics in 2016, and my Ph.D. in Solid Mechanics from the University of Texas at Austin in 2020. Prior to joining PKU in March 2022, I conducted postdoctoral research at the Mathematical Institute, University of Oxford, as a Marie Curie Fellow.

My research has equipped me with extensive knowledge in various areas of mechanics and materials, including thin film mechanics, surface phenomena, interface mechanics, 2D materials, and nanocarbon-based composites. My published works predominantly focus on the mechanics of thin solids and liquids, with particular emphasis on elasticity metrology, elastocapillarity, wrinkling instability, adhesion, and friction. Broadly, I am interested in understanding the deformation behaviors of slender solids when interacting with other objects, including liquids, and both rigid and deformable substrates.

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Roll a Number</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Raleway:wght@300;400;700&display=swap">
    <style>
        body {
            font-family: 'Raleway', sans-serif;
            text-align: center;
            margin-top: 50px;
            background-color: #f5f5f5;
            color: #333;
        }
        h1 {
            font-size: 36px;
            color: #2c3e50;
            margin-bottom: 20px;
            font-weight: 700;
        }
        #result {
            font-size: 72px;
            color: #e74c3c;
            margin: 20px 0;
            padding: 20px;
            border-radius: 10px;
            background-color: #ecf0f1;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        button {
            font-size: 24px;
            padding: 15px 30px;
            color: #fff;
            background-color: #3498db;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            box-shadow: 0 4px 6px rgba(52, 152, 219, 0.5);
            transition: background-color 0.3s ease, box-shadow 0.3s ease;
        }
        button:hover {
            background-color: #2980b9;
            box-shadow: 0 6px 12px rgba(52, 152, 219, 0.5);
        }
    </style>
</head>
<body>
    <h1>Roll a Number between 0 and 100</h1>
    <div id="result">0</div>
    <button onclick="rollNumber()">Roll</button>

    <script>
        function rollNumber() {
            const randomNumber = Math.floor(Math.random() * 101); // Random number between 0 and 100
            document.getElementById('result').innerText = randomNumber;
            if (randomNumber === 0 || randomNumber === 100) {
                alert("Congrats! Your rolling result has been sent to daizh@pku.edu.cn");
            }
        }
    </script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<!-- 版权:季风吹响大海,QQ:630876811 -->
<!-- 免费分享请勿二次贩卖 -->
<!-- 仅供学习交流使用,下载请于24小时删除 -->

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.0/dist/css/bootstrap.min.css"
    integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">
  <link rel="stylesheet" href="./css/index.css">
  <script src="https://cdn.bootcdn.net/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"
    integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo"
    crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.0/dist/js/bootstrap.min.js"
    integrity="sha384-OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI"
    crossorigin="anonymous"></script>
  <script src="./js/xtiper.min.js"></script>
  <link rel="stylesheet" href="./css/xtiper.css">
  <title>Document</title>
  <style>

  </style>
</head>

<body>
  <div class="container">
    <!-- 2、定义行-->
    <div class="row box-widht">
      <!-- 3、定义元素 -->

      <div class="col-lg-6 col-sm-12" style=" margin: auto;">
        <div class="logo"></div>
        <div class="alert alert-primary info" role="alert">
          <span> 1.下载<a href="http://app.mi.com/details?id=com.xiaomi.hm.health"
              target="_blank">小米运动</a>注册账号,设置密码</span>
        </div>
        <div class="alert alert-primary info" role="alert">
          <span>2.App内绑定你想同步数据的项目</span>
        </div>
        <div>
          <div class="iconcss">
            <svg width="1.5em" height="1.5em" viewBox="0 0 18 18" class="bi bi-person-fill icon" fill="currentColor"
              xmlns="http://www.w3.org/2000/svg">
              <path fill-rule="evenodd"
                d="M3 14s-1 0-1-1 1-4 6-4 6 3 6 4-1 1-1 1H3zm5-6a3 3 0 1 0 0-6 3 3 0 0 0 0 6z" />
            </svg>
            <input type="text" name="user" id="user" class="form-control marginbottom" placeholder="请输入小米账号">
          </div>
          <div class="iconcss"> <svg width="1.5em" height="1.5em" viewBox="0 0 18 18" class="bi bi-lock-fill icon"
              fill="currentColor" xmlns="http://www.w3.org/2000/svg">
              <path d="M2.5 9a2 2 0 0 1 2-2h7a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2h-7a2 2 0 0 1-2-2V9z" />
              <path fill-rule="evenodd" d="M4.5 4a3.5 3.5 0 1 1 7 0v3h-1V4a2.5 2.5 0 0 0-5 0v3h-1V4z" />
            </svg>
            <input type="password" name="password" id="password" class="form-control marginbottom" placeholder="请输入密码">
          </div>

          <div class="iconcss">
            <svg width="1.5em" height="1.5em" viewBox="0 0 18 18" class="bi bi-heart-fill icon" fill="currentColor"
              xmlns="http://www.w3.org/2000/svg">
              <path fill-rule="evenodd" d="M8 1.314C12.438-3.248 23.534 4.735 8 15-7.534 4.736 3.562-3.248 8 1.314z" />
            </svg>
            <input type="text" name="step" id="step" class="form-control marginbottom" placeholder="请输入步数">
          </div>

        </div>
        <div class="btncss">
          <button type="button" class="btn btn-warning">提交</button>
          <div class="spinner-border text-primary" role="status">
            <span class="sr-only loading">Loading...</span>
          </div>
        </div>

      </div>
    </div>
  </div>
  <div class="foot">
    <span>
  <script src="./js/index.js"></script>
  <script>
    $('.text-primary').hide()
  </script>
</body>

</html>

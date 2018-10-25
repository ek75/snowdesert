# snowdesert
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>Snow desert</title>
<meta name="generator" content="WYSIWYG Web Builder 14 Trial Version - http://www.wysiwygwebbuilder.com">
<link href="base/jquery-ui.min.css" rel="stylesheet">
<link href="Егор_1.css" rel="stylesheet">
<link href="index.css" rel="stylesheet">
<script src="jquery-1.12.4.min.js"></script>
<script src="jquery-ui.min.js"></script>
<script src="wwb14.min.js"></script>
<script>
$(document).ready(function()
{
   $("#RollOverText2").hover(function()
   {
      var y = $(this).height() - $(".caption", this).height();
      $(".caption", this).css("top", y);
      $(".caption", this).stop().animate({opacity: 0.60},{queue:false, duration:500});
   }, function()
   {
      $(".caption", this).stop().animate({opacity: 0},{queue:false, duration:500});
   });
   $("#Progressbar1").progressbar(
   {
      value: 100,
      change: function() 
      {
         $("#Progressbar1-label").text($(this).progressbar('value') + '%');
      }
   });
   $("#Progressbar2").progressbar(
   {
      value: 15,
      change: function() 
      {
         $("#Progressbar2-label").text($(this).progressbar('value') + '%');
      }
   });
   $("#Progressbar3").progressbar(
   {
      value: 100,
      change: function() 
      {
         $("#Progressbar3-label").text($(this).progressbar('value') + '%');
      }
   });
   $(".SlideMenu1_Folder a").click(function()
   {
      var $popup = $(this).parent().find('ul');
      if ($popup.is(':hidden'))
      {
         $popup.fadeIn();
         $popup.attr('aria-expanded', 'true');
      }
      else
      {
         $popup.fadeOut();
         $popup.attr('aria-expanded', 'false');
      }
   });
});
</script>
</head>
<body>
<a href="http://www.wysiwygwebbuilder.com" target="_blank"><img src="images/builtwithwwb14.png" alt="WYSIWYG Web Builder" style="position:absolute;left:988px;top:601px;margin: 0;border-width:0;z-index:250"></a>
<input type="submit" id="Button1" onclick="ShowObject('wb_Shape1', 1);ShowObject('Button3', 1);ShowObject('wb_Text1', 0);ShowObject('Button1', 0);ShowObject('wb_Picture1', 1);ShowObject('wb_Text3', 0);ShowObject('wb_Image1', 1);ShowObject('Button4', 1);ShowObject('wb_Image4', 1);ShowObject('Progressbar1', 1);ShowObject('Progressbar2', 1);ShowObject('wb_IconFont1', 1);ShowObject('wb_IconFont2', 1);return false;" name="" value="Начать игру!" style="position:absolute;left:502px;top:87px;width:370px;height:26px;z-index:35;">
<div id="RollOverText2" style="overflow:hidden;position:absolute;left:243px;top:100px;width:0px;height:0px;z-index:36;">
   <img alt="Title" class="image" src="">
   <div class="caption">
      <div class="title">Title</div>
      <p class="description">Image description goes here</p>
      <a class="link" href="">More information</a>
   </div>
</div>
<div id="wb_Text1" style="position:absolute;left:492px;top:11px;width:415px;height:62px;z-index:37;">
<span style="color:#FFFFFF;font-family:Arial;font-size:53px;"><strong>SNOW DESERT</strong></span></div>
<div id="wb_ClipArt1" style="position:absolute;left:275px;top:525px;width:97px;height:83px;z-index:38;">
<img src="images/img0001.png" id="ClipArt1" alt="" style="width:97px;height:83px;"></div>
<div id="wb_Shape1" style="position:absolute;left:427px;top:484px;width:543px;height:109px;visibility:hidden;z-index:39;">
<img src="images/img0002.png" id="Shape1" alt="" style="width:543px;height:109px;"></div>
<input type="submit" id="Button3" onclick="ShowObject('wb_Shape1', 0);ShowObject('Button3', 0);ShowObject('wb_Picture1', 0);ShowObject('wb_Picture3', 1);ShowObject('wb_Shape2', 1);ShowObject('Button6', 1);ShowObject('Button7', 1);return false;" name="" value="Далее..." style="position:absolute;left:874px;top:608px;width:96px;height:25px;visibility:hidden;z-index:40;">
<picture id="wb_Picture1" style="position:absolute;left:428px;top:124px;width:543px;height:360px;visibility:hidden;z-index:41">
<img src="images/0_155a15_b540290b_XXL.jpg" id="Picture1" alt="" srcset="">
</picture>
<div id="wb_Text3" style="position:absolute;left:425px;top:140px;width:577px;height:22px;z-index:42;">
<span style="color:#FFFFFF;font-family:'Times New Roman';font-size:20px;">Вы оказались посреди тундры и ваша главная&nbsp; задача - выжить!</span></div>
<div id="wb_Image1" style="position:absolute;left:427px;top:1px;width:96px;height:95px;visibility:hidden;z-index:43;">
<img src="images/backpack-picture-30020.png" id="Image1" alt=""></div>
<table style="position:absolute;left:160px;top:10px;width:256px;height:283px;z-index:44;visibility:hidden;" id="Table1">
<tr>
<td class="cell0"><picture id="wb_Picture2" style="display:none;width: 100%;height:45px;z-index:0">
<img src="images/imgonline-com-ua-Transparent-backgr-PdwxNjrMoI.png" id="Picture2" alt="" srcset="">
</picture>
</td>
<td class="cell0"><div id="wb_Image2" style="display:none;width:47px;height:35px;z-index:1;">
<img src="images/knife-png-hunting-knife-png-1000.png" id="Image2" alt="">
</div>
</td>
<td class="cell0"><div id="wb_Image3" style="display:none;width:47px;height:45px;z-index:2;">
<img src="images/imgonline-com-ua-Transparent-backgr-WJr6otOutZZ7f2Av.png" id="Image3" alt="">
</div>
</td>
<td class="cell0"><div id="wb_Image6" style="display:none;width:43px;height:46px;z-index:3;">
<img src="images/imgonline-com-ua-Transparent-backgr-6JOOqZ5uUtJFTF.png" id="Image6" alt="">
</div>
</td>
<td class="cell0"><div id="wb_Image7" style="display:none;width:49px;height:49px;z-index:4;">
<img src="images/imgonline-com-ua-Transparent-backgr-t5ae5u0BGZ.png" id="Image7" alt="">
</div>
</td>
</tr>
<tr>
<td class="cell0"><picture id="wb_Picture5" style="display:none;width: 100%;height:47px;z-index:5">
<img src="images/imgonline-com-ua-Transparent-backgr-kzY1ZjPRWbd.png" id="Picture5" alt="" srcset="">
</picture>
</td>
<td class="cell0"><picture id="wb_Picture6" style="display:none;width: 100%;height:47px;z-index:6">
<img src="images/imgonline-com-ua-Transparent-backgr-kzY1ZjPRWbd.png" id="Picture6" alt="" srcset="">
</picture>
</td>
<td class="cell0"><picture id="wb_Picture7" style="display:none;width: 100%;height:47px;z-index:7">
<img src="images/imgonline-com-ua-Transparent-backgr-kzY1ZjPRWbd.png" id="Picture7" alt="" srcset="">
</picture>
</td>
<td class="cell0"><picture id="wb_Picture8" style="display:none;width: 100%;height:43px;z-index:8">
<img src="images/imgonline-com-ua-Transparent-backgr-RA4byaynZkyrxuf.png" id="Picture8" alt="" srcset="">
</picture>
</td>
<td class="cell0"><picture id="wb_Picture9" style="display:none;width: 100%;height:44px;z-index:9">
<img src="images/imgonline-com-ua-Transparent-backgr-kWUYzvSQMQwSzG3Z.png" id="Picture9" alt="" srcset="">
</picture>
</td>
</tr>
<tr>
<td class="cell0"><picture id="wb_Picture10" style="display:none;width: 100%;height:49px;z-index:10">
<img src="images/imgonline-com-ua-Transparent-backgr-HPAFEnC38v0.png" id="Picture10" alt="" srcset="">
</picture>
</td>
<td class="cell1"><span style="color:#000000;font-family:Arial;font-size:13px;line-height:16px;"> </span></td>
<td class="cell1"><span style="color:#000000;font-family:Arial;font-size:13px;line-height:16px;"> </span></td>
<td class="cell2"><span style="color:#000000;font-family:Arial;font-size:13px;line-height:16px;"> </span></td>
<td class="cell2"><span style="color:#000000;font-family:Arial;font-size:13px;line-height:16px;"> </span></td>
</tr>
<tr>
<td colspan="4" class="cell3"><picture id="wb_Picture12" style="display:none;width: 100%;height:113px;z-index:11">
<img src="images/imgonline-com-ua-Transparent-backgr-VKbaljaZ0wKCZ8.png" id="Picture12" alt="" srcset="">
</picture>
</td>
<td class="cell4"><div id="wb_Image8" style="display:none;width:39px;height:127px;z-index:12;">
<img src="images/imgonline-com-ua-Transparent-backgr-zNJFu0rGUx.png" id="Image8" alt="">
</div>
</td>
</tr>
</table>
<input type="submit" id="Button4" onclick="ShowObject('Table1', 1);ShowObject('Button4', 0);ShowObject('Button5', 1);ShowObjectWithEffect('wb_Image2', 1, '', 0);ShowObjectWithEffect('wb_Image3', 1, '', 0);ShowObjectWithEffect('wb_Picture2', 1, '', 0);ShowObjectWithEffect('wb_Picture12', 1, '', 0);return false;" name="" value="Открыть" style="position:absolute;left:427px;top:96px;width:96px;height:25px;visibility:hidden;z-index:45;">
<input type="submit" id="Button5" onclick="ShowObject('Table1', 0);ShowObject('Button5', 0);ShowObject('Button4', 1);ShowObjectWithEffect('wb_Image2', 0, '', 0);ShowObjectWithEffect('wb_Image3', 0, '', 0);ShowObjectWithEffect('wb_Picture2', 0, '', 0);ShowObjectWithEffect('wb_Image6', 0, '', 0);ShowObjectWithEffect('wb_Image7', 0, '', 0);ShowObjectWithEffect('wb_Image8', 0, '', 0);ShowObjectWithEffect('wb_Picture12', 0, '', 0);return false;" name="" value="Закрыть" style="position:absolute;left:427px;top:96px;width:96px;height:25px;visibility:hidden;z-index:46;">
<picture id="wb_Picture3" style="position:absolute;left:428px;top:124px;width:543px;height:361px;visibility:hidden;z-index:47">
<img src="images/s6kac7.jpg" id="Picture3" alt="" srcset="">
</picture>
<div id="wb_Shape2" style="position:absolute;left:428px;top:484px;width:543px;height:108px;visibility:hidden;z-index:48;">
<img src="images/img0003.png" id="Shape2" alt="" style="width:543px;height:108px;"></div>
<div id="wb_Image4" style="position:absolute;left:516px;top:7px;width:100px;height:106px;visibility:hidden;z-index:49;">
<img src="images/true_north_compass.png" id="Image4" alt=""></div>
<div id="wb_Form1" style="position:absolute;visibility:hidden;left:43px;top:607px;width:400px;height:165px;z-index:50;">
<form name="SNOW_DESERT" method="post" action="mailto:egorkuku@inbox.ru" enctype="text/plain" id="Form1">
<label for="TextArea1" id="Label1" style="visibility:hidden;position:absolute;left:10px;top:0px;width:182px;height:16px;line-height:16px;z-index:26;">Оставьте мне свой отзыв!</label>
<input type="submit" id="Button2" name="" value="ОТПРАВИТЬ" style="position:absolute;left:114px;top:135px;width:96px;height:25px;visibility:hidden;z-index:27;">
<textarea name="Your feedback" id="TextArea1" style="position:absolute;left:10px;top:24px;width:190px;height:90px;visibility:hidden;z-index:28;" rows="4" cols="29" spellcheck="false"></textarea>
</form>
</div>
<input type="submit" id="Button6" onclick="ShowObject('wb_Text4', 1);ShowObject('wb_Picture4', 1);ShowObject('wb_Picture3', 0);ShowObject('wb_Shape2', 0);ShowObject('wb_Shape3', 1);ShowObject('Button6', 0);ShowObject('Button7', 0);return false;" name="" value="Атака" style="position:absolute;left:874px;top:608px;width:97px;height:25px;visibility:hidden;z-index:51;">
<input type="submit" id="Button7" onclick="ShowObject('wb_Image5', 1);ShowObject('wb_Shape4', 1);ShowObject('Button7', 0);ShowObject('Button8', 1);return false;" name="" value="Уйти" style="position:absolute;left:428px;top:608px;width:96px;height:25px;visibility:hidden;z-index:52;">
<picture id="wb_Picture4" style="position:absolute;left:428px;top:124px;width:543px;height:360px;visibility:hidden;z-index:53">
<img src="images/Безымянный.png" id="Picture4" alt="" srcset="">
</picture>
<div id="wb_Text4" style="position:absolute;left:528px;top:185px;width:371px;height:60px;visibility:hidden;z-index:54;">
<span style="color:#000000;font-family:Arial;font-size:53px;">GAME OVER!</span></div>
<div id="wb_Shape3" style="position:absolute;left:428px;top:484px;width:543px;height:107px;visibility:hidden;z-index:55;">
<img src="images/img0004.png" id="Shape3" alt="" style="width:543px;height:107px;"></div>
<div id="wb_Image5" style="position:absolute;left:428px;top:124px;width:543px;height:361px;visibility:hidden;z-index:56;">
<img src="images/3764225.jpg" id="Image5" alt=""></div>
<div id="wb_Shape4" style="position:absolute;left:428px;top:485px;width:543px;height:107px;visibility:hidden;z-index:57;">
<img src="images/img0005.png" id="Shape4" alt="" style="width:543px;height:107px;"></div>
<input type="submit" id="Button8" onclick="ShowObject('Button9', 1);ShowObject('Button4', 0);ShowObject('Dialog', 1);ShowObject('wb_Shape5', 1);ShowObject('wb_Shape6', 1);ShowObject('Button10', 1);ShowObject('wb_Image9', 1);ShowObject('wb_Shape7', 1);ShowObject('Button12', 1);ShowObject('Button8', 0);return false;" name="" value="Далее..." style="position:absolute;left:873px;top:608px;width:97px;height:25px;visibility:hidden;z-index:58;">
<input type="submit" id="Button9" onclick="ShowObject('Table1', 1);ShowObjectWithEffect('wb_Image2', 1, '', 0);ShowObjectWithEffect('wb_Image3', 1, '', 0);ShowObjectWithEffect('wb_Picture2', 1, '', 0);ShowObjectWithEffect('wb_Image7', 1, '', 0);ShowObjectWithEffect('wb_Image6', 1, '', 0);ShowObjectWithEffect('wb_Image8', 1, '', 0);ShowObjectWithEffect('wb_Picture5', 1, '', 0);ShowObjectWithEffect('wb_Picture6', 1, '', 0);ShowObjectWithEffect('wb_Picture7', 1, '', 0);ShowObjectWithEffect('wb_Picture8', 1, '', 0);ShowObjectWithEffect('wb_Picture9', 1, '', 0);ShowObjectWithEffect('wb_Picture10', 1, '', 0);ShowObject('wb_Picture11', 1);ShowObject('Button11', 1);ShowObject('Button9', 0);ShowObjectWithEffect('wb_Picture12', 1, '', 0);return false;" name="" value="Открыть" style="position:absolute;left:427px;top:96px;width:96px;height:25px;visibility:hidden;z-index:59;">
<picture id="wb_Picture11" style="position:absolute;left:212px;top:113px;width:52px;height:49px;visibility:hidden;z-index:60">
<img src="images/imgonline-com-ua-Transparent-backgr-t0jg3v5e0ZZcC.png" id="Picture11" alt="" srcset="">
</picture>
<div id="wb_Shape5" style="position:absolute;left:202px;top:342px;width:173px;height:160px;visibility:hidden;z-index:61;">
<img src="images/img0006.png" id="Shape5" alt="" style="width:173px;height:160px;"></div>
<div id="wb_Shape6" style="position:absolute;left:202px;top:316px;width:173px;height:35px;visibility:hidden;z-index:62;">
<img src="images/img0007.png" id="Shape6" alt="" style="width:173px;height:35px;"></div>
<input type="submit" id="Button10" onclick="ShowObject('wb_Shape5', 0);ShowObject('wb_Shape6', 0);ShowObject('Button10', 0);return false;" name="" value="Закрыть" style="position:absolute;left:279px;top:477px;width:96px;height:25px;visibility:hidden;z-index:63;">
<input type="submit" id="Button11" onclick="ShowObject('Button11', 0);ShowObject('Button9', 1);ShowObject('Table1', 0);ShowObjectWithEffect('wb_Image2', 0, '', 0);ShowObjectWithEffect('wb_Image3', 0, '', 0);ShowObjectWithEffect('wb_Picture2', 0, '', 0);ShowObjectWithEffect('wb_Image7', 0, '', 0);ShowObjectWithEffect('wb_Image6', 0, '', 0);ShowObjectWithEffect('wb_Image8', 0, '', 0);ShowObjectWithEffect('wb_Picture5', 0, '', 0);ShowObjectWithEffect('wb_Picture6', 0, '', 0);ShowObjectWithEffect('wb_Picture7', 0, '', 0);ShowObjectWithEffect('wb_Picture8', 0, '', 0);ShowObjectWithEffect('wb_Picture9', 0, '', 0);ShowObjectWithEffect('wb_Picture10', 0, '', 0);ShowObject('wb_Picture11', 0);ShowObjectWithEffect('wb_Picture12', 0, '', 0);return false;" name="" value="Закрыть" style="position:absolute;left:427px;top:96px;width:96px;height:25px;visibility:hidden;z-index:64;">
<div id="wb_Image9" style="position:absolute;left:428px;top:124px;width:542px;height:360px;visibility:hidden;z-index:65;">
<img src="images/3264.jpg" id="Image9" alt="KONICA MINOLTA DIGITAL CAMERA" title="KONICA MINOLTA DIGITAL CAMERA"></div>
<div id="wb_Shape7" style="position:absolute;left:428px;top:484px;width:542px;height:107px;visibility:hidden;z-index:66;">
<img src="images/img0008.png" id="Shape7" alt="" style="width:542px;height:107px;"></div>
<input type="submit" id="Button12" onclick="ShowObject('Button13', 1);ShowObject('wb_Shape8', 1);ShowObject('wb_Shape9', 1);ShowObject('Button15', 1);ShowObject('wb_Picture13', 1);ShowObject('wb_Shape10', 1);ShowObject('Button12', 0);ShowObject('Progressbar2', 0);ShowObject('Progressbar3', 1);return false;" name="" value="Далее..." style="position:absolute;left:872px;top:608px;width:98px;height:25px;visibility:hidden;z-index:67;">
<input type="submit" id="Button13" onclick="ShowObjectWithEffect('wb_Image2', 1, '', 0);ShowObjectWithEffect('wb_Picture2', 1, '', 0);ShowObjectWithEffect('wb_Image6', 1, '', 0);ShowObjectWithEffect('wb_Image8', 1, '', 0);ShowObjectWithEffect('wb_Picture5', 1, '', 0);ShowObjectWithEffect('wb_Picture6', 1, '', 0);ShowObjectWithEffect('wb_Picture9', 1, '', 0);ShowObjectWithEffect('wb_Picture10', 1, '', 0);ShowObject('Table1', 1);ShowObject('Button13', 0);ShowObject('Button14', 1);ShowObjectWithEffect('wb_Picture12', 1, '', 0);return false;" name="" value="Открыть" style="position:absolute;left:427px;top:96px;width:96px;height:25px;visibility:hidden;z-index:68;">
<input type="submit" id="Button14" onclick="ShowObjectWithEffect('wb_Picture12', 0, '', 0);ShowObject('Table1', 0);ShowObjectWithEffect('wb_Image2', 0, '', 0);ShowObjectWithEffect('wb_Picture2', 0, '', 0);ShowObjectWithEffect('wb_Image6', 0, '', 0);ShowObjectWithEffect('wb_Image8', 0, '', 0);ShowObjectWithEffect('wb_Picture5', 0, '', 0);ShowObjectWithEffect('wb_Picture6', 0, '', 0);ShowObjectWithEffect('wb_Picture9', 0, '', 0);ShowObjectWithEffect('wb_Picture10', 0, '', 0);ShowObject('Button14', 0);ShowObject('Button13', 1);return false;" name="" value="Закрыть" style="position:absolute;left:427px;top:96px;width:96px;height:25px;visibility:hidden;z-index:69;">
<div id="wb_Shape8" style="position:absolute;left:202px;top:351px;width:173px;height:86px;visibility:hidden;z-index:70;">
<img src="images/img0009.png" id="Shape8" alt="" style="width:173px;height:86px;"></div>
<div id="wb_Shape9" style="position:absolute;left:202px;top:310px;width:173px;height:47px;visibility:hidden;z-index:71;">
<img src="images/img0010.png" id="Shape9" alt="" style="width:173px;height:47px;"></div>
<input type="submit" id="Button15" onclick="ShowObject('Button15', 0);ShowObject('wb_Shape8', 0);ShowObject('wb_Shape9', 0);return false;" name="" value="Закрыть" style="position:absolute;left:279px;top:412px;width:96px;height:25px;visibility:hidden;z-index:72;">
<picture id="wb_Picture13" style="position:absolute;left:428px;top:124px;width:542px;height:360px;visibility:hidden;z-index:73">
<img src="images/0_155a15_b540290b_XXL.jpg" id="Picture13" alt="" srcset="">
</picture>
<div id="wb_Shape10" style="position:absolute;left:428px;top:484px;width:542px;height:107px;visibility:hidden;z-index:74;">
<img src="images/img0011.png" id="Shape10" alt="" style="width:542px;height:107px;"></div>
<div id="wb_Form2" style="position:absolute;left:0px;top:524px;width:283px;height:140px;z-index:75;">
<form name="contact" method="post" action="mailto:egorkuku@inbox.ru?subject=Contact Information" id="Form2">
<label for="Editbox1" id="Label2" style="position:absolute;left:10px;top:20px;width:35px;height:16px;line-height:16px;z-index:29;">Name:</label>
<label for="Editbox2" id="Label3" style="position:absolute;left:10px;top:58px;width:35px;height:16px;line-height:16px;z-index:30;">Email:</label>
<input type="text" id="Editbox2" style="position:absolute;left:63px;top:58px;width:190px;height:16px;z-index:31;" name="email" value="" spellcheck="false">
<input type="text" id="Editbox1" style="position:absolute;left:63px;top:19px;width:190px;height:16px;z-index:32;" name="name" value="" spellcheck="false">
<input type="submit" id="Button16" name="" value="Send" style="position:absolute;left:63px;top:97px;width:96px;height:25px;z-index:33;">
</form>
</div>
<div id="Progressbar1"  style="position:absolute;left:673px;top:32px;visibility:hidden;width:295px;height:24px;z-index:76;">
<div id="Progressbar1-label">100%</div>
</div>
<div id="wb_IconFont1" style="position:absolute;left:622px;top:24px;width:51px;height:42px;visibility:hidden;text-align:center;z-index:77;">
<div id="IconFont1"><i class="material-icons">&#xe87d;</i></div></div>
<div id="Progressbar2"  style="position:absolute;left:673px;top:73px;visibility:hidden;width:295px;height:24px;z-index:78;">
<div id="Progressbar2-label">15%</div>
</div>
<div id="wb_IconFont2" style="position:absolute;left:628px;top:69px;width:38px;height:35px;visibility:hidden;text-align:center;z-index:79;">
<div id="IconFont2"><i class="material-icons">&#xe56c;</i></div></div>
<div id="Progressbar3"  style="position:absolute;left:673px;top:73px;visibility:hidden;width:295px;height:24px;z-index:80;">
<div id="Progressbar3-label">100%</div>
</div>
<div id="SlideMenu1" style="position:absolute;left:19px;top:11px;width:108px;height:620px;z-index:81;">
<ul role="menu">
   <li class="SlideMenu1_Folder" aria-haspopup="true"><a>Обратная связь</a>
      <ul role="menu" aria-expanded="true">
         <li><a role="menuitem" href="http://vk.com/egor_kuku">Вконтакте</a></li>
         <li><a role="menuitem" href="https://www.facebook.com/profile.php?id=100013190319108">Facebook</a></li>
      </ul>
   </li>
</ul>
</div>
<div id="PageHeader1" style="position:absolute;text-align:left;left:0px;top:0px;width:100%;height:1px;z-index:7777;">
</div>
</body>
</html>

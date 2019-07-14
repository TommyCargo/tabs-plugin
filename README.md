# tabs-plugin
Плагин реализующий вкладки

Вызовите функцию tabs(infoHeaderTabClassSelector, infoHeaderParentClassSelector, infoTabContentSelector);
Пример script.js:

tabs('.info-header-tab', '.info-header', '.info-tabcontent');

Пример HTML:

<div class="info" >
	<div class="info-header">
	<div class="info-header-tab">1 вкладка</div>
	<div class="info-header-tab">2 вкладка</div>
	<div class="info-header-tab">3вкладка</div>	
</div>
  <div class="info-tabcontent> Содержание вкладки №1 </div>
  <div class="info-tabcontent> Содержание вкладки №2 </div>
  <div class="info-tabcontent> Содержание вкладки №3 </div>
  <script src="tPlug.js"></script>
	<script src="script.js"></script>

CSS:

.info .show {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}

.info .hide {
  display: none;
}




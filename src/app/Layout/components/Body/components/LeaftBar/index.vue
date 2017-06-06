<template>
  <div id="leftBar" class="sideBar left animated fadeInLeft">
    <div class="bar-content" id="leftContent">
      <div class="con-5">
        <div class="graph-title" style="border-left: 5px solid rgb(0, 180, 255);"><span class="graph-brand-text"
                                                                                        id="graphBrandTextPie">年度事件汇聚</span><span
          class="graph-brand-subtext" id="graphBrandTextPieTtile">Statistics Of Area Event</span></div>
        <div class="row" style="margin-top: -10px;">
          <div id="span0" class="col-md-4">
            <div class="userSumCountsItems">
              <div id="uItemsCount0" class="rptValueTextLg">
                <div data-count="this" data-from="1" data-to="51" data-suffix="" data-duration="1"
                     data-easing="false">51


                </div>
              </div>
              <p id="uUtilDetailTotal0" class="rptLabelTextSm">街面秩序</p></div>
          </div>
          <div id="span1" class="col-md-4">
            <div class="userSumCountsItems">
              <div id="uItemsCount1" class="rptValueTextLg">
                <div data-count="this" data-from="1" data-to="18" data-suffix="" data-duration="1"
                     data-easing="false">18


                </div>
              </div>
              <p id="uUtilDetailTotal1" class="rptLabelTextSm">社会管理</p></div>
          </div>
          <div id="span2" class="col-md-4">
            <div class="userSumCountsItems">
              <div id="uItemsCount2" class="rptValueTextLg">
                <div data-count="this" data-from="1" data-to="14" data-suffix="" data-duration="1"
                     data-easing="false">14


                </div>
              </div>
              <p id="uUtilDetailTotal2" class="rptLabelTextSm">施工管理</p></div>
          </div>
        </div>
        <div id="EchartPie" _echarts_instance_="ec_1496624828104"
             style="-webkit-tap-highlight-color: transparent; user-select: none; position: relative; background: transparent;">
          <div style="position: relative; overflow: hidden; width: 300px; height: 149px;">
            <canvas width="300" height="149" data-zr-dom-id="zr_0"
                    style="position: absolute; left: 0px; top: 0px; width: 300px; height: 149px; user-select: none; -webkit-tap-highlight-color: rgba(0, 0, 0, 0);"></canvas>
          </div>
          <div></div>
        </div>
      </div>
      <div class="con-3">
        <div class="graph-title" style="border-left: 5px solid rgb(0, 180, 255);"><span class="graph-brand-text"
                                                                                        id="graphBrandTextHistogram">区域事件汇聚</span><span
          class="graph-brand-subtext" id="graphBrandTextHistogramTtile">Statistics Of Annual Event</span></div>
        <div id="EchartHistogram" class="gif" _echarts_instance_="ec_1496624828105"
             style="-webkit-tap-highlight-color: transparent; user-select: none; position: relative; background: transparent;">
          <div style="position: relative; overflow: hidden; width: 300px; height: 49px;">
            <canvas width="300" height="49" data-zr-dom-id="zr_0"
                    style="position: absolute; left: 0px; top: 0px; width: 300px; height: 49px; user-select: none; -webkit-tap-highlight-color: rgba(0, 0, 0, 0);"></canvas>
          </div>
          <div></div>
        </div>
      </div>
      <div id="sort3" class="con-2" style="padding-top: 5px;">
        <div id="thematicMap" class="row-12 col-lg-12 col-md-12 col-sm-12" style="text-align: center;"><a
          href="javascript:void(0)"><b style="color:#fff">TOP3</b></a></div>
        <div id="thematicMap" class="row-12 col-lg-12 col-md-12 col-sm-12" style="text-align: center;">
          <div id="top_1" class="media top_ref" data="机动车乱停放">
            <div class="media-left"><a href="http://portal.smartxspace.com/App/cityCase/cityCase.html#"><img
              class="media-object" src="./theme/img/1_gray.png" alt="..."></a></div>
            <div class="media-body top"><h4 class="media-heading" style="margin-bottom: 0px;"></h4>机动车乱停放<a
              href="http://portal.smartxspace.com/App/cityCase/cityCase.html#" style="float:right"><span
              class="badge">24</span></a></div>
          </div>
        </div>
        <div id="thematicMap" class="row-12 col-lg-12 col-md-12 col-sm-12" style="text-align: center;">
          <div id="top_2" class="media top_ref" data="无照经营游商">
            <div class="media-left"><a href="http://portal.smartxspace.com/App/cityCase/cityCase.html#"><img
              class="media-object" src="./theme/img/2_gray.png" alt="..."></a></div>
            <div class="media-body top"><h4 class="media-heading" style="margin-bottom: 0px;"></h4>无照经营游商<a
              href="http://portal.smartxspace.com/App/cityCase/cityCase.html#" style="float:right"><span
              class="badge">23</span></a></div>
          </div>
        </div>
        <div id="thematicMap" class="row-12 col-lg-12 col-md-12 col-sm-12" style="text-align: center;">
          <div id="top_3" class="media top_ref" data="重点人口">
            <div class="media-left"><a href="http://portal.smartxspace.com/App/cityCase/cityCase.html#"><img
              class="media-object" src="./theme/img/3_gray.png" alt="..."></a></div>
            <div class="media-body top"><h4 class="media-heading" style="margin-bottom: 0px;"></h4>重点人口<a
              href="http://portal.smartxspace.com/App/cityCase/cityCase.html#" style="float:right"><span
              class="badge">10</span></a></div>
          </div>
        </div>
      </div>
    </div>
    <span id="leftClickSpan" class="glyphicon glyphicon-option-vertical opration-handler" aria-hidden="true"></span>
  </div>
</template>
<script>
  export default {
    name: 'leftbar'
  }
</script>

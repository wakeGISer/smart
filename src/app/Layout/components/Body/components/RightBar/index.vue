<template>
  <div id="RightBar" class="sideBar right animated fadeInRight">
    <span id="rightClickSpan" class="glyphicon glyphicon-option-vertical opration-handler" aria-hidden="true"></span>
    <div class="bar-content" id="rightContent">
      <div id="layerLister" style="height:100%; overflow: hidden;">
        <div id="layerListTitle">
          <div class="graph-title" style="border-left: 5px solid rgb(0, 180, 255);"><span class="graph-brand-text"
                                                                                          id="graphBrandTextHistogramMyMap">地图内容</span><span
            class="graph-brand-subtext" id="graphBrandTextHistogramTtileMyMap">Content Of Map</span></div>
        </div>
        <div id="layerList" class="mCustomScrollbar _mCS_1 mCS-autoHide"
             style="max-height: 437px; position: relative; overflow: visible; height: 437px;">
          <div id="mCSB_1" class="mCustomScrollBox mCS-light-thin mCSB_vertical mCSB_outside" tabindex="0"
               style="max-height: 437px;">
            <div id="mCSB_1_container" class="mCSB_container" style="position:relative; top:0; left:0;" dir="ltr">
              <dl class="layer-list">
                <dt>施工管理类 <input type="checkbox" checked="" class="pull-right iswitch iswitch-orange" title="打开/关闭图层"
                                 name="施工管理类"></dt>
                <dd class="picturePoint" layerid="gdyc"> 工地扬尘<span class="pull-right zoomto" title="缩放至图层"></span>
                  <div class="symbol" style="background: url(images/icons/icon_3.png) no-repeat center center;"></div>
                </dd>
                <dd class="picturePoint" layerid="sgzd"> 施工占道<span class="pull-right zoomto" title="缩放至图层"></span>
                  <div class="symbol"
                       style="background: url(images/icons/icon_10.png) no-repeat center center;"></div>
                </dd>
                <dt>社会管理类 <input type="checkbox" checked="" class="pull-right iswitch iswitch-orange" title="打开/关闭图层"
                                 name="社会管理类"></dt>
                <dd class="picturePoint" layerid="lmjs">流动人口<span class="pull-right zoomto" title="缩放至图层"></span>
                  <div class="symbol" style="background: url(images/icons/icon_1.png) no-repeat center center;"></div>
                </dd>
                <dd class="picturePoint" layerid="xsddshps">网络舆情<span class="pull-right zoomto" title="缩放至图层"></span>
                  <div class="symbol" style="background: url(images/icons/icon7.png) no-repeat center center;"></div>
                </dd>
                <dt>街面秩序类 <input type="checkbox" checked="" class="pull-right iswitch iswitch-orange" title="打开/关闭图层"
                                 name="街面秩序类"></dt>
                <dd class="picturePoint" layerid="ldwdl">乱堆物堆料<span class="pull-right zoomto" title="缩放至图层"></span>
                  <div class="symbol" style="background: url(images/icons/icon_8.png) no-repeat center center;"></div>
                </dd>
                <dd class="picturePoint" layerid="jdcltf">机动车乱停放<span class="pull-right zoomto" title="缩放至图层"></span>
                  <div class="symbol" style="background: url(images/icons/case5.png) no-repeat center center;"></div>
                </dd>
                <dt>基础设施 <input type="checkbox" checked="" class="pull-right iswitch iswitch-orange" title="打开/关闭图层"
                                name="基础设施"></dt>
                <dd class="mesh3d" layerid="buildings">建筑物<span class="pull-right zoomto" title="缩放至图层"></span>
                  <div class="symbol" style="background: url(images/building.png) no-repeat center center;"></div>
                </dd>
                <dt>基础底图 <input type="checkbox" checked="" class="pull-right iswitch iswitch-orange" title="打开/关闭图层"
                                name="基础底图"></dt>
                <dd class="tiled" layerid="basemap">梦幻蓝底图


                  <div class="symbol" style="background: url(images/buleBaseMap.png) no-repeat center center;"></div>
                </dd>
              </dl>
            </div>
          </div>
          <div id="mCSB_1_scrollbar_vertical"
               class="mCSB_scrollTools mCSB_1_scrollbar mCS-light-thin mCSB_scrollTools_vertical"
               style="display: block;">
            <div class="mCSB_draggerContainer">
              <div id="mCSB_1_dragger_vertical" class="mCSB_dragger"
                   style="position: absolute; min-height: 30px; display: block; height: 281px; max-height: 427px;"
                   oncontextmenu="return false;">
                <div class="mCSB_dragger_bar" style="line-height: 30px;"></div>
              </div>
              <div class="mCSB_draggerRail"></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
  export default {
    name: 'rightbar'
  }
</script>

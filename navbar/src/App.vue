<template>
  <div class="">
    <div>
      <div class="sidebar-container">
        <div class="sidebar-logo">
          Project Aerospace
        </div>
        <ul class="sidebar-navigation">
          <li>
            <a href="/"> <i class="fa fa-home" aria-hidden="true"></i> HOME </a>
          </li>
          <li @click="updatepath">
            <router-link to="/fleet">
              <i class="fa fa-home" aria-hidden="true"></i> FLEET
            </router-link>
          </li>
          <li @click="updatepath">
            <router-link to="/flightdata">
              <i class="fa fa-tachometer" aria-hidden="true"></i> FLIGHT DATA
            </router-link>
          </li>
            <li @click="updatepath">
            <router-link to="/myapp">
              <i class="fa fa-tachometer" aria-hidden="true"></i> ANGULAR APP
            </router-link>
          </li>
        </ul>
      </div>
      <div class="content-container" style="padding-left: 250px">
        <div class="asc-top-navbar--container">
          <header
            class="asc-top-navbar--toolbar v-sheet theme--light v-toolbar v-toolbar--dense v-app-bar"
            data-booted="true"
            style="height: 48px; margin-top: 0px; transform: translateY(0px); left: 0px; right: 0px;"
          >
            <div class="v-toolbar__content" style="height: 48px;">
              <div class="v-toolbar__title">
                <div class="asc-top-navbar--title h3">
                  <span style="padding-left: 50px">Project Micro Frontend</span
                  ><span class="asc-top-navbar--registered">®</span>
                </div>
              </div>
              <div class="spacer"></div>
              <!---->
            </div>
          </header>
        </div>
        <b-container v-if="!path_flag && path_name === '/'">
          <div style="padding-left: 38px;padding-top: 20px">
    <h5> DASHBOARD | ABOUT </h5>
    <div>This is a project about micro frontend. It has both Angular and Vue apps included as different tabs</div>
  </div>
<div style="padding-left: 28px; padding-top: 50px" class="col-sm-12 col-md-5 col-12">

                              <div class="asc-metrics-column--margin">
                                <div data-automation-id="wrapper_bar_chart" class="asc-bar-chart-wrapper--container">
                                  <div class="asc-spinner-wrapper">
                                    <div class="asc-stacked-chart--container" style="position: relative">
                                      <div data-v-7d2fa9fa="" class="asc-highchart" data-highcharts-chart="0" style="overflow: hidden">
                                        <div id="highcharts-2hpn3ks-0" dir="ltr" class="highcharts-container" style="
                                            position: relative;
                                            overflow: hidden;
                                            width: 513px;
                                            height: 272px;
                                            text-align: left;
                                            line-height: normal;
                                            z-index: 0;
                                            -webkit-tap-highlight-color: rgba(
                                              0,
                                              0,
                                              0,
                                              0
                                            );
                                            user-select: none;
                                            touch-action: manipulation;
                                            outline: none;
                                            font-family: 'Helvetica Neue',
                                              helvetica, arial, 'Lucida Grande',
                                              sans-serif;
                                          ">
                                          <svg version="1.1" class="highcharts-root" style="
                                              font-family: 'Helvetica Neue',
                                                helvetica, arial,
                                                'Lucida Grande', sans-serif;
                                              font-size: 12px;
                                            " xmlns="http://www.w3.org/2000/svg" width="513" height="272" viewBox="0 0 513 272">
                                            <desc>
                                              Created with Highcharts 9.3.2
                                            </desc>
                                            <defs>
                                              <clipPath id="highcharts-2hpn3ks-1-">
                                                <rect x="0" y="0" width="186" height="396" fill="none"></rect>
                                              </clipPath>
                                              <clipPath id="highcharts-2hpn3ks-9-">
                                                <rect x="0" y="0" width="186" height="396" fill="none"></rect>
                                              </clipPath>
                                            </defs>
                                            <rect fill="#ffffff" class="highcharts-background" x="0" y="0" width="513" height="272" rx="0" ry="0"></rect>
                                            <rect fill="none" class="highcharts-plot-background" x="93" y="48" width="396" height="186"></rect>
                                            <g class="highcharts-pane-group" data-z-index="0"></g>
                                            <rect fill="none" class="highcharts-plot-border" data-z-index="1" x="93" y="48" width="396" height="186"></rect>
                                            <g class="highcharts-grid highcharts-xaxis-grid" data-z-index="1">
                                              <path fill="none" stroke-dasharray="none" data-z-index="1" class="highcharts-grid-line" d="M 93 75.5 L 489 75.5" opacity="1"></path>
                                              <path fill="none" stroke-dasharray="none" data-z-index="1" class="highcharts-grid-line" d="M 93 101.5 L 489 101.5" opacity="1"></path>
                                              <path fill="none" stroke-dasharray="none" data-z-index="1" class="highcharts-grid-line" d="M 93 128.5 L 489 128.5" opacity="1"></path>
                                              <path fill="none" stroke-dasharray="none" data-z-index="1" class="highcharts-grid-line" d="M 93 154.5 L 489 154.5" opacity="1"></path>
                                              <path fill="none" stroke-dasharray="none" data-z-index="1" class="highcharts-grid-line" d="M 93 181.5 L 489 181.5" opacity="1"></path>
                                              <path fill="none" stroke-dasharray="none" data-z-index="1" class="highcharts-grid-line" d="M 93 207.5 L 489 207.5" opacity="1"></path>
                                              <path fill="none" stroke-dasharray="none" data-z-index="1" class="highcharts-grid-line" d="M 93 234.5 L 489 234.5" opacity="1"></path>
                                              <path fill="none" stroke-dasharray="none" data-z-index="1" class="highcharts-grid-line" d="M 93 48.5 L 489 48.5" opacity="1"></path>
                                            </g>
                                            <g class="highcharts-grid highcharts-yaxis-grid" data-z-index="1">
                                              <path fill="none" stroke="#bebebe" stroke-width="1" stroke-dasharray="4,3" data-z-index="1" class="highcharts-grid-line" d="M 92.5 48 L 92.5 234" opacity="1"></path>
                                              <path fill="none" stroke="#bebebe" stroke-width="1" stroke-dasharray="4,3" data-z-index="1" class="highcharts-grid-line" d="M 171.5 48 L 171.5 234" opacity="1"></path>
                                              <path fill="none" stroke="#bebebe" stroke-width="1" stroke-dasharray="4,3" data-z-index="1" class="highcharts-grid-line" d="M 250.5 48 L 250.5 234" opacity="1"></path>
                                              <path fill="none" stroke="#bebebe" stroke-width="1" stroke-dasharray="4,3" data-z-index="1" class="highcharts-grid-line" d="M 330.5 48 L 330.5 234" opacity="1"></path>
                                              <path fill="none" stroke="#bebebe" stroke-width="1" stroke-dasharray="4,3" data-z-index="1" class="highcharts-grid-line" d="M 409.5 48 L 409.5 234" opacity="1"></path>
                                              <path fill="none" stroke="#bebebe" stroke-width="1" stroke-dasharray="4,3" data-z-index="1" class="highcharts-grid-line" d="M 489.5 48 L 489.5 234" opacity="1"></path>
                                            </g>
                                            <g class="highcharts-axis highcharts-xaxis" data-z-index="2">
                                              <path fill="none" class="highcharts-axis-line" data-z-index="7" d="M 93 48 L 93 234"></path>
                                            </g>
                                            <g class="highcharts-axis highcharts-yaxis" data-z-index="2">
                                              <path fill="none" class="highcharts-axis-line" data-z-index="7" d="M 93 234 L 489 234"></path>
                                            </g>
                                            <g class="highcharts-series-group" data-z-index="3">
                                              <g class="highcharts-series highcharts-series-0 highcharts-bar-series highcharts-tracker" data-z-index="0.1" opacity="1" transform="translate(489,234) rotate(90) scale(-1,1) scale(1 1)" clip-path="url(#highcharts-2hpn3ks-9-)" style="cursor: default" width="396" height="186">
                                                <rect x="168.5" y="383.5" width="8" height="13" fill="rgb(81,202,195)" stroke="#ffffff" stroke-width="1" opacity="1" class="highcharts-point"></rect>
                                                <rect x="141.5" y="395.5" width="8" height="1" fill="#51cac3" stroke="#ffffff" stroke-width="1" opacity="1" class="highcharts-point"></rect>
                                                <rect x="115.5" y="389.5" width="8" height="7" fill="rgb(81,202,195)" stroke="#ffffff" stroke-width="1" opacity="1" class="highcharts-point"></rect>
                                                <rect x="88.5" y="338.5" width="8" height="58" fill="rgb(81,202,195)" stroke="#ffffff" stroke-width="1" opacity="1" class="highcharts-point"></rect>
                                                <rect x="61.5" y="65.5" width="8" height="331" fill="rgb(81,202,195)" stroke="#ffffff" stroke-width="1" opacity="1" class="highcharts-point"></rect>
                                                <rect x="35.5" y="381.5" width="8" height="15" fill="rgb(81,202,195)" stroke="#ffffff" stroke-width="1" opacity="1" class="highcharts-point"></rect>
                                                <rect x="8.5" y="386.5" width="8" height="10" fill="rgb(81,202,195)" stroke="#ffffff" stroke-width="1" opacity="1" class="highcharts-point"></rect>
                                              </g>
                                              <g class="highcharts-markers highcharts-series-0 highcharts-bar-series" data-z-index="0.1" opacity="1" transform="translate(489,234) rotate(90) scale(-1,1) scale(1 1)" clip-path="none"></g>
                                            </g>
                                            <text x="253" text-anchor="middle" class="highcharts-title" data-z-index="4" style="
                                                color: #333333;
                                                font-size: 18px;
                                                fill: #333333;
                                              " y="30"></text>
                                            <text x="16" text-anchor="start" class="highcharts-subtitle" data-z-index="4" style="
                                                color: #1f1f1f;
                                                font-size: 14px;
                                                font-family: Roboto;
                                                text-transform: uppercase;
                                                font-weight: 500;
                                                letter-spacing: 1px;
                                                line-height: 18px;
                                                fill: #1f1f1f;
                                              " y="32">
                                              Issue Count By Status
                                            </text>
                                            <text x="16" text-anchor="start" class="highcharts-caption" data-z-index="4" style="
                                                color: #666666;
                                                fill: #666666;
                                              " y="268"></text>
                                            <g class="highcharts-data-labels highcharts-series-0 highcharts-bar-series highcharts-tracker" data-z-index="6" opacity="1" transform="translate(93,48) scale(1 1)" style="cursor: default">
                                              <g class="highcharts-label highcharts-data-label highcharts-data-label-color-undefined" data-z-index="1" style="cursor: default" transform="translate(13,3)">
                                                <text x="5" data-z-index="1" y="16" style="
                                                    color: #000000;
                                                    font-size: 11px;
                                                    font-weight: bold;
                                                    fill: #000000;
                                                  ">
                                                  <tspan class="highcharts-text-outline" fill="#FFFFFF" stroke="#FFFFFF" stroke-width="2px" stroke-linejoin="round" style="">
                                                    16
                                                    <tspan x="5" y="16">
                                                      ​
                                                    </tspan>
                                                  </tspan>
                                                  16
                                                </text>
                                              </g>
                                              <g class="highcharts-label highcharts-data-label highcharts-data-label-color-undefined" data-z-index="1" style="cursor: default" transform="translate(1,30)">
                                                <text x="5" data-z-index="1" y="16" style="
                                                    color: #000000;
                                                    font-size: 11px;
                                                    font-weight: bold;
                                                    fill: #000000;
                                                  ">
                                                  <tspan class="highcharts-text-outline" fill="#FFFFFF" stroke="#FFFFFF" stroke-width="2px" stroke-linejoin="round" style="">
                                                    1
                                                    <tspan x="5" y="16">
                                                      ​
                                                    </tspan>
                                                  </tspan>
                                                  1
                                                </text>
                                              </g>
                                              <g class="highcharts-label highcharts-data-label highcharts-data-label-color-undefined" data-z-index="1" style="cursor: default" transform="translate(7,56)">
                                                <text x="5" data-z-index="1" y="16" style="
                                                    color: #000000;
                                                    font-size: 11px;
                                                    font-weight: bold;
                                                    fill: #000000;
                                                  ">
                                                  <tspan class="highcharts-text-outline" fill="#FFFFFF" stroke="#FFFFFF" stroke-width="2px" stroke-linejoin="round">
                                                    9
                                                    <tspan x="5" y="16">
                                                      ​
                                                    </tspan>
                                                  </tspan>
                                                  9
                                                </text>
                                              </g>
                                              <g class="highcharts-label highcharts-data-label highcharts-data-label-color-undefined" data-z-index="1" style="cursor: default" transform="translate(58,83)">
                                                <text x="5" data-z-index="1" y="16" style="
                                                    color: #000000;
                                                    font-size: 11px;
                                                    font-weight: bold;
                                                    fill: #000000;
                                                  ">
                                                  <tspan class="highcharts-text-outline" fill="#FFFFFF" stroke="#FFFFFF" stroke-width="2px" stroke-linejoin="round">
                                                    73
                                                    <tspan x="5" y="16">
                                                      ​
                                                    </tspan>
                                                  </tspan>
                                                  73
                                                </text>
                                              </g>
                                              <g class="highcharts-label highcharts-data-label highcharts-data-label-color-undefined" data-z-index="1" style="cursor: default" transform="translate(331,110)">
                                                <text x="5" data-z-index="1" y="16" style="
                                                    color: #000000;
                                                    font-size: 11px;
                                                    font-weight: bold;
                                                    fill: #000000;
                                                  ">
                                                  <tspan class="highcharts-text-outline" fill="#FFFFFF" stroke="#FFFFFF" stroke-width="2px" stroke-linejoin="round" style="">
                                                    418
                                                    <tspan x="5" y="16">
                                                      ​
                                                    </tspan>
                                                  </tspan>
                                                  418
                                                </text>
                                              </g>
                                              <g class="highcharts-label highcharts-data-label highcharts-data-label-color-undefined" data-z-index="1" style="cursor: default" transform="translate(15,136)">
                                                <text x="5" data-z-index="1" y="16" style="
                                                    color: #000000;
                                                    font-size: 11px;
                                                    font-weight: bold;
                                                    fill: #000000;
                                                  ">
                                                  <tspan class="highcharts-text-outline" fill="#FFFFFF" stroke="#FFFFFF" stroke-width="2px" stroke-linejoin="round">
                                                    19
                                                    <tspan x="5" y="16">
                                                      ​
                                                    </tspan>
                                                  </tspan>
                                                  19
                                                </text>
                                              </g>
                                              <g class="highcharts-label highcharts-data-label highcharts-data-label-color-undefined" data-z-index="1" style="cursor: default" transform="translate(10,163)">
                                                <text x="5" data-z-index="1" y="16" style="
                                                    color: #000000;
                                                    font-size: 11px;
                                                    font-weight: bold;
                                                    fill: #000000;
                                                  ">
                                                  <tspan class="highcharts-text-outline" fill="#FFFFFF" stroke="#FFFFFF" stroke-width="2px" stroke-linejoin="round">
                                                    12
                                                    <tspan x="5" y="16">
                                                      ​
                                                    </tspan>
                                                  </tspan>
                                                  12
                                                </text>
                                              </g>
                                            </g>
                                            <g class="highcharts-legend highcharts-no-tooltip" data-z-index="7">
                                              <rect fill="none" class="highcharts-legend-box" rx="0" ry="0" x="0" y="0" width="8" height="8" visibility="hidden"></rect>
                                              <g data-z-index="1"><g></g></g>
                                            </g>
                                            <g class="highcharts-axis-labels highcharts-xaxis-labels" data-z-index="7">
                                              <text x="78" style="
                                                  color: #000;
                                                  cursor: default;
                                                  font-size: 12px;
                                                  fill: #000;
                                                " text-anchor="end" transform="translate(0,0)" y="66" opacity="1">
                                                New
                                              </text>
                                              <text x="78" style="
                                                  color: #000;
                                                  cursor: default;
                                                  font-size: 12px;
                                                  fill: #000;
                                                " text-anchor="end" transform="translate(0,0)" y="93" opacity="1">
                                                Triage
                                              </text>
                                              <text x="78" style="
                                                  color: #000;
                                                  cursor: default;
                                                  font-size: 12px;
                                                  fill: #000;
                                                " text-anchor="end" transform="translate(0,0)" y="120" opacity="1">
                                                Disposition
                                              </text>
                                              <text x="78" style="
                                                  color: #000;
                                                  cursor: default;
                                                  font-size: 12px;
                                                  fill: #000;
                                                " text-anchor="end" transform="translate(0,0)" y="146" opacity="1">
                                                Monitor
                                              </text>
                                              <text x="78" style="
                                                  color: #000;
                                                  cursor: default;
                                                  font-size: 12px;
                                                  fill: #000;
                                                " text-anchor="end" transform="translate(0,0)" y="173" opacity="1">
                                                No Action
                                              </text>
                                              <text x="78" style="
                                                  color: #000;
                                                  cursor: default;
                                                  font-size: 12px;
                                                  fill: #000;
                                                " text-anchor="end" transform="translate(0,0)" y="199" opacity="1">
                                                In Progress
                                              </text>
                                              <text x="78" style="
                                                  color: #000;
                                                  cursor: default;
                                                  font-size: 12px;
                                                  fill: #000;
                                                " text-anchor="end" transform="translate(0,0)" y="226" opacity="1">
                                                Completed
                                              </text>
                                            </g>
                                            <g class="highcharts-axis-labels highcharts-yaxis-labels" data-z-index="7">
                                              <text x="93" style="
                                                  color: #000;
                                                  cursor: default;
                                                  font-size: 12px;
                                                  fill: #000;
                                                " text-anchor="middle" transform="translate(0,0)" y="254" opacity="1">
                                                0
                                              </text>
                                              <text x="172.2" style="
                                                  color: #000;
                                                  cursor: default;
                                                  font-size: 12px;
                                                  fill: #000;
                                                " text-anchor="middle" transform="translate(0,0)" y="254" opacity="1">
                                                100
                                              </text>
                                              <text x="251.4" style="
                                                  color: #000;
                                                  cursor: default;
                                                  font-size: 12px;
                                                  fill: #000;
                                                " text-anchor="middle" transform="translate(0,0)" y="254" opacity="1">
                                                200
                                              </text>
                                              <text x="330.6" style="
                                                  color: #000;
                                                  cursor: default;
                                                  font-size: 12px;
                                                  fill: #000;
                                                " text-anchor="middle" transform="translate(0,0)" y="254" opacity="1">
                                                300
                                              </text>
                                              <text x="409.8" style="
                                                  color: #000;
                                                  cursor: default;
                                                  font-size: 12px;
                                                  fill: #000;
                                                " text-anchor="middle" transform="translate(0,0)" y="254" opacity="1">
                                                400
                                              </text>
                                              <text x="478.98750019073486" style="
                                                  color: #000;
                                                  cursor: default;
                                                  font-size: 12px;
                                                  fill: #000;
                                                " text-anchor="middle" transform="translate(0,0)" y="254" opacity="1">
                                                500
                                              </text>
                                            </g>
                                            <g class="highcharts-label highcharts-tooltip highcharts-color-undefined" style="
                                                cursor: default;
                                                white-space: nowrap;
                                                pointer-events: none;
                                              " data-z-index="8" transform="translate(157,-9999)" opacity="0" visibility="hidden">
                                              <path fill="none" class="highcharts-label-box highcharts-tooltip-box highcharts-shadow" d="M 3 0 L 73 0 C 76 0 76 0 76 3 L 76 27 C 76 30 76 30 73 30 L 3 30 C 0 30 0 30 0 27 L 0 21 L -6 15 L 0 9 L 0 3 C 0 0 0 0 3 0" stroke="#000000" stroke-opacity="0.049999999999999996" stroke-width="5" transform="translate(1, 1)"></path>
                                              <path fill="none" class="highcharts-label-box highcharts-tooltip-box highcharts-shadow" d="M 3 0 L 73 0 C 76 0 76 0 76 3 L 76 27 C 76 30 76 30 73 30 L 3 30 C 0 30 0 30 0 27 L 0 21 L -6 15 L 0 9 L 0 3 C 0 0 0 0 3 0" stroke="#000000" stroke-opacity="0.09999999999999999" stroke-width="3" transform="translate(1, 1)"></path>
                                              <path fill="none" class="highcharts-label-box highcharts-tooltip-box highcharts-shadow" d="M 3 0 L 73 0 C 76 0 76 0 76 3 L 76 27 C 76 30 76 30 73 30 L 3 30 C 0 30 0 30 0 27 L 0 21 L -6 15 L 0 9 L 0 3 C 0 0 0 0 3 0" stroke="#000000" stroke-opacity="0.15" stroke-width="1" transform="translate(1, 1)"></path>
                                              <path fill="#000" class="highcharts-label-box highcharts-tooltip-box" d="M 3 0 L 73 0 C 76 0 76 0 76 3 L 76 27 C 76 30 76 30 73 30 L 3 30 C 0 30 0 30 0 27 L 0 21 L -6 15 L 0 9 L 0 3 C 0 0 0 0 3 0"></path>
                                              <text x="8" data-z-index="1" y="20" style="
                                                  color: #fff;
                                                  font-size: 12px;
                                                  fill: #fff;
                                                ">
                                                Monitor: 73
                                              </text>
                                            </g>
                                          </svg>
                                        </div>
                                      </div>
                                      <div class="erd_scroll_detection_container erd_scroll_detection_container_animation_active" style="
                                          visibility: hidden;
                                          display: inline;
                                          width: 0px;
                                          height: 0px;
                                          z-index: -1;
                                          overflow: hidden;
                                          margin: 0px;
                                          padding: 0px;
                                        ">
                                        <div dir="ltr" class="erd_scroll_detection_container" style="
                                            position: absolute;
                                            flex: 0 0 auto;
                                            overflow: hidden;
                                            z-index: -1;
                                            visibility: hidden;
                                            width: 100%;
                                            height: 100%;
                                            left: 0px;
                                            top: 0px;
                                          ">
                                          <div class="erd_scroll_detection_container" style="
                                              position: absolute;
                                              flex: 0 0 auto;
                                              overflow: hidden;
                                              z-index: -1;
                                              visibility: hidden;
                                              inset: -9px -8px -8px -9px;
                                            ">
                                            <div style="
                                                position: absolute;
                                                flex: 0 0 auto;
                                                overflow: scroll;
                                                z-index: -1;
                                                visibility: hidden;
                                                width: 100%;
                                                height: 100%;
                                              ">
                                              <div style="
                                                  position: absolute;
                                                  left: 0px;
                                                  top: 0px;
                                                  width: 540px;
                                                  height: 299px;
                                                "></div>
                                            </div>
                                            <div style="
                                                position: absolute;
                                                flex: 0 0 auto;
                                                overflow: scroll;
                                                z-index: -1;
                                                visibility: hidden;
                                                width: 100%;
                                                height: 100%;
                                              ">
                                              <div style="
                                                  position: absolute;
                                                  width: 200%;
                                                  height: 200%;
                                                "></div>
                                            </div>
                                          </div>
                                        </div>
                                      </div>
                                    </div>
                                    <!----><!---->
                                  </div>
                                </div>
                              </div>
                            </div>
        </b-container>
        <b-container v-else><router-view /></b-container>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      path_name: location.pathname,
      path_flag: 0,
    };
  },
  methods: {
    updatepath() {
      this.path_flag++;
    },
  },
};
</script>

<style>
/* stylelint-disable no-descending-specificity */
/* .asc-primary-navbar--container {
  top: 0;
  left: 0;
  height: 100vh;
  width: 180px;
  color: #fff;
  text-align: center;
  position: fixed;
  overflow-x: hidden;
  background-color:#333;

  .asc-primary-navbar--header {
    background-color: #1f1f1f;
    height: 48px;

    &:hover {
      cursor: pointer;
    }

    .asc-primary-navbar--gear-logo-container {
      height: 32px;
      display: flex;
      align-items: center;

      .asc-primary-navbar--logo {
        margin: 16px 0 0 10px;
        fill: #fff;
        overflow: visible;
      }
    }
  }
} */

/* .asc-primary-navbar-link--container {
  width: 180px;

  & .v-btn {
    color: #a6a6a6;
    padding: 0;
    margin: 0;
    width: 180px;
    height: 48px;
    text-align: left;
    min-width: 48px !important;
    border-bottom: 4px solid#333;
    border-radius: 0;

    &:hover {
      color: #e8e8e8;
      border-bottom: 4px solid #4f4f4f;
    }

    & .asc-primary-navbar-link--button-text {
      margin-left: 12px;
      font-size: 16px;
      text-transform: uppercase;
      padding-top: 3px;
      letter-spacing: 0;
    }

    // prettier-ignore
    & .asc-primary-navbar-link--button-text-no-padding.asc-primary-navbar-link--button-text {
      margin-left: 0;
    }

    // prettier-ignore
    & .asc-primary-navbar-link--button-child-text.asc-primary-navbar-link--button-text {
      margin-left: 24px;
    }

    & .v-btn__content {
      justify-content: flex-start;
      padding: 0 13px;
      margin: 0;

      & .v-icon--right {
        margin-left: 12px;
      }
    }
  }

  & .v-btn--router {
    &:hover {
      text-decoration: none;
    }
  }

  & a {
    text-decoration: none;
  }

  & .asc-primary-navbar-link--active {
    background-color: #848484 !important;
    color: #fff;
  }
} */

.sidebar-container {
  position: fixed;
  width: 220px;
  height: 100%;
  left: 0;
  overflow-x: hidden;
  overflow-y: auto;
  background: #1a1a1a;
  color: #fff;
}

.content-container {
  padding-top: 20px;
}

.sidebar-logo {
  padding: 10px 15px 10px 30px;
  font-size: 20px;
  background-color: #2574a9;
}

.sidebar-navigation {
  padding: 0;
  margin: 0;
  list-style-type: none;
  position: relative;
}

.sidebar-navigation li {
  background-color: transparent;
  position: relative;
  display: inline-block;
  width: 100%;
  line-height: 20px;
}

.sidebar-navigation li a {
  padding: 10px 15px 10px 30px;
  display: block;
  color: #fff;
}

.sidebar-navigation li .fa {
  margin-right: 10px;
}

.sidebar-navigation li i:active,
.sidebar-navigation li a:hover,
.sidebar-navigation li a:focus {
  text-decoration: none;
  outline: none;
}

.sidebar-navigation li::before {
  background-color: #2574a9;
  position: absolute;
  content: "";
  height: 100%;
  left: 0;
  top: 0;
  -webkit-transition: width 0.2s ease-in;
  transition: width 0.2s ease-in;
  width: 3px;
  z-index: -1;
}

.sidebar-navigation li:hover::before {
  width: 100%;
}

.sidebar-navigation .header {
  font-size: 12px;
  text-transform: uppercase;
  background-color: #151515;
  padding: 10px 15px 10px 30px;
}

.sidebar-navigation .header::before {
  background-color: transparent;
}

.content-container {
  padding-left: 220px;
}
</style>

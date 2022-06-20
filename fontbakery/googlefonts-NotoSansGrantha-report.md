## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[12] NotoSansGrantha-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2020-2021 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansGrantha/googlefonts/ttf/NotoSansGrantha-Regular.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 1755, but got 534 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/grantha.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansGrantha/googlefonts/ttf/NotoSansGrantha-Regular.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/grantha.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𑍠𑌢𑌯𑍋𑍢</span> (Added by SIESTA)</li>


<pre>Expected: rrVocalic_gran=0+1225|ddha_gran=1+1025|eeMatra_gran=2+936|ya_gran=2+1632|aaMatra_gran=2@-685,0+0|lVocalicMatra_gran=2@-20,0+0</pre>



<pre>Got     : rrVocalic_gran=0+1225|ddha_gran=1+1025|eeMatra_gran=2+906|ya_gran=2+1632|aaMatra_gran=2@-685,0+0|lVocalicMatra_gran=2@-20,0+0</pre>



<pre>                                                                 ^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4788 2824" transform="matrix(1 0 0 -1 0 0)">
<path d="M1155.0,61.0Q1155.0,1.0 1125.5,-41.5Q1096.0,-84.0 1046.5,-107.0Q997.0,-130.0 937.0,-130.0Q876.0,-130.0 828.0,-108.0Q780.0,-86.0 743.0,-57.0L774.0,3.0Q797.0,-15.0 838.0,-36.5Q879.0,-58.0 931.0,-58.0Q993.0,-58.0 1031.0,-23.5Q1069.0,11.0 1069.0,60.0Q1069.0,93.0 1051.5,121.5Q1034.0,150.0 1002.0,167.0Q970.0,184.0 926.0,184.0L908.0,184.0L908.0,256.0L916.0,256.0Q962.0,256.0 994.5,279.5Q1027.0,303.0 1044.0,339.5Q1061.0,376.0 1061.0,413.0Q1061.0,464.0 1030.5,488.5Q1000.0,513.0 957.0,513.0Q920.0,513.0 895.0,497.0Q870.0,481.0 870.0,452.0Q870.0,437.0 879.0,422.0Q888.0,407.0 912.0,407.0Q919.0,407.0 927.5,408.5Q936.0,410.0 944.0,414.0L960.0,347.0Q952.0,343.0 935.0,338.0Q918.0,333.0 895.0,333.0Q852.0,333.0 818.0,359.5Q784.0,386.0 784.0,436.0Q784.0,474.0 806.0,505.5Q828.0,537.0 868.5,556.5Q909.0,576.0 964.0,576.0Q1046.0,576.0 1096.5,533.5Q1147.0,491.0 1147.0,420.0Q1147.0,366.0 1115.5,314.0Q1084.0,262.0 1031.0,230.0Q1082.0,218.0 1118.5,173.5Q1155.0,129.0 1155.0,61.0ZM715.0,46.0Q715.0,-34.0 666.0,-83.0Q617.0,-132.0 537.0,-132.0Q496.0,-132.0 467.0,-119.5Q438.0,-107.0 419.0,-90.5Q400.0,-74.0 392.0,-61.0Q383.0,-74.0 364.5,-90.5Q346.0,-107.0 317.5,-119.5Q289.0,-132.0 249.0,-132.0Q200.0,-132.0 159.0,-111.0Q118.0,-90.0 94.0,-50.0Q70.0,-10.0 70.0,46.0Q70.0,116.0 109.5,161.5Q149.0,207.0 209.0,232.0Q153.0,258.0 123.0,296.0Q93.0,334.0 81.5,373.5Q70.0,413.0 70.0,442.0Q70.0,489.0 90.5,518.5Q111.0,548.0 143.0,562.0Q175.0,576.0 208.0,576.0Q235.0,576.0 264.0,566.5Q293.0,557.0 313.0,534.5Q333.0,512.0 333.0,473.0Q333.0,431.0 309.0,403.5Q285.0,376.0 249.0,362.0Q213.0,348.0 177.0,347.0Q200.0,315.0 250.5,290.0Q301.0,265.0 392.0,265.0Q483.0,265.0 533.5,290.0Q584.0,315.0 608.0,347.0Q571.0,348.0 535.5,362.0Q500.0,376.0 476.0,403.5Q452.0,431.0 452.0,473.0Q452.0,512.0 472.0,534.5Q492.0,557.0 521.0,566.5Q550.0,576.0 577.0,576.0Q611.0,576.0 642.5,562.0Q674.0,548.0 694.5,518.5Q715.0,489.0 715.0,442.0Q715.0,413.0 703.5,373.5Q692.0,334.0 662.0,296.0Q632.0,258.0 575.0,232.0Q635.0,207.0 675.0,161.5Q715.0,116.0 715.0,46.0ZM146.0,443.0Q146.0,435.0 147.0,423.5Q148.0,412.0 152.0,399.0Q197.0,394.0 229.0,412.5Q261.0,431.0 261.0,463.0Q261.0,489.0 242.5,500.5Q224.0,512.0 205.0,512.0Q180.0,512.0 163.0,494.5Q146.0,477.0 146.0,443.0ZM524.0,463.0Q524.0,431.0 556.0,412.5Q588.0,394.0 633.0,398.0Q636.0,412.0 637.5,423.5Q639.0,435.0 639.0,443.0Q639.0,477.0 622.0,494.5Q605.0,512.0 580.0,512.0Q561.0,512.0 542.5,500.5Q524.0,489.0 524.0,463.0ZM392.0,197.0Q354.0,197.0 313.0,191.0Q272.0,185.0 236.0,168.5Q200.0,152.0 178.0,122.0Q156.0,92.0 156.0,44.0Q156.0,2.0 173.5,-22.0Q191.0,-46.0 215.5,-55.5Q240.0,-65.0 261.0,-65.0Q296.0,-65.0 324.5,-45.0Q353.0,-25.0 360.0,6.0L424.0,6.0Q431.0,-25.0 461.0,-44.0Q491.0,-63.0 526.0,-63.0Q548.0,-63.0 571.5,-54.0Q595.0,-45.0 612.0,-21.5Q629.0,2.0 629.0,44.0Q629.0,92.0 607.5,122.0Q586.0,152.0 550.5,168.5Q515.0,185.0 473.5,191.0Q432.0,197.0 392.0,197.0Z"  transform="translate(0, 1034)"/>
<path d="M869.0,334.0Q869.0,429.0 831.0,485.0Q793.0,541.0 735.0,541.0Q768.0,525.0 787.0,498.5Q806.0,472.0 806.0,440.0Q806.0,411.0 790.0,384.5Q774.0,358.0 745.5,341.0Q717.0,324.0 679.0,324.0Q647.0,324.0 617.0,338.5Q587.0,353.0 568.5,381.0Q550.0,409.0 550.0,449.0Q550.0,498.0 577.0,532.5Q604.0,567.0 648.5,586.0Q693.0,605.0 743.0,605.0Q841.0,605.0 898.0,533.0Q955.0,461.0 955.0,336.0Q955.0,263.0 935.5,198.5Q916.0,134.0 879.5,84.5Q843.0,35.0 793.0,6.5Q743.0,-22.0 682.0,-22.0Q633.0,-22.0 597.5,-3.5Q562.0,15.0 538.0,45.0Q514.0,75.0 501.0,108.0Q470.0,54.0 411.0,16.0Q352.0,-22.0 266.0,-22.0Q184.0,-22.0 138.5,17.0Q93.0,56.0 93.0,114.0Q93.0,167.0 131.0,200.5Q169.0,234.0 231.0,268.0Q282.0,295.0 318.5,315.0Q355.0,335.0 375.0,357.5Q395.0,380.0 395.0,416.0Q395.0,460.0 366.0,491.5Q337.0,523.0 287.0,529.0Q330.0,496.0 330.0,444.0Q330.0,412.0 313.0,383.5Q296.0,355.0 266.5,337.0Q237.0,319.0 199.0,319.0Q168.0,319.0 138.5,333.5Q109.0,348.0 89.5,375.5Q70.0,403.0 70.0,442.0Q70.0,491.0 99.5,526.5Q129.0,562.0 176.0,581.5Q223.0,601.0 274.0,601.0Q331.0,601.0 378.0,578.5Q425.0,556.0 453.0,516.0Q481.0,476.0 481.0,424.0Q481.0,380.0 458.0,345.0Q435.0,310.0 392.0,279.0Q349.0,248.0 287.0,212.0Q232.0,181.0 205.5,161.0Q179.0,141.0 179.0,113.0Q179.0,82.0 209.0,66.0Q239.0,50.0 281.0,50.0Q339.0,50.0 376.0,73.5Q413.0,97.0 434.0,129.5Q455.0,162.0 464.0,189.0L545.0,189.0Q548.0,177.0 557.0,154.0Q566.0,131.0 581.5,107.5Q597.0,84.0 621.5,67.5Q646.0,51.0 682.0,51.0Q724.0,51.0 758.5,75.0Q793.0,99.0 817.5,139.5Q842.0,180.0 855.5,230.5Q869.0,281.0 869.0,334.0ZM630.0,452.0Q630.0,426.0 645.0,411.0Q660.0,396.0 683.0,396.0Q709.0,396.0 721.5,412.0Q734.0,428.0 734.0,446.0Q734.0,471.0 713.5,490.5Q693.0,510.0 663.0,517.0Q648.0,505.0 639.0,488.5Q630.0,472.0 630.0,452.0ZM146.0,447.0Q146.0,420.0 163.0,406.0Q180.0,392.0 202.0,392.0Q230.0,392.0 242.0,410.0Q254.0,428.0 254.0,446.0Q254.0,471.0 235.5,488.0Q217.0,505.0 188.0,512.0Q169.0,501.0 157.5,484.5Q146.0,468.0 146.0,447.0Z"  transform="translate(1225, 1034)"/>
<path d="M400.0,-14.0Q302.0,-14.0 227.5,37.0Q153.0,88.0 111.5,179.5Q70.0,271.0 70.0,393.0Q70.0,505.0 103.5,589.0Q137.0,673.0 195.5,729.5Q254.0,786.0 329.5,814.5Q405.0,843.0 488.0,843.0Q651.0,843.0 738.5,733.0Q826.0,623.0 826.0,425.0L826.0,-12.0L740.0,-12.0L740.0,365.0Q740.0,492.0 716.0,582.5Q692.0,673.0 637.0,722.0Q582.0,771.0 488.0,771.0Q429.0,771.0 370.5,750.5Q312.0,730.0 263.5,685.5Q215.0,641.0 185.5,569.5Q156.0,498.0 156.0,395.0Q156.0,299.0 187.0,224.5Q218.0,150.0 273.0,108.0Q262.0,137.0 262.0,171.0Q262.0,219.0 283.0,259.5Q304.0,300.0 345.0,324.5Q386.0,349.0 445.0,349.0Q494.0,349.0 534.0,329.5Q574.0,310.0 598.0,272.0Q622.0,234.0 622.0,178.0Q622.0,113.0 590.5,70.0Q559.0,27.0 508.0,6.5Q457.0,-14.0 400.0,-14.0ZM348.0,171.0Q348.0,141.0 356.0,113.0Q364.0,85.0 381.0,61.0Q402.0,58.0 423.0,58.0Q482.0,58.0 509.0,88.0Q536.0,118.0 536.0,171.0Q536.0,221.0 511.5,249.0Q487.0,277.0 443.0,277.0Q400.0,277.0 374.0,249.0Q348.0,221.0 348.0,171.0Z"  transform="translate(2250, 1034)"/>
<path d="M239.0,-11.0Q168.0,-11.0 124.0,39.0Q80.0,89.0 80.0,192.0L80.0,566.0L166.0,566.0L166.0,193.0Q166.0,132.0 190.5,96.5Q215.0,61.0 255.0,61.0Q279.0,61.0 302.0,74.0Q325.0,87.0 346.0,116.0L346.0,566.0L432.0,566.0L432.0,72.0L781.0,72.0L781.0,566.0L867.0,566.0L867.0,0.0L346.0,0.0L346.0,35.0Q331.0,20.0 304.5,4.5Q278.0,-11.0 239.0,-11.0Z"  transform="translate(3156, 1034)"/>
<path d="M80.0,0.0L80.0,566.0L615.0,566.0L615.0,494.0L445.0,494.0L445.0,0.0L359.0,0.0L359.0,494.0L166.0,494.0L166.0,0.0L80.0,0.0Z"  transform="translate(4103, 1034)"/>
<path d="M837.0,185.0L837.0,494.0L672.0,494.0L672.0,0.0L586.0,0.0L586.0,365.0Q554.0,428.0 499.5,466.0Q445.0,504.0 377.0,504.0Q319.0,504.0 273.5,477.0Q228.0,450.0 198.5,401.5Q169.0,353.0 160.0,289.0Q186.0,307.0 217.0,317.5Q248.0,328.0 281.0,328.0Q353.0,328.0 399.5,284.0Q446.0,240.0 446.0,165.0Q446.0,82.0 397.5,35.0Q349.0,-12.0 269.0,-12.0Q216.0,-12.0 170.5,13.5Q125.0,39.0 97.5,94.0Q70.0,149.0 70.0,237.0Q70.0,318.0 95.5,381.5Q121.0,445.0 165.0,488.0Q209.0,531.0 265.5,553.5Q322.0,576.0 384.0,576.0Q451.0,576.0 501.0,552.5Q551.0,529.0 586.0,493.0L586.0,566.0L1302.0,566.0L1302.0,494.0L1169.0,494.0L1169.0,185.0Q1169.0,155.0 1165.0,121.0Q1161.0,87.0 1145.5,56.5Q1130.0,26.0 1096.0,7.0Q1062.0,-12.0 1003.0,-12.0Q944.0,-12.0 910.0,7.0Q876.0,26.0 860.5,56.5Q845.0,87.0 841.0,121.0Q837.0,155.0 837.0,185.0ZM1003.0,58.0Q1037.0,58.0 1054.0,74.0Q1071.0,90.0 1077.0,116.5Q1083.0,143.0 1083.0,176.0L1083.0,494.0L923.0,494.0L923.0,176.0Q923.0,143.0 929.0,116.5Q935.0,90.0 952.0,74.0Q969.0,58.0 1003.0,58.0ZM267.0,258.0Q237.0,258.0 209.0,245.5Q181.0,233.0 157.0,212.0Q162.0,132.0 194.5,96.0Q227.0,60.0 273.0,60.0Q312.0,60.0 336.0,85.0Q360.0,110.0 360.0,155.0Q360.0,205.0 334.0,231.5Q308.0,258.0 267.0,258.0Z"  transform="translate(4768, 1034)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4818 2824" transform="matrix(1 0 0 -1 0 0)">
<path d="M1155.0,61.0Q1155.0,1.0 1125.5,-41.5Q1096.0,-84.0 1046.5,-107.0Q997.0,-130.0 937.0,-130.0Q876.0,-130.0 828.0,-108.0Q780.0,-86.0 743.0,-57.0L774.0,3.0Q797.0,-15.0 838.0,-36.5Q879.0,-58.0 931.0,-58.0Q993.0,-58.0 1031.0,-23.5Q1069.0,11.0 1069.0,60.0Q1069.0,93.0 1051.5,121.5Q1034.0,150.0 1002.0,167.0Q970.0,184.0 926.0,184.0L908.0,184.0L908.0,256.0L916.0,256.0Q962.0,256.0 994.5,279.5Q1027.0,303.0 1044.0,339.5Q1061.0,376.0 1061.0,413.0Q1061.0,464.0 1030.5,488.5Q1000.0,513.0 957.0,513.0Q920.0,513.0 895.0,497.0Q870.0,481.0 870.0,452.0Q870.0,437.0 879.0,422.0Q888.0,407.0 912.0,407.0Q919.0,407.0 927.5,408.5Q936.0,410.0 944.0,414.0L960.0,347.0Q952.0,343.0 935.0,338.0Q918.0,333.0 895.0,333.0Q852.0,333.0 818.0,359.5Q784.0,386.0 784.0,436.0Q784.0,474.0 806.0,505.5Q828.0,537.0 868.5,556.5Q909.0,576.0 964.0,576.0Q1046.0,576.0 1096.5,533.5Q1147.0,491.0 1147.0,420.0Q1147.0,366.0 1115.5,314.0Q1084.0,262.0 1031.0,230.0Q1082.0,218.0 1118.5,173.5Q1155.0,129.0 1155.0,61.0ZM715.0,46.0Q715.0,-34.0 666.0,-83.0Q617.0,-132.0 537.0,-132.0Q496.0,-132.0 467.0,-119.5Q438.0,-107.0 419.0,-90.5Q400.0,-74.0 392.0,-61.0Q383.0,-74.0 364.5,-90.5Q346.0,-107.0 317.5,-119.5Q289.0,-132.0 249.0,-132.0Q200.0,-132.0 159.0,-111.0Q118.0,-90.0 94.0,-50.0Q70.0,-10.0 70.0,46.0Q70.0,116.0 109.5,161.5Q149.0,207.0 209.0,232.0Q153.0,258.0 123.0,296.0Q93.0,334.0 81.5,373.5Q70.0,413.0 70.0,442.0Q70.0,489.0 90.5,518.5Q111.0,548.0 143.0,562.0Q175.0,576.0 208.0,576.0Q235.0,576.0 264.0,566.5Q293.0,557.0 313.0,534.5Q333.0,512.0 333.0,473.0Q333.0,431.0 309.0,403.5Q285.0,376.0 249.0,362.0Q213.0,348.0 177.0,347.0Q200.0,315.0 250.5,290.0Q301.0,265.0 392.0,265.0Q483.0,265.0 533.5,290.0Q584.0,315.0 608.0,347.0Q571.0,348.0 535.5,362.0Q500.0,376.0 476.0,403.5Q452.0,431.0 452.0,473.0Q452.0,512.0 472.0,534.5Q492.0,557.0 521.0,566.5Q550.0,576.0 577.0,576.0Q611.0,576.0 642.5,562.0Q674.0,548.0 694.5,518.5Q715.0,489.0 715.0,442.0Q715.0,413.0 703.5,373.5Q692.0,334.0 662.0,296.0Q632.0,258.0 575.0,232.0Q635.0,207.0 675.0,161.5Q715.0,116.0 715.0,46.0ZM146.0,443.0Q146.0,435.0 147.0,423.5Q148.0,412.0 152.0,399.0Q197.0,394.0 229.0,412.5Q261.0,431.0 261.0,463.0Q261.0,489.0 242.5,500.5Q224.0,512.0 205.0,512.0Q180.0,512.0 163.0,494.5Q146.0,477.0 146.0,443.0ZM524.0,463.0Q524.0,431.0 556.0,412.5Q588.0,394.0 633.0,398.0Q636.0,412.0 637.5,423.5Q639.0,435.0 639.0,443.0Q639.0,477.0 622.0,494.5Q605.0,512.0 580.0,512.0Q561.0,512.0 542.5,500.5Q524.0,489.0 524.0,463.0ZM392.0,197.0Q354.0,197.0 313.0,191.0Q272.0,185.0 236.0,168.5Q200.0,152.0 178.0,122.0Q156.0,92.0 156.0,44.0Q156.0,2.0 173.5,-22.0Q191.0,-46.0 215.5,-55.5Q240.0,-65.0 261.0,-65.0Q296.0,-65.0 324.5,-45.0Q353.0,-25.0 360.0,6.0L424.0,6.0Q431.0,-25.0 461.0,-44.0Q491.0,-63.0 526.0,-63.0Q548.0,-63.0 571.5,-54.0Q595.0,-45.0 612.0,-21.5Q629.0,2.0 629.0,44.0Q629.0,92.0 607.5,122.0Q586.0,152.0 550.5,168.5Q515.0,185.0 473.5,191.0Q432.0,197.0 392.0,197.0Z"  transform="translate(0, 1034)"/>
<path d="M869.0,334.0Q869.0,429.0 831.0,485.0Q793.0,541.0 735.0,541.0Q768.0,525.0 787.0,498.5Q806.0,472.0 806.0,440.0Q806.0,411.0 790.0,384.5Q774.0,358.0 745.5,341.0Q717.0,324.0 679.0,324.0Q647.0,324.0 617.0,338.5Q587.0,353.0 568.5,381.0Q550.0,409.0 550.0,449.0Q550.0,498.0 577.0,532.5Q604.0,567.0 648.5,586.0Q693.0,605.0 743.0,605.0Q841.0,605.0 898.0,533.0Q955.0,461.0 955.0,336.0Q955.0,263.0 935.5,198.5Q916.0,134.0 879.5,84.5Q843.0,35.0 793.0,6.5Q743.0,-22.0 682.0,-22.0Q633.0,-22.0 597.5,-3.5Q562.0,15.0 538.0,45.0Q514.0,75.0 501.0,108.0Q470.0,54.0 411.0,16.0Q352.0,-22.0 266.0,-22.0Q184.0,-22.0 138.5,17.0Q93.0,56.0 93.0,114.0Q93.0,167.0 131.0,200.5Q169.0,234.0 231.0,268.0Q282.0,295.0 318.5,315.0Q355.0,335.0 375.0,357.5Q395.0,380.0 395.0,416.0Q395.0,460.0 366.0,491.5Q337.0,523.0 287.0,529.0Q330.0,496.0 330.0,444.0Q330.0,412.0 313.0,383.5Q296.0,355.0 266.5,337.0Q237.0,319.0 199.0,319.0Q168.0,319.0 138.5,333.5Q109.0,348.0 89.5,375.5Q70.0,403.0 70.0,442.0Q70.0,491.0 99.5,526.5Q129.0,562.0 176.0,581.5Q223.0,601.0 274.0,601.0Q331.0,601.0 378.0,578.5Q425.0,556.0 453.0,516.0Q481.0,476.0 481.0,424.0Q481.0,380.0 458.0,345.0Q435.0,310.0 392.0,279.0Q349.0,248.0 287.0,212.0Q232.0,181.0 205.5,161.0Q179.0,141.0 179.0,113.0Q179.0,82.0 209.0,66.0Q239.0,50.0 281.0,50.0Q339.0,50.0 376.0,73.5Q413.0,97.0 434.0,129.5Q455.0,162.0 464.0,189.0L545.0,189.0Q548.0,177.0 557.0,154.0Q566.0,131.0 581.5,107.5Q597.0,84.0 621.5,67.5Q646.0,51.0 682.0,51.0Q724.0,51.0 758.5,75.0Q793.0,99.0 817.5,139.5Q842.0,180.0 855.5,230.5Q869.0,281.0 869.0,334.0ZM630.0,452.0Q630.0,426.0 645.0,411.0Q660.0,396.0 683.0,396.0Q709.0,396.0 721.5,412.0Q734.0,428.0 734.0,446.0Q734.0,471.0 713.5,490.5Q693.0,510.0 663.0,517.0Q648.0,505.0 639.0,488.5Q630.0,472.0 630.0,452.0ZM146.0,447.0Q146.0,420.0 163.0,406.0Q180.0,392.0 202.0,392.0Q230.0,392.0 242.0,410.0Q254.0,428.0 254.0,446.0Q254.0,471.0 235.5,488.0Q217.0,505.0 188.0,512.0Q169.0,501.0 157.5,484.5Q146.0,468.0 146.0,447.0Z"  transform="translate(1225, 1034)"/>
<path d="M400.0,-14.0Q302.0,-14.0 227.5,37.0Q153.0,88.0 111.5,179.5Q70.0,271.0 70.0,393.0Q70.0,505.0 103.5,589.0Q137.0,673.0 195.5,729.5Q254.0,786.0 329.5,814.5Q405.0,843.0 488.0,843.0Q651.0,843.0 738.5,733.0Q826.0,623.0 826.0,425.0L826.0,-12.0L740.0,-12.0L740.0,365.0Q740.0,492.0 716.0,582.5Q692.0,673.0 637.0,722.0Q582.0,771.0 488.0,771.0Q429.0,771.0 370.5,750.5Q312.0,730.0 263.5,685.5Q215.0,641.0 185.5,569.5Q156.0,498.0 156.0,395.0Q156.0,299.0 187.0,224.5Q218.0,150.0 273.0,108.0Q262.0,137.0 262.0,171.0Q262.0,219.0 283.0,259.5Q304.0,300.0 345.0,324.5Q386.0,349.0 445.0,349.0Q494.0,349.0 534.0,329.5Q574.0,310.0 598.0,272.0Q622.0,234.0 622.0,178.0Q622.0,113.0 590.5,70.0Q559.0,27.0 508.0,6.5Q457.0,-14.0 400.0,-14.0ZM348.0,171.0Q348.0,141.0 356.0,113.0Q364.0,85.0 381.0,61.0Q402.0,58.0 423.0,58.0Q482.0,58.0 509.0,88.0Q536.0,118.0 536.0,171.0Q536.0,221.0 511.5,249.0Q487.0,277.0 443.0,277.0Q400.0,277.0 374.0,249.0Q348.0,221.0 348.0,171.0Z"  transform="translate(2250, 1034)"/>
<path d="M239.0,-11.0Q168.0,-11.0 124.0,39.0Q80.0,89.0 80.0,192.0L80.0,566.0L166.0,566.0L166.0,193.0Q166.0,132.0 190.5,96.5Q215.0,61.0 255.0,61.0Q279.0,61.0 302.0,74.0Q325.0,87.0 346.0,116.0L346.0,566.0L432.0,566.0L432.0,72.0L781.0,72.0L781.0,566.0L867.0,566.0L867.0,0.0L346.0,0.0L346.0,35.0Q331.0,20.0 304.5,4.5Q278.0,-11.0 239.0,-11.0Z"  transform="translate(3186, 1034)"/>
<path d="M80.0,0.0L80.0,566.0L615.0,566.0L615.0,494.0L445.0,494.0L445.0,0.0L359.0,0.0L359.0,494.0L166.0,494.0L166.0,0.0L80.0,0.0Z"  transform="translate(4133, 1034)"/>
<path d="M837.0,185.0L837.0,494.0L672.0,494.0L672.0,0.0L586.0,0.0L586.0,365.0Q554.0,428.0 499.5,466.0Q445.0,504.0 377.0,504.0Q319.0,504.0 273.5,477.0Q228.0,450.0 198.5,401.5Q169.0,353.0 160.0,289.0Q186.0,307.0 217.0,317.5Q248.0,328.0 281.0,328.0Q353.0,328.0 399.5,284.0Q446.0,240.0 446.0,165.0Q446.0,82.0 397.5,35.0Q349.0,-12.0 269.0,-12.0Q216.0,-12.0 170.5,13.5Q125.0,39.0 97.5,94.0Q70.0,149.0 70.0,237.0Q70.0,318.0 95.5,381.5Q121.0,445.0 165.0,488.0Q209.0,531.0 265.5,553.5Q322.0,576.0 384.0,576.0Q451.0,576.0 501.0,552.5Q551.0,529.0 586.0,493.0L586.0,566.0L1302.0,566.0L1302.0,494.0L1169.0,494.0L1169.0,185.0Q1169.0,155.0 1165.0,121.0Q1161.0,87.0 1145.5,56.5Q1130.0,26.0 1096.0,7.0Q1062.0,-12.0 1003.0,-12.0Q944.0,-12.0 910.0,7.0Q876.0,26.0 860.5,56.5Q845.0,87.0 841.0,121.0Q837.0,155.0 837.0,185.0ZM1003.0,58.0Q1037.0,58.0 1054.0,74.0Q1071.0,90.0 1077.0,116.5Q1083.0,143.0 1083.0,176.0L1083.0,494.0L923.0,494.0L923.0,176.0Q923.0,143.0 929.0,116.5Q935.0,90.0 952.0,74.0Q969.0,58.0 1003.0,58.0ZM267.0,258.0Q237.0,258.0 209.0,245.5Q181.0,233.0 157.0,212.0Q162.0,132.0 194.5,96.0Q227.0,60.0 273.0,60.0Q312.0,60.0 336.0,85.0Q360.0,110.0 360.0,155.0Q360.0,205.0 334.0,231.5Q308.0,258.0 267.0,258.0Z"  transform="translate(4798, 1034)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𑌯𑍄௯𑌿</span> (Added by SIESTA)</li>


<pre>Expected: ya_gran=0+1408|rrVocalicMatra_gran=0@-417,0+0|nine_tamil=2+1155|iMatra_gran=2+0</pre>



<pre>Got     : ya_gran=0+1408|rrVocalicMatra_gran=0@-417,1+0|nine_tamil=2+1155|iMatra_gran=2+0</pre>



<pre>                                                    ^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2563 2824" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 1034)"/>
<path d=""  transform="translate(991, 1035)"/>
<path d=""  transform="translate(1408, 1034)"/>
<path d=""  transform="translate(2563, 1034)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2563 2824" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 1034)"/>
<path d=""  transform="translate(991, 1034)"/>
<path d=""  transform="translate(1408, 1034)"/>
<path d=""  transform="translate(2563, 1034)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf"> ௱𑌲𑍌𑍩</span> (Added by SIESTA)</li>


<pre>Expected: space=0+260|onehundred_tamil=1+887|la_gran=2+1145|eeMatra_gran=2+906|auLengthMark_gran=2+0|threecomb_gran=2+0</pre>



<pre>Got     : space=0+260|onehundred_tamil=1+887|la_gran=2+1145|auMatra_gran=2+2575|threecomb_gran=2+0</pre>



<pre>                                                            ^^             ++++++++++++++++++++++ ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4867 2824" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 1034)"/>
<path d=""  transform="translate(260, 1034)"/>
<path d=""  transform="translate(1147, 1034)"/>
<path d=""  transform="translate(2292, 1034)"/>
<path d=""  transform="translate(4867, 1034)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3198 2824" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 1034)"/>
<path d=""  transform="translate(260, 1034)"/>
<path d=""  transform="translate(1147, 1034)"/>
<path d=""  transform="translate(2292, 1034)"/>
<path d=""  transform="translate(3198, 1034)"/>
<path d=""  transform="translate(3198, 1034)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">௱𑌡𑌼𑍁</span> (Added by SIESTA)</li>


<pre>Expected: onehundred_tamil=0+887|dda_gran=1+983|dottedCircle=1+600|nukta_gran=1+0|uMatra_gran=1+0</pre>



<pre>Got     : onehundred_tamil=0+887|dda_gran=1+983|nukta_gran=1+0|uMatra_gran=1+0</pre>



<pre>                                                +++++++++++++++++++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1870 2824" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 1034)"/>
<path d=""  transform="translate(887, 1034)"/>
<path d=""  transform="translate(1870, 1034)"/>
<path d=""  transform="translate(1870, 1034)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2470 2824" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 1034)"/>
<path d=""  transform="translate(887, 1034)"/>
<path d=""  transform="translate(1870, 1034)"/>
<path d=""  transform="translate(2470, 1034)"/>
<path d=""  transform="translate(2470, 1034)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𑌠𑍄</span> (Added by SIESTA)</li>


<pre>Expected: ttha_gran=0+1183|rrVocalicMatra_gran=0@-417,0+0</pre>



<pre>Got     : ttha_gran=0+1183|rrVocalicMatra_gran=0@-417,1+0</pre>



<pre>                                                      ^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1183 2824" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 1034)"/>
<path d=""  transform="translate(766, 1035)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1183 2824" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 1034)"/>
<path d=""  transform="translate(766, 1034)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𑌝𑍋𑌦</span> (Added by SIESTA)</li>


<pre>Expected: eeMatra_gran=0+936|jha_gran=0+2028|aaMatra_gran=0@-685,0+0|da_gran=2+813</pre>



<pre>Got     : eeMatra_gran=0+906|jha_gran=0+2028|aaMatra_gran=0@-685,0+0|da_gran=2+813</pre>



<pre>                          ^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3747 2824" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 1034)"/>
<path d=""  transform="translate(906, 1034)"/>
<path d=""  transform="translate(2249, 1034)"/>
<path d=""  transform="translate(2934, 1034)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3777 2824" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 1034)"/>
<path d=""  transform="translate(936, 1034)"/>
<path d=""  transform="translate(2279, 1034)"/>
<path d=""  transform="translate(2964, 1034)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𑌞𑍄𑍲𑌓</span> (Added by SIESTA)</li>


<pre>Expected: nya_gran=0+1583|rrVocalicMatra_gran=0@-417,0+0|nacomb_gran=0@-733,310+0|oo_gran=3+1002</pre>



<pre>Got     : nya_gran=0+1583|rrVocalicMatra_gran=0@-417,1+0|nacomb_gran=0@-733,310+0|oo_gran=3+1002</pre>



<pre>                                                     ^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2585 2824" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 1034)"/>
<path d=""  transform="translate(1166, 1035)"/>
<path d=""  transform="translate(850, 1344)"/>
<path d=""  transform="translate(1583, 1034)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2585 2824" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 1034)"/>
<path d=""  transform="translate(1166, 1034)"/>
<path d=""  transform="translate(850, 1344)"/>
<path d=""  transform="translate(1583, 1034)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">௨𑍢᳴</span> (Added by SIESTA)</li>


<pre>Expected: two_tamil=0+1067|lVocalicMatra_gran=0+0|dottedCircle=0+600|tonecandraabove_vedic=0+0</pre>



<pre>Got     : two_tamil=0+1067|lVocalicMatra_gran=0+0|tonecandraabove_vedic=0+0</pre>



<pre>                                                  +++++++++++++++++++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1067 2824" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 1034)"/>
<path d=""  transform="translate(1067, 1034)"/>
<path d=""  transform="translate(1067, 1034)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1667 2824" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 1034)"/>
<path d=""  transform="translate(1067, 1034)"/>
<path d=""  transform="translate(1067, 1034)"/>
<path d=""  transform="translate(1667, 1034)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𑌳𑌅𑍣𑌰𑍄</span> (Added by SIESTA)</li>


<pre>Expected: lla_gran=0+1368|a_gran=1+2588|llVocalicMatra_gran=1@-1580,0+0|ra_gran=3+1218|rrVocalicMatra_gran=3@-417,0+0</pre>



<pre>Got     : lla_gran=0+1368|a_gran=1+2588|llVocalicMatra_gran=1@-1580,0+0|ra_gran=3+1218|rrVocalicMatra_gran=3@-417,1+0</pre>



<pre>                                                                                                                  ^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5174 2824" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 1034)"/>
<path d=""  transform="translate(1368, 1034)"/>
<path d=""  transform="translate(2376, 1034)"/>
<path d=""  transform="translate(3956, 1034)"/>
<path d=""  transform="translate(4757, 1035)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5174 2824" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 1034)"/>
<path d=""  transform="translate(1368, 1034)"/>
<path d=""  transform="translate(2376, 1034)"/>
<path d=""  transform="translate(3956, 1034)"/>
<path d=""  transform="translate(4757, 1034)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𑌛𑍋𑌙𑌦ᳳ</span> (Added by SIESTA)</li>


<pre>Expected: eeMatra_gran=0+936|cha_gran=0+2015|aaMatra_gran=0@-685,0+0|nga_gran=2+867|da_gran=3+813|rotatedArdhavisarga_vedic=4+635</pre>



<pre>Got     : eeMatra_gran=0+906|cha_gran=0+2015|aaMatra_gran=0@-685,0+0|nga_gran=2+867|da_gran=3+813|rotatedArdhavisarga_vedic=4+635</pre>



<pre>                          ^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5236 2824" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 1034)"/>
<path d=""  transform="translate(906, 1034)"/>
<path d=""  transform="translate(2236, 1034)"/>
<path d=""  transform="translate(2921, 1034)"/>
<path d=""  transform="translate(3788, 1034)"/>
<path d=""  transform="translate(4601, 1034)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5266 2824" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 1034)"/>
<path d=""  transform="translate(936, 1034)"/>
<path d=""  transform="translate(2266, 1034)"/>
<path d=""  transform="translate(2951, 1034)"/>
<path d=""  transform="translate(3818, 1034)"/>
<path d=""  transform="translate(4631, 1034)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">௩𑌟𑌃</span> (Added by SIESTA)</li>


<pre>Expected: three_tamil=0+985|tta_gran=1+948|dottedCircle=1+600|visarga_gran=1+400</pre>



<pre>Got     : three_tamil=0+985|tta_gran=1+948|visarga_gran=1+400</pre>



<pre>                                           +++++++++++++++++++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2333 2824" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 1034)"/>
<path d=""  transform="translate(985, 1034)"/>
<path d=""  transform="translate(1933, 1034)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2933 2824" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 1034)"/>
<path d=""  transform="translate(985, 1034)"/>
<path d=""  transform="translate(1933, 1034)"/>
<path d=""  transform="translate(2533, 1034)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss09 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss10 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+11302, U+1133E, U+1133F, U+11341, U+11342, U+11343, U+11344, U+1134D, U+11357, U+11362, U+11363 and U+1CD3 [code: non-mark-chars]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 6 | 6 | 115 | 8 | 100 | 0 |
| 0% | 3% | 3% | 49% | 3% | 43% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
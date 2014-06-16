kibana-china-map
================

添加一个中国各省份的map panels


*步骤：
>1. app/panels/map/editor.html  
   添加一个select option， 修改为 ng-options="f for f in ['world','europe','usa',**'china'**]"
>2. app/panels/map/lib目录下，放入**map.china.js**

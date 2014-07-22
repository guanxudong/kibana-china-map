kibana-china-map
================

添加一个中国各省份的map panels


步骤：
>1. app/panels/map/editor.html  
    修改ng-options="f for f in ['world','europe','usa',**'china'**]"
>2. app/panels/map/lib目录下，放入**map.china.js**
>3. kibana add map panels时，"fields"填省份拼音的字段


*注意：如果没有出现china选项，请清理浏览器缓存*

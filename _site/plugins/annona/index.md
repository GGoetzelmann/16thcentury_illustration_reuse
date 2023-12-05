<script src="{{"/plugins/js/content-state.js" | absolute_url }}"></script>
<script src="https://ncsu-libraries.github.io/annona/dist/annona.js"></script>
<link rel="stylesheet" type="text/css" href="https://ncsu-libraries.github.io/annona/dist/annona.css">

## Annona Storyboard viewer

This is a demo of the [Annona Storyboard viewer](https://ncsu-libraries.github.io/annona/) by Niqui O'Neill from NC State University Libraries. Annona allows you to navigate through your annotations and can be a useful way of sharing them with others.

Use the left and right arrow keys below to navigate through your annotations.

<div id="storyboard"></div>
        

<script type="text/javascript">
    var annotationList = getContentState();
    if(typeof(annotationList) == "string" && annotationList.length > 0) {
        var div = document.getElementById("storyboard");
        //div.innerHTML = "<iiif-storyboard url='" + annotationList + "'></iiif-storyboard>"
        //div.innerHTML = "<iiif-annotation annotationurl='" + annotationList + "' styling='table_view:true;hide_fullobject:true'></iiif-annotation>" 
    }
</script>


<div id="annotations">
</div>
<script>


fetch(getContentState())
  .then(response => response.json())
  .then(json => {
    
    console.log(btoa(JSON.stringify(json)))
    var dataString = json["items"].map(x => "base64," + btoa(JSON.stringify(x))).join(";")

    console.log(dataString)

    //makeScript();

    div.innerHTML = "<iiif-storyboard url='" + dataString + "' styling=\"matchclick: true;customid:matchclick;hide_autorunbutton:true;startposition:1;hide_annocontrols:true;hide_nextbuttons:true;hide_reloadbutton:false;toggleoverlay:true\"></iiif-storyboard>"
  });


</script>
<!--
<div id="multiboardtest"></div>
<script type="text/javascript">
    var div2 = document.getElementById("multiboardtest");
    var annolist2 = "https://ncsu-libraries.github.io/annona/webannotations/mc00084-001-te0159-000-001-0001-list.json;https://ncsu-libraries.github.io/annona/webannotations/ua023-015-003-bx0002-004-026-list.json;https://ncsu-libraries.github.io/annona/webannotations/mc00084-001-te0159-000-001-0001-list.json"
    div2.innerHTML = "<iiif-storyboard url='" + annolist2 + "'></iiif-storyboard>"
</script>
-->

<!--
<div id="multiboardtestData"></div>
<script type="text/javascript">
    var div3 = document.getElementById("multiboardtestData");
    var annolist3 = "generatedAnnoList1;generatedAnnoList2;generatedAnnoList1;generatedAnnoList2;generatedAnnoList1;generatedAnnoList2;generatedAnnoList1;generatedAnnoList2"
    div3.innerHTML = "<iiif-storyboard url='" + annolist3 + "' styling=\"matchclick: true;customid:matchclick;hide_autorunbutton:true;startposition:1;continousboard:true\"></iiif-storyboard>"
</script>
--> 

<!--
<div id="tableview"></div>
<script type="text/javascript">
    var annotationList = getContentState();
    console.log(annotationList)
    var div4 = document.getElementById("tableview");
    div4.innerHTML = "<iiif-annotation annotationurl='" + annotationList + "' styling='table_view:true;hide_fullobject:true'></iiif-annotation>"
</script>
--> 
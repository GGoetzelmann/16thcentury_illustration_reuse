<script src="{{"/plugins/js/content-state.js" | absolute_url }}"></script>
<script src="https://ncsu-libraries.github.io/annona/dist/annona.js"></script>
<link rel="stylesheet" type="text/css" href="https://ncsu-libraries.github.io/annona/dist/annona.css">

## Annona Storyboard viewer

This is a demo of the [Annona Storyboard viewer](https://ncsu-libraries.github.io/annona/) by Niqui O'Neill from NC State University Libraries. Annona allows you to navigate through your annotations and can be a useful way of sharing them with others.

Use the left and right arrow keys below to navigate through your annotations.

Smile, this is a test change
<div id="storyboard"></div>
        

<script type="text/javascript">
    var annotationList = getContentState();
    if(typeof(annotationList) == "string" && annotationList.length > 0) {
        var div = document.getElementById("storyboard");
        div.innerHTML = "<iiif-storyboard url='" + annotationList + "'></iiif-storyboard>"
    }
</script>

<div id="multiboardtest"></div>
<script type="text/javascript">
    var div = document.getElementById("multiboardtest");
    div.innerHTML = "<iiif-storyboard url="https://ncsu-libraries.github.io/annona/webannotations/mc00084-001-te0159-000-001-0001-list.json;https://ncsu-libraries.github.io/annona/webannotations/ua023-015-003-bx0002-004-026-list.json"></iiif-storyboard>"
</script>

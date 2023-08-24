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


<script type="application/json" id="generatedAnnoList2">
{
  "@type" : "sc:AnnotationList",
  "resources" : [ {
    "resource" : [ {
      "http://dev.llgc.org.uk/sas/full_text" : "",
      "@type" : "dctypes:Text",
      "format" : "text/html",
      "chars" : ""
    } ],
    "@type" : "oa:Annotation",
    "dcterms:creator" : "https://dev.gdmrdigital.com/user/1245635613/31686246",
    "motivation" : [ "oa:commenting" ],
    "dcterms:created" : "2023-08-24T09:45:55",
    "@id" : "https://dev.gdmrdigital.com/annotation/anno/1692870355727",
    "dcterms:modified" : "2023-08-24T09:45:55",
    "@context" : "file:/usr/local/tomcat/webapps/ROOT/contexts/iiif-2.0.json",
    "on" : [ 
    {
        "within" : {
          "@type" : "sc:Manifest",
          "@id" : "https://digitale.bibliothek.uni-halle.de/i3f/v20/995803/manifest"
        },
        "@type" : "oa:SpecificResource",
        "selector" : {
          "default" : {
            "@type" : "oa:FragmentSelector",
            "value" : "xywh=135,461,574,1069"
          },
          "item" : {
            "@type" : "oa:SvgSelector",
            "value" : "<svg xmlns='http://www.w3.org/2000/svg'><path xmlns=\"http://www.w3.org/2000/svg\" d=\"M135.07937,460.70635h287.18254v0h287.18254v534.58333v534.58333h-287.18254h-287.18254v-534.58333z\" data-paper-data=\"{&quot;strokeWidth&quot;:1,&quot;rotation&quot;:0,&quot;deleteIcon&quot;:null,&quot;rotationIcon&quot;:null,&quot;group&quot;:null,&quot;editable&quot;:true,&quot;annotation&quot;:null}\" id=\"rectangle_ad701e37-d2d2-4c1c-b87e-0909199e2dee\" fill-opacity=\"0\" fill=\"#00bfff\" fill-rule=\"nonzero\" stroke=\"#00bfff\" stroke-width=\"1\" stroke-linecap=\"butt\" stroke-linejoin=\"miter\" stroke-miterlimit=\"10\" stroke-dasharray=\"\" stroke-dashoffset=\"0\" font-family=\"none\" font-weight=\"none\" font-size=\"none\" text-anchor=\"none\" style=\"mix-blend-mode: normal\"/></svg>"
          },
          "@type" : "oa:Choice"
        },
        "full" : "https://digitale.bibliothek.uni-halle.de/i3f/v20/995803/canvas/1142990"
     }
  ]
  } ],
  "@id" : "https://dev.gdmrdigital.com/annotations/1245635613/31686246/38386f43a04fb2d1c9c516c83f79fb30.json",
  "@context" : "http://iiif.io/api/presentation/2/context.json"
}
</script>
<script type="application/json" id="generatedAnnoList1">
{
  "@type" : "sc:AnnotationList",
  "resources" : [ {
    "resource" : [ {
      "http://dev.llgc.org.uk/sas/full_text" : "",
      "@type" : "dctypes:Text",
      "format" : "text/html",
      "chars" : ""
    } ],
    "@type" : "oa:Annotation",
    "dcterms:creator" : "https://dev.gdmrdigital.com/user/1245635613/31686246",
    "motivation" : [ "oa:commenting" ],
    "dcterms:created" : "2023-08-24T09:45:55",
    "@id" : "https://dev.gdmrdigital.com/annotation/anno/1692870355727",
    "dcterms:modified" : "2023-08-24T09:45:55",
    "@context" : "file:/usr/local/tomcat/webapps/ROOT/contexts/iiif-2.0.json",
    "on" : [ 
    {
      "within" : {
        "@type" : "sc:Manifest",
        "@id" : "https://content.staatsbibliothek-berlin.de/dc/669844667/manifest"
      },
      "@type" : "oa:SpecificResource",
      "selector" : {
        "default" : {
          "@type" : "oa:FragmentSelector",
          "value" : "xywh=27,333,555,1069"
        },
        "item" : {
          "@type" : "oa:SvgSelector",
          "value" : "<svg xmlns='http://www.w3.org/2000/svg'><path xmlns=\"http://www.w3.org/2000/svg\" d=\"M26.55556,332.61111h277.74603v0h277.74603v534.36508v534.36508h-277.74603h-277.74603v-534.36508z\" data-paper-data=\"{&quot;strokeWidth&quot;:1,&quot;rotation&quot;:0,&quot;deleteIcon&quot;:null,&quot;rotationIcon&quot;:null,&quot;group&quot;:null,&quot;editable&quot;:true,&quot;annotation&quot;:null}\" id=\"rectangle_2d7be6da-2e54-49ec-858d-1fdeb039724b\" fill-opacity=\"0\" fill=\"#00bfff\" fill-rule=\"nonzero\" stroke=\"#00bfff\" stroke-width=\"1\" stroke-linecap=\"butt\" stroke-linejoin=\"miter\" stroke-miterlimit=\"10\" stroke-dasharray=\"\" stroke-dashoffset=\"0\" font-family=\"none\" font-weight=\"none\" font-size=\"none\" text-anchor=\"none\" style=\"mix-blend-mode: normal\"/></svg>"
        },
        "@type" : "oa:Choice"
      },
      "full" : "https://content.staatsbibliothek-berlin.de/dc/669844667-0051/canvas"
    }
  ]
  } ],
  "@id" : "https://dev.gdmrdigital.com/annotations/1245635613/31686246/38386f43a04fb2d1c9c516c83f79fb30.json",
  "@context" : "http://iiif.io/api/presentation/2/context.json"
}
</script>
<!--
<div id="multiboardtest"></div>
<script type="text/javascript">
    var div2 = document.getElementById("multiboardtest");
    var annolist2 = "https://ncsu-libraries.github.io/annona/webannotations/mc00084-001-te0159-000-001-0001-list.json;https://ncsu-libraries.github.io/annona/webannotations/ua023-015-003-bx0002-004-026-list.json;https://ncsu-libraries.github.io/annona/webannotations/mc00084-001-te0159-000-001-0001-list.json"
    div2.innerHTML = "<iiif-storyboard url='" + annolist2 + "'></iiif-storyboard>"
</script>
-->
<div id="multiboardtestData"></div>
<script type="text/javascript">
    var div3 = document.getElementById("multiboardtestData");
    var annolist3 = "generatedAnnoList1;generatedAnnoList2"
    div3.innerHTML = "<iiif-storyboard url='" + annolist3 + "' styling=\"matchclick: true;customid:matchclick;\"></iiif-storyboard>"
</script>

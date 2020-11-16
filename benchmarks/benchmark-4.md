---
sort: 4
title: 16 Diagrams
---

# 16 Diagrams

## Result

| **Name** | **Result** |
| Loading Time | <insert id='statosioLoadingTime'>waiting..</insert> |
| Dom Elements | <insert id='statosioDomElements'>waiting..</insert> |

## Diagrams

### 1. showTitle (A)

<div id="example-1">
	<script>
		d3.statosio(file,"domain",["mobile"],{"showTitle":true,"viewDomId":"example-1"})
	</script>
</div>
[More Details](../options/show__title.html#example-a) | Show title

### 2. showTitle (B)

<div id="example-2">
	<script>
		d3.statosio(file,"domain",["mobile"],{"showTitle":false,"viewDomId":"example-2"})
	</script>
</div>
[More Details](../options/show__title.html#example-b) | Hide title

### 3. showLegend (A)

<div id="example-3">
	<script>
		d3.statosio(file,"domain",["mobile","desktop"],{"showLegend":true,"viewDomId":"example-3"})
	</script>
</div>
[More Details](../options/show__legend.html#example-a) | Show legend

### 4. showLegend (B)

<div id="example-4">
	<script>
		d3.statosio(file,"domain",["mobile","desktop"],{"showLegend":false,"viewDomId":"example-4"})
	</script>
</div>
[More Details](../options/show__legend.html#example-b) | Hide legend

### 5. showAverage (A)

<div id="example-5">
	<script>
		d3.statosio(file,"domain",["mobile"],{"showAverage":true,"viewDomId":"example-5"})
	</script>
</div>
[More Details](../options/show__average.html#example-a) | Show average Line

### 6. showAverage (B)

<div id="example-6">
	<script>
		d3.statosio(file,"domain",["mobile"],{"showAverage":false,"viewDomId":"example-6"})
	</script>
</div>
[More Details](../options/show__average.html#example-b) | Hide average Line

### 7. showRangeYLog (A)

<div id="example-7">
	<script>
		d3.statosio(file,"domain",["mobile"],{"showRangeYLog":true,"viewDomId":"example-7"})
	</script>
</div>
[More Details](../options/show__range_y_log.html#example-a) | Show Y Range in Log Scale

### 8. showRangeYLog (B)

<div id="example-8">
	<script>
		d3.statosio(file,"domain",["mobile"],{"showRangeYLog":false,"viewDomId":"example-8"})
	</script>
</div>
[More Details](../options/show__range_y_log.html#example-b) | Show Y Range in Linear Scale

### 9. showDataAsCircle (A)

<div id="example-9">
	<script>
		d3.statosio(file,"domain",["mobile"],{"showDataAsCircle":true,"viewDomId":"example-9"})
	</script>
</div>
[More Details](../options/show__data_as_circle.html#example-a) | Draw data with circles

### 10. showDataAsCircle (B)

<div id="example-10">
	<script>
		d3.statosio(file,"domain",["mobile"],{"showDataAsCircle":false,"viewDomId":"example-10"})
	</script>
</div>
[More Details](../options/show__data_as_circle.html#example-b) | Draw data with bars

### 11. viewTitle (A)

<div id="example-11">
	<script>
		d3.statosio(file,"domain",["mobile"],{"viewTitle":"42","viewDomId":"example-11"})
	</script>
</div>
[More Details](../options/view__title.html#example-a) | Change title to: "```42```"

### 12. viewDomId (A)

<div id="example-12">
	<script>
		d3.statosio(file,"domain",["mobile"],{"viewDomId":"example-12"})
	</script>
</div>
[More Details](../options/view__dom_id.html#example-a) | Insert SVG into the DOM Element with the id: "```findMe```"

### 13. viewMarginTop (A)

<div id="example-13">
	<script>
		d3.statosio(file,"domain",["mobile"],{"viewMarginTop":0,"viewDomId":"example-13"})
	</script>
</div>
[More Details](../options/view__margin__top.html#example-a) | Set top margin to: ```0```

### 14. viewMarginTop (B)

<div id="example-14">
	<script>
		d3.statosio(file,"domain",["mobile"],{"viewMarginTop":150,"viewDomId":"example-14"})
	</script>
</div>
[More Details](../options/view__margin__top.html#example-b) | Set top margin to: ```150```

### 15. viewMarginRight (A)

<div id="example-15">
	<script>
		d3.statosio(file,"domain",["mobile"],{"viewMarginRight":0,"viewDomId":"example-15"})
	</script>
</div>
[More Details](../options/view__margin__right.html#example-a) | Set right margin to: ```0```

### 16. viewMarginRight (B)

<div id="example-16">
	<script>
		d3.statosio(file,"domain",["mobile"],{"viewMarginRight":200,"viewDomId":"example-16"})
	</script>
</div>
[More Details](../options/view__margin__right.html#example-b) | Set right margin to: ```200```


---
sort: 3
title: 8 Diagrams
---

# 8 Diagrams

## Result

| **Name** | **Result** |
| Loading Time | <insert id='statosioLoadingTime'>waiting..</insert> |
| Dom Elements | <insert id='statosioDomElements'>waiting..</insert> |

## Diagrams

### 1. showTitle (A)

<div id="example-1">
	<script>
		d3.statosio(file,"name",["mobile"],{"showTitle":true,"viewDomId":"example-1"})
	</script>
</div>
[More Details](../options/show__title.html#example-a) | Show title

### 2. showTitle (B)

<div id="example-2">
	<script>
		d3.statosio(file,"name",["mobile"],{"showTitle":false,"viewDomId":"example-2"})
	</script>
</div>
[More Details](../options/show__title.html#example-b) | Hide title

### 3. showLegend (A)

<div id="example-3">
	<script>
		d3.statosio(file,"name",["mobile","desktop"],{"showLegend":true,"viewDomId":"example-3"})
	</script>
</div>
[More Details](../options/show__legend.html#example-a) | Show legend

### 4. showLegend (B)

<div id="example-4">
	<script>
		d3.statosio(file,"name",["mobile","desktop"],{"showLegend":false,"viewDomId":"example-4"})
	</script>
</div>
[More Details](../options/show__legend.html#example-b) | Hide legend

### 5. showAverage (A)

<div id="example-5">
	<script>
		d3.statosio(file,"name",["mobile"],{"showAverage":true,"viewDomId":"example-5"})
	</script>
</div>
[More Details](../options/show__average.html#example-a) | Show average Line

### 6. showAverage (B)

<div id="example-6">
	<script>
		d3.statosio(file,"name",["mobile"],{"showAverage":false,"viewDomId":"example-6"})
	</script>
</div>
[More Details](../options/show__average.html#example-b) | Hide average Line

### 7. showRangeYLog (A)

<div id="example-7">
	<script>
		d3.statosio(file,"name",["mobile"],{"showRangeYLog":true,"viewDomId":"example-7"})
	</script>
</div>
[More Details](../options/show__range_y_log.html#example-a) | Show Y Range in Log Scale

### 8. showRangeYLog (B)

<div id="example-8">
	<script>
		d3.statosio(file,"name",["mobile"],{"showRangeYLog":false,"viewDomId":"example-8"})
	</script>
</div>
[More Details](../options/show__range_y_log.html#example-b) | Show Y Range in Linear Scale


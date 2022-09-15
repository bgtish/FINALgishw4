<!doctype html>
<html>
<head>
<title>Control Points</title>
<meta name="description" content="Our first page">
<meta name="keywords" content="html tutorial template">
</head>
<body>

<div id="CSVTable"></div>
<script src="//ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
<script src="//jquerycsvtotable.googlecode.com/files/jquery.csvToTable.js"></script>

<script>
$(function() {
  $('#CSVTable').CSVToTable('POINTS_unrect_unc_topo_1993.points.csv');
});
</script>


</body>
</html>
# python_gedcom_to_html
A simple python script to turn gedcom files to a compact and easy to read html document

I wanted a simple script to plot my family tree. Not beeing able to find one, I created it and uploaded it to this repository.

The code allows you to import a gedcom file and plot it easily as html. Below is an example

Hope you find it useful!

<!DOCTYPE html>
<html>
<head>
	<title>Family Tree</title>
	<meta charset="utf-8">
	<link rel="stylesheet" href="tree_style.css">
</head>
<body>
	<div class="paper_sheet">
		<div class="trea_area">
			<div class='tree_element'  style='top:0mm; left:150mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Guillermo José Morelli </span><span class='extra_content'>1980<br>-</span></div>
<div class='hor_line'  style='top:7.0mm; left:140mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:3.0mm; left:145.0mm; width:1mm; height:4.0mm; line-height:4.0mm;'></div>
<div class='hor_line'  style='top:3.0mm; left:145.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:8mm; left:150mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Gustavo Andrés Morelli </span><span class='extra_content'>1982<br>-</span></div>
<div class='hor_line'  style='top:7.0mm; left:140mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:7.0mm; left:145.0mm; width:1mm; height:4.0mm; line-height:4.0mm;'></div>
<div class='hor_line'  style='top:11.0mm; left:145.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:4.0mm; left:100mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Maria Raquel Kovacevich </span><span class='extra_content'>1958<br>-</span></div>
<div class='hor_line'  style='top:7.0mm; left:90mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:7.0mm; left:95.0mm; width:1mm; height:0.0mm; line-height:0.0mm;'></div>
<div class='hor_line'  style='top:7.0mm; left:95.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:4.0mm; left:50mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Antonio S Kovacevich </span><span class='extra_content'>1922<br>1889</span></div>
<div class='hor_line'  style='top:17.0mm; left:40mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:7.0mm; left:45.0mm; width:1mm; height:10.0mm; line-height:10.0mm;'></div>
<div class='hor_line'  style='top:7.0mm; left:45.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:16mm; left:50mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>María Angélica Kovacevich </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:17.0mm; left:40mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:17.0mm; left:45.0mm; width:1mm; height:2.0mm; line-height:2.0mm;'></div>
<div class='hor_line'  style='top:19.0mm; left:45.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:24mm; left:50mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Lucrecia Kovacevich </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:17.0mm; left:40mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:17.0mm; left:45.0mm; width:1mm; height:10.0mm; line-height:10.0mm;'></div>
<div class='hor_line'  style='top:27.0mm; left:45.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:14.0mm; left:0mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Juan Próspero Kovacevich </span><span class='extra_content'>1885<br>1962</span></div>
<div class='hor_line'  style='top:120.0mm; left:-10mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:17.0mm; left:-5.0mm; width:1mm; height:103.0mm; line-height:103.0mm;'></div>
<div class='hor_line'  style='top:17.0mm; left:-5.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:32mm; left:150mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Blas Skejich </span><span class='extra_content'>2008<br>-</span></div>
<div class='hor_line'  style='top:39.0mm; left:140mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:35.0mm; left:145.0mm; width:1mm; height:4.0mm; line-height:4.0mm;'></div>
<div class='hor_line'  style='top:35.0mm; left:145.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:40mm; left:150mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Chiara Pomba </span><span class='extra_content'>1993<br>-</span></div>
<div class='hor_line'  style='top:39.0mm; left:140mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:39.0mm; left:145.0mm; width:1mm; height:4.0mm; line-height:4.0mm;'></div>
<div class='hor_line'  style='top:43.0mm; left:145.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:36.0mm; left:100mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Andrea Kovacevich </span><span class='extra_content'>1962<br>-</span></div>
<div class='hor_line'  style='top:49.0mm; left:90mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:39.0mm; left:95.0mm; width:1mm; height:10.0mm; line-height:10.0mm;'></div>
<div class='hor_line'  style='top:39.0mm; left:95.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:48mm; left:150mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Matko Cimolai </span><span class='extra_content'>2012<br>-</span></div>
<div class='hor_line'  style='top:51.0mm; left:140mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:51.0mm; left:145.0mm; width:1mm; height:0.0mm; line-height:0.0mm;'></div>
<div class='hor_line'  style='top:51.0mm; left:145.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:48.0mm; left:100mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Mercedes Kovacevich </span><span class='extra_content'>1969<br>-</span></div>
<div class='hor_line'  style='top:49.0mm; left:90mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:49.0mm; left:95.0mm; width:1mm; height:2.0mm; line-height:2.0mm;'></div>
<div class='hor_line'  style='top:51.0mm; left:95.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:56mm; left:100mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Santiago (Tato) Kovacevich </span><span class='extra_content'>1978<br>-</span></div>
<div class='hor_line'  style='top:49.0mm; left:90mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:49.0mm; left:95.0mm; width:1mm; height:10.0mm; line-height:10.0mm;'></div>
<div class='hor_line'  style='top:59.0mm; left:95.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:46.0mm; left:50mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Santiago Kovacevich </span><span class='extra_content'>1937<br>1996</span></div>
<div class='hor_line'  style='top:49.0mm; left:40mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:49.0mm; left:45.0mm; width:1mm; height:0.0mm; line-height:0.0mm;'></div>
<div class='hor_line'  style='top:49.0mm; left:45.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:46.0mm; left:0mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Santiago Kovacevich </span><span class='extra_content'>1887<br>1962</span></div>
<div class='hor_line'  style='top:120.0mm; left:-10mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:49.0mm; left:-5.0mm; width:1mm; height:71.0mm; line-height:71.0mm;'></div>
<div class='hor_line'  style='top:49.0mm; left:-5.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:64mm; left:50mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Reparata Ronga </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:71.0mm; left:40mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:67.0mm; left:45.0mm; width:1mm; height:4.0mm; line-height:4.0mm;'></div>
<div class='hor_line'  style='top:67.0mm; left:45.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:72mm; left:50mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>María Ronga </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:71.0mm; left:40mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:71.0mm; left:45.0mm; width:1mm; height:4.0mm; line-height:4.0mm;'></div>
<div class='hor_line'  style='top:75.0mm; left:45.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:68.0mm; left:0mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Maria Kovacevich </span><span class='extra_content'>1890<br>-</span></div>
<div class='hor_line'  style='top:120.0mm; left:-10mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:71.0mm; left:-5.0mm; width:1mm; height:49.0mm; line-height:49.0mm;'></div>
<div class='hor_line'  style='top:71.0mm; left:-5.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:80mm; left:150mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Lorena Di Natale </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:87.0mm; left:140mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:83.0mm; left:145.0mm; width:1mm; height:4.0mm; line-height:4.0mm;'></div>
<div class='hor_line'  style='top:83.0mm; left:145.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:88mm; left:150mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Andrea Di Natale </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:87.0mm; left:140mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:87.0mm; left:145.0mm; width:1mm; height:4.0mm; line-height:4.0mm;'></div>
<div class='hor_line'  style='top:91.0mm; left:145.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:84.0mm; left:100mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Maria Elena Gallo </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:99.0mm; left:90mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:87.0mm; left:95.0mm; width:1mm; height:12.0mm; line-height:12.0mm;'></div>
<div class='hor_line'  style='top:87.0mm; left:95.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:96mm; left:150mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Silvina Gallo Gallo </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:111.0mm; left:140mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:99.0mm; left:145.0mm; width:1mm; height:12.0mm; line-height:12.0mm;'></div>
<div class='hor_line'  style='top:99.0mm; left:145.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:104mm; left:150mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Martín Gallo </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:111.0mm; left:140mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:107.0mm; left:145.0mm; width:1mm; height:4.0mm; line-height:4.0mm;'></div>
<div class='hor_line'  style='top:107.0mm; left:145.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:112mm; left:150mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Pablo Gallo </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:111.0mm; left:140mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:111.0mm; left:145.0mm; width:1mm; height:4.0mm; line-height:4.0mm;'></div>
<div class='hor_line'  style='top:115.0mm; left:145.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:120mm; left:150mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Carolina Gallo </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:111.0mm; left:140mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:111.0mm; left:145.0mm; width:1mm; height:12.0mm; line-height:12.0mm;'></div>
<div class='hor_line'  style='top:123.0mm; left:145.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:108.0mm; left:100mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Orlando Jose Gallo </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:99.0mm; left:90mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:99.0mm; left:95.0mm; width:1mm; height:12.0mm; line-height:12.0mm;'></div>
<div class='hor_line'  style='top:111.0mm; left:95.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:96.0mm; left:50mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Elena Dominga Boglich </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:135.0mm; left:40mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:99.0mm; left:45.0mm; width:1mm; height:36.0mm; line-height:36.0mm;'></div>
<div class='hor_line'  style='top:99.0mm; left:45.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:128mm; left:150mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Eduardo Baraldo </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:135.0mm; left:140mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:131.0mm; left:145.0mm; width:1mm; height:4.0mm; line-height:4.0mm;'></div>
<div class='hor_line'  style='top:131.0mm; left:145.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:136mm; left:150mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Silvina Baraldo </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:135.0mm; left:140mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:135.0mm; left:145.0mm; width:1mm; height:4.0mm; line-height:4.0mm;'></div>
<div class='hor_line'  style='top:139.0mm; left:145.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:132.0mm; left:100mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>María E E clement </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:143.0mm; left:90mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:135.0mm; left:95.0mm; width:1mm; height:8.0mm; line-height:8.0mm;'></div>
<div class='hor_line'  style='top:135.0mm; left:95.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:144mm; left:150mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Guillermo Puppo </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:151.0mm; left:140mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:147.0mm; left:145.0mm; width:1mm; height:4.0mm; line-height:4.0mm;'></div>
<div class='hor_line'  style='top:147.0mm; left:145.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:152mm; left:150mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Paula Puppo </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:151.0mm; left:140mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:151.0mm; left:145.0mm; width:1mm; height:4.0mm; line-height:4.0mm;'></div>
<div class='hor_line'  style='top:155.0mm; left:145.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:148.0mm; left:100mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Lucrecia Ernestina Clement </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:143.0mm; left:90mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:143.0mm; left:95.0mm; width:1mm; height:8.0mm; line-height:8.0mm;'></div>
<div class='hor_line'  style='top:151.0mm; left:95.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:140.0mm; left:50mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Lucrecia Ernestina Boglich </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:135.0mm; left:40mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:135.0mm; left:45.0mm; width:1mm; height:8.0mm; line-height:8.0mm;'></div>
<div class='hor_line'  style='top:143.0mm; left:45.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:160mm; left:100mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Marta Ángela Peracchio </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:171.0mm; left:90mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:163.0mm; left:95.0mm; width:1mm; height:8.0mm; line-height:8.0mm;'></div>
<div class='hor_line'  style='top:163.0mm; left:95.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:168mm; left:150mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Guido Peracchio </span><span class='extra_content'>1990<br>-</span></div>
<div class='hor_line'  style='top:179.0mm; left:140mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:171.0mm; left:145.0mm; width:1mm; height:8.0mm; line-height:8.0mm;'></div>
<div class='hor_line'  style='top:171.0mm; left:145.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:176mm; left:150mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Joaquín Peracchio </span><span class='extra_content'>1995<br>-</span></div>
<div class='hor_line'  style='top:179.0mm; left:140mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:179.0mm; left:145.0mm; width:1mm; height:0.0mm; line-height:0.0mm;'></div>
<div class='hor_line'  style='top:179.0mm; left:145.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:184mm; left:150mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Julio Peracchio </span><span class='extra_content'>2000<br>-</span></div>
<div class='hor_line'  style='top:179.0mm; left:140mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:179.0mm; left:145.0mm; width:1mm; height:8.0mm; line-height:8.0mm;'></div>
<div class='hor_line'  style='top:187.0mm; left:145.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:176.0mm; left:100mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Aldo J M Peracchio </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:171.0mm; left:90mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:171.0mm; left:95.0mm; width:1mm; height:8.0mm; line-height:8.0mm;'></div>
<div class='hor_line'  style='top:179.0mm; left:95.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:168.0mm; left:50mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Margarita Marta Boglich </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:135.0mm; left:40mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:135.0mm; left:45.0mm; width:1mm; height:36.0mm; line-height:36.0mm;'></div>
<div class='hor_line'  style='top:171.0mm; left:45.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:132.0mm; left:0mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Margarita Kovacevich </span><span class='extra_content'>1895<br>1980</span></div>
<div class='hor_line'  style='top:120.0mm; left:-10mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:120.0mm; left:-5.0mm; width:1mm; height:15.0mm; line-height:15.0mm;'></div>
<div class='hor_line'  style='top:135.0mm; left:-5.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:192mm; left:150mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Francesco Lorenzatti </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:203.0mm; left:140mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:195.0mm; left:145.0mm; width:1mm; height:8.0mm; line-height:8.0mm;'></div>
<div class='hor_line'  style='top:195.0mm; left:145.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:200mm; left:150mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Paula Lorenzatti </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:203.0mm; left:140mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:203.0mm; left:145.0mm; width:1mm; height:0.0mm; line-height:0.0mm;'></div>
<div class='hor_line'  style='top:203.0mm; left:145.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:208mm; left:150mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>José Ignacio Lorenzatti </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:203.0mm; left:140mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:203.0mm; left:145.0mm; width:1mm; height:8.0mm; line-height:8.0mm;'></div>
<div class='hor_line'  style='top:211.0mm; left:145.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:200.0mm; left:100mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>María Antonia Kovacevich </span><span class='extra_content'>1958<br>-</span></div>
<div class='hor_line'  style='top:211.0mm; left:90mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:203.0mm; left:95.0mm; width:1mm; height:8.0mm; line-height:8.0mm;'></div>
<div class='hor_line'  style='top:203.0mm; left:95.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:216mm; left:150mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Francisco Kovacevich </span><span class='extra_content'>1995<br>-</span></div>
<div class='hor_line'  style='top:219.0mm; left:140mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:219.0mm; left:145.0mm; width:1mm; height:0.0mm; line-height:0.0mm;'></div>
<div class='hor_line'  style='top:219.0mm; left:145.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:216.0mm; left:100mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Miguel Kovacevich </span><span class='extra_content'>1960<br>-</span></div>
<div class='hor_line'  style='top:211.0mm; left:90mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:211.0mm; left:95.0mm; width:1mm; height:8.0mm; line-height:8.0mm;'></div>
<div class='hor_line'  style='top:219.0mm; left:95.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:208.0mm; left:50mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Antolín (Tito) Kovacevich </span><span class='extra_content'>1929<br>-</span></div>
<div class='hor_line'  style='top:223.0mm; left:40mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:211.0mm; left:45.0mm; width:1mm; height:12.0mm; line-height:12.0mm;'></div>
<div class='hor_line'  style='top:211.0mm; left:45.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:224mm; left:150mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Ernani Iuso </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:227.0mm; left:140mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:227.0mm; left:145.0mm; width:1mm; height:0.0mm; line-height:0.0mm;'></div>
<div class='hor_line'  style='top:227.0mm; left:145.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:224.0mm; left:100mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Gabriela Kovacevich </span><span class='extra_content'>1964<br>-</span></div>
<div class='hor_line'  style='top:235.0mm; left:90mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:227.0mm; left:95.0mm; width:1mm; height:8.0mm; line-height:8.0mm;'></div>
<div class='hor_line'  style='top:227.0mm; left:95.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:232mm; left:150mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Martín Candia </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:235.0mm; left:140mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:235.0mm; left:145.0mm; width:1mm; height:0.0mm; line-height:0.0mm;'></div>
<div class='hor_line'  style='top:235.0mm; left:145.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:232.0mm; left:100mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Patricia Kovacevich </span><span class='extra_content'>1966<br>-</span></div>
<div class='hor_line'  style='top:235.0mm; left:90mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:235.0mm; left:95.0mm; width:1mm; height:0.0mm; line-height:0.0mm;'></div>
<div class='hor_line'  style='top:235.0mm; left:95.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:240mm; left:100mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Juan Pablo Kovacevich </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:235.0mm; left:90mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:235.0mm; left:95.0mm; width:1mm; height:8.0mm; line-height:8.0mm;'></div>
<div class='hor_line'  style='top:243.0mm; left:95.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:232.0mm; left:50mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Miguel Ángel (Quico) Kovacevich </span><span class='extra_content'>-<br>-</span></div>
<div class='hor_line'  style='top:223.0mm; left:40mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:223.0mm; left:45.0mm; width:1mm; height:12.0mm; line-height:12.0mm;'></div>
<div class='hor_line'  style='top:235.0mm; left:45.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:220.0mm; left:0mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Miguel Kovacevich </span><span class='extra_content'>1898<br>1985</span></div>
<div class='hor_line'  style='top:120.0mm; left:-10mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='ver_line'  style='top:120.0mm; left:-5.0mm; width:1mm; height:103.0mm; line-height:103.0mm;'></div>
<div class='hor_line'  style='top:223.0mm; left:-5.0mm; width:5.0mm; height:1mm; line-height:1mm;'></div>
<div class='tree_element'  style='top:117.0mm; left:-50mm; width:40mm; height:6mm; line-height:6mm;'><span class='main_content'>Ante Kovacevich </span><span class='extra_content'>1855<br>1929</span></div>

		</div>
	</div>
</body>
</html>

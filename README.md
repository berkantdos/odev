<?php
$sehirler = array ("Balıkesir","Antalya","Kütahya","Mersin","Denizli","İstanbul");

echo "<h3>For</h3";
for ($i=0; $i<count($sehirler); $i++)
{
	echo $sehirler[$i];
	echo "<br></br>";
}
echo "<h3>While</h3>";
$i=0;
while($i<count($sehirler))
{
	echo $sehirler[$i++];
	echo "<br></br>";
}
echo "<h3>Do-while</h3>";
$i=0;
do
{
	echo $sehirler[$i++];
	echo "<br></br>";
}
while($i<count($sehirler));

echo "<h3>Foreach</h3";

foreach($sehirler as $anahtar => $sehirler)
{
	echo $anahtar;
	echo " - ";
	echo $sehirler;
	echo "<br></br>";
}
?>

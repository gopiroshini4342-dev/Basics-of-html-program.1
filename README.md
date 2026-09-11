# Basics-of-html-program.1
<?php
// Student Marks Management

$marks = array(85, 72, 90, 65, 78);

$total = array_sum($marks);
$average = $total / count($marks);
$highest = max($marks);
$lowest = min($marks);

echo "<h2>Student Marks Management</h2>";

echo "Marks: ";
print_r($marks);

echo "<br><br>";
echo "Total Marks: " . $total;
echo "<br>";
echo "Average Marks: " . $average;
echo "<br>";
echo "Highest Mark: " . $highest;
echo "<br>";
echo "Lowest Mark: " . $lowest;
?>


output:
       Student Marks Management

Marks: Array ( [0] => 85 [1] => 72 [2] => 90 [3] => 65 [4] => 78 )

Total Marks: 390
Average Marks: 78
Highest Mark: 90
Lowest Mark: 65

https://codefights.com/arcade/intro/level-4/ZCD7NQnED724bJtjN
Given a rectangular matrix of characters, add a border of asterisks(*) to it.

Example

For

picture = ["abc",
           "ded"]
the output should be

addBorder(picture) = ["*****",
                      "*abc*",
                      "*ded*",
                      "*****"]
                      

function addBorder($picture) {
    $t = [];
    $max = strlen(max($picture));
    foreach($picture as $k => $p) 
        $t[++$k] = "*".$p."*"; 
    $t[0] = $t[count($picture) + 1] = str_repeat("*",$max+2);
    ksort($t);
    return $t;
}

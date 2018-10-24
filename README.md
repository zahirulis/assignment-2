# assignment-2
<?php
function printBot(){
    
    static $number;
    $number = $number??1;
    if($number >= 29){
        return;
    }

    if($number%2 !==0){
        echo $number."\n";
    }
    $number++;

    printBot();
}
printBot();/*

# AssignmentSolve2

Here the variable haystack holds the value where we need to search and needle holds value which needs to be searched.

# Applied Logic

I have split the whole haystack into an array.
<code>
$haystackArray = str_split($haystack);
</code>

Which will run in loop, within that loop I am forming a searchable string taking the needle length into consideration.

<code>
    if(isset($haystackArray[$key + $increment])){

        $searchAbleNeedle = $searchAbleNeedle . $haystackArray[$key + $increment];
    }

</code>

Newly formed String will then be checked if matches the needle, if matches algorithm will increase the occurrence by one.

<code>

    if($searchAbleNeedle == $needle){
                $occurrence ++;
    }

</code>

Thus finally getting the Output of the search;

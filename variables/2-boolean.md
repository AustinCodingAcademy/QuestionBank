Beginning Variable Exercises - Booleans
=======================================

For each of the situation given, make up 2 or more variables that you
think might relevant, and assign them some example values.  Then use
a command in your scripting language to output some sentences that use
some of the variable values.

At least one of the variables should given be a boolean value (true or false).
Then use an if to only print a certain relevant sentence if its corresponding
variable is true.


Example
-------

**Situation** What musical instruments to you like to play?

**Possible Answer in PHP**

    <?php
    $clarinet = true;
    $trombone = false;

    # sentences
    if ($clarinet) {
    ?>
        <p>I like to play the clarinet.</p>
    <?php
    }

    if ($trombone) {
    ?>
        <p>I like to jam out on the trombone.</p>
    <?php
    }
    ?>


**Possible Answer in Javascript**
(Javascript gurus please feel free to correct my scoping/style etc.)

    var clarinet = true;
    var trombone = false;

    // sentences
    if (clarinet) {
        console.log("I like to play the clarinet.");
    }

    if (trombone) {
        console.log("I like to jam out on the trombone.");
    }


Problems
--------

**1. Situation** What colors do you like and dislike?

**2. Situation** What are some things you like to do?  Don't like to do?

**3. Situation** What are some apps you like to use?  Don't like to use?

**4. Situation** What kind of computer do you use, Mac or PC?  Or something else I've never heard of?

**5. Situation** What kind of phone do you use, Android or iPhone?  Or ... Windows phone??

**6. Situation** What personality types would you say you are?


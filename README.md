speedTheme
==========

(Pseudo try of)Framework for Wordpress

Status: Pre-Alpha (Aka Don't touch this thing; Still in basic development)

Licence: MIT (for the moment)


### Guidelines


What is in what Folder:

* /dev/ = pre-compiled stylus and javascript
* /includes/ = php files non standar to wordpress
* /res/ = production static resources like CSS and JS

#### Code style:

Style identation:

    <?php

    if($whathevah==5){
        doStuff();
    }
    else{
        $whathevah = 3;

        if($whathevah == programIsUsless()){
            moreStuff();
        }
    }

    ?>

HTML/PHP independent indent from each other in mix situations

    <table>
    <?php foreach ($rows as $row): ?>
        <tr>
        <?php if ($row->foo()): ?>
            <?php echo $row ?>
        <?php else: ?>
            Something else
        <?php endif ?>
        </tr>
    <?php endforeach ?>
    </table>

**CSS and Stylus** propieties should be in alphabetical order


### Responsive Breakpoints

Resolutions suport: From 0 to 4096px (Relative to the standard 72ppi/96ppi)

* **TV**: From 4096px to 1920px
* **Desktop**: From 1920px to 1024px
* **Tablets**: From 1024px to 728px
* **Smartphones/Phanblets(?¿)**: From 728px to 320px
* **Simple Phones**: From 320px to 240px
* **Weird Devices**: From 240px to 0px


No native-speaker here, sorry for the bad english BTW.

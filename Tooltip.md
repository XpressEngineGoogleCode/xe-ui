# UI Tooltip Element #

## Details ##

The Tooltip element can be applied to most HTML tags. It is based on the [TipTip jQuery tolltip plugin](http://code.drewwilson.com/entry/tiptip-jquery-plugin).

It is activated via Javascript and presents the value of the `title` attribute in an custom tooltip.

## Examples ##
A Tooltip on an input`[`type=text`]`.

HTML:
```
<input type="text" value="" class="xe-ui-panel-text" title="I am the tooltip text."/>
```

JS:
```
<script type="text/javascript">
    jQuery( function(){
        jQuery(".xe-ui-panel-text").each( function() {
            jQuery(this).tipTip({defaultPosition: "right", activation: "focus", maxWidth:"300px", delay:"0"});
        });
    });
</script>
```
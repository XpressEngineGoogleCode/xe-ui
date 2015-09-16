# UI Panel Element #

## Details ##

A panel is a element that separates, from a logical point of view, different areas of the page.

A panel is a `<div></div>` with the `xe-ui-panel` class applied to it. It has two sections:

### Content ###

Content is placed in a `<div></div>` with the `xe-ui-panel-controller` class applied.
```
<div class="xe-ui-panel">
	<div class="xe-ui-panel-content">
		Content goes here.
	</div>
</div>
```

### Controls ###

Panel actions should be placed in the controls section of the panel. The controls section is a `<div></div>` with the `xe-ui-panel-controller` class applied.

You can add a nice `<hr />` separator that is already skinned.
```
<div class="xe-ui-panel">
        <hr />
	<div class="xe-ui-panel-content">
		Content goes here.
	</div>
	<div class="xe-ui-panel-controller">
		Controls go here.
	</div>
</div>
```

## Examples ##
A panel with content and functionality:
```
<div class="xe-ui-panel">
	<div class="xe-ui-panel-content">
		<h2>Nice title here</h2>
		<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris eu tincidunt dolor. Sed consectetur, velit id sagittis pulvinar, lorem metus consequat leo, eget hendrerit elit metus non quam. Suspendisse potenti. Pellentesque ut mauris nunc, ut volutpat metus. Curabitur nec erat ligula. Donec iaculis mattis ultricies. Donec ut facilisis ipsum. Aenean condimentum semper vestibulum. In nisl augue, pulvinar eu fermentum in, tempor at velit. Nulla adipiscing, purus vitae blandit porta, dui orci scelerisque velit, quis fringilla tortor turpis a dui.</p>
		<p>Pellentesque non lacus enim. Vivamus condimentum, nunc at hendrerit pretium, augue ligula hendrerit nisl, id tincidunt nunc mauris non enim. Nam pretium arcu vitae sapien semper malesuada. Quisque tempor diam sit amet diam aliquet condimentum. Morbi faucibus bibendum nunc gravida tempor. Proin ut leo nec eros laoreet molestie. Aliquam id tellus turpis, in ullamcorper dolor.</p>
	</div>
	<div class="xe-ui-panel-controller">
		<hr />
		<p style="text-align: center;"><a href="{getUrl('','act','dispInstallLicence')}" class="xe-ui-button-gray gradient">Let's start!</a></p>
	</div>
</div>
```
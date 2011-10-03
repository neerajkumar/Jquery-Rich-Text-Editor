# A light weight RTE jQuery Plugin

The plugin is originally created by Andrey Gayvoronsky - 

* http://www.gayvoronsky.com.
* http://code.google.com/p/rte-light

Now, you can define the height of the rte as well as css for the body of your textareas.

### Example: 

  $('textarea').live(function() {
    $('textarea.your_textarea_class').rte({
      css: ['jquery.rte.css'],
      width: 400,
      height: 100,
      controls_rte: rte_toolbar,
      iframe_body_css: 
        "padding:5px;font: 12px Tahoma, Verdana, Arial, Helvetica, sans-serif;",
	});
  });

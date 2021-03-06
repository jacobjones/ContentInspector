# EPiCode.ContentInspector

The Content Inspector is an UI addon for Episerver which helps you get a better overview and improved navigation of complex content structures. Very useful for nested blocks/content.

## Features
* A new menu item for content area, allowing you to inspect the selected content
* Preview of content
* Simple navigation to nested content.
* Works with any IContent type, including commerce items and forms.
* Displays visitor groupings
* Inspect current content using via the tools menu
* Display additional properties using the _Inspectable_ attribute




```c#

[Inspectable]
public virtual string Heading { get; set; }
```

More information at http://world.episerver.com/blogs/Per-Magne-Skuseth/Dates/2017/2/content-inspector/


![](https://raw.githubusercontent.com/BVNetwork/ContentInspector/master/doc/img/menu.png)
![](https://raw.githubusercontent.com/BVNetwork/ContentInspector/master/doc/img/inspect.png)

## Configuration

To set the base url used by rastarization for previewing, you can add the following to appSettings:

``` 
<add key="ContentInspector.RasterizeBaseUrl" value="/static/css/" />
``` 

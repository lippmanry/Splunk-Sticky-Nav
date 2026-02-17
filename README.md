## **Splunk-Sticky-Nav**

For environments that either cannot or do not want to use JS - a pure CSS sticky nav bar. This nav bar is partiall transparent and will stay in the upper left corner, extending only when hovered over. Set the row IDs to align with the links.

Example:
```
<div class="navbar">
<div class="subnav">
<button class="subnavbtn">Nav &#xA0;<i class="icon-triangle-down-small"></i></button>
<div class="subnav-content">
<a href="#row6">Row 6</a>
</div>
</div> 
</div>
<img width="603" height="144" alt="image" src="https://github.com/user-attachments/assets/f58fd0e5-c5ec-4219-a371-d2860a7af3ea" />

```
The links can be set via ```<a href="#row6">Row 6</a>``` to match the row IDs in the xml. ```<row id="row6">```

![sticky_nav-ezgif com-resize](https://github.com/user-attachments/assets/12e7439c-966a-4638-8d95-541cbe41aea0)


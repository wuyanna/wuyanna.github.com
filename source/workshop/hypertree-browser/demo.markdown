---
layout: page
title: "Demo"
comments: true
sharing: true
footer: true
---

<object data="data:application/x-silverlight-2," type="application/x-silverlight-2" width="500" height="500">
          <param name="source" value="{{ root_url }}/workshop/HyperTree.Web/ClientBin/HyperTree.xap"/>
          <param name="onError" value="onSilverlightError" />
          <param name="background" value="white" />
          <param name="minRuntimeVersion" value="4.0.50826.0" />
          <param name="autoUpgrade" value="true" />
          <a href="http://go.microsoft.com/fwlink/?LinkID=149156&v=4.0.50826.0" style="text-decoration:none">
              <img src="http://go.microsoft.com/fwlink/?LinkId=161376" alt="Get Microsoft Silverlight" style="border-style:none"/>
          </a>
        </object>

The Demo is displaying the hierarchical data of [this XBRL data]({{ root_url }}/workshop/hypertree-browser/xbrl.xml).
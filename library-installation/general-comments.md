_Library Installation_
# General comments

- Telerik recently added **[NPM Packages](http://docs.telerik.com/kendo-ui/intro/installation/npm#overview)** based installation of the Kendo UI library.

- Aurelia UI Toolkits team recommendends to use this NPM Packages distribution of the Kendo UI library because this installation method fits well in all different variants of building your Aurelia application and removes the need to differentiate between Kendo UI PRO and Kendo UI Core library in the installation process itself.

  More precisely, our new installation process is compliant with Telerik's NPM based installation, with added simplification: in all tutorial samples we always use Kendo UI Professional library, regardless of the fact that we actually just add the **[Autocomplete](http://aurelia-ui-toolkits.github.io/demo-kendo/#/samples/autocomplete-basic-use)** component.
  
- Applications not using JSPM, should install Kendo UI library via the following command

  ```
npm install --save @progress/kendo-ui
```


- For SystemJS / JSPM based application, the above command becomes:

  ```
  jspm install npm:@progress/kendo-ui

  ```

All subsequent sections of this **[installation](../installation.html)** as well as all tutorials are rewritten to accomodate the above described changes. As a consequence, each of our subseqently described "installation cases"  became a lot simpler, as explained on subsequent pages in this section.

<p align=center>
  <img src="https://user-images.githubusercontent.com/2712405/30787549-3ac04c7a-a159-11e7-97f8-945968083013.png"></img>
 <br><br>
</p>
***
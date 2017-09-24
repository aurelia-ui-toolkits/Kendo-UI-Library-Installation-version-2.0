More precisely, our new installation process is compliant with Telerik's NPM based installation, with added simplification: in all tutorial samples we always use Kendo UI Professional library, regardless of the fact that we actually just add the **[Autocomplete](http://aurelia-ui-toolkits.github.io/demo-kendo/#/samples/autocomplete-basic-use)** component.
- Tutorial samples that do not use JSPM, are simply invoking the following command

```
npm install --save @progress/kendo-ui
```
to add the Kendo UI library to the applications that uses the Kendo UI Bridge.

- For SystemJS / JSPM based application, the above command becomes:

```
jspm install npm:@progress/kendo-ui

```



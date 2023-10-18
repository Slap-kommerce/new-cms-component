# Download and Run Project
1. Download project and extract zip
2. run ```npm i```


# Component Build Specs

The creation of a new cms component will occur in two stages:<br>

1. Create a regular component that is responsive to three screen resolutions: desktop, tablet, mobile. <br>

<table><tr><td>
    <img src="images/component-desktop.png">
</td></tr></table>

2. Create a secondary view of the above component to be used by the CMS to preview live changes in the component. In addition, create a component containing the corresponding fields from which those changes occur<br>
<table><tr><td>
    <img src="images/component-cms.png">
</td></tr></table>




# Create CMS View
1. Go to ```src/page-plugins/```
2. Create a folder, using Pascal-case, using the component name, for example NewComponentName
3. Within the newly created folder, further create three tsx files:
   * ```NewComponentName.tsx```
   * ```NewComponentName_Menu.tsx```
   * ```NewComponentName_Preview.tsx```



```typescript
<div style={{ width : 700}}>
<ContainerTitled sx={{ container : { paddingLeft : 0, paddingRight : 0 }}} notitle>
```

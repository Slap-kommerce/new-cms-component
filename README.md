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

1. go to src/pages/page-editor.tsx
2. 



```typescript
<div style={{ width : 700}}>
<ContainerTitled sx={{ container : { paddingLeft : 0, paddingRight : 0 }}} notitle>
```

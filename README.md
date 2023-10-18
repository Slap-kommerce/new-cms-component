# Component Build Specs

The creation of a new cms component will occur in two stages:<br>

1. Create a regular component that is responsive to three screen resolutions: desktop, tablet, mobile. <br>

<table><tr><td>
    <img src="images/component-desktop.png">
</td></tr></table>

2. Create a secondary view of the above component. The secondary view will be used by the CMS to preview live changes in the component, and the menu component containing fields from which those changes occur <br>
<table><tr><td>
    <img src="images/component-cms.png">
</td></tr></table>

# Create CMS View



```typescript
<div style={{ width : 700}}>
<ContainerTitled sx={{ container : { paddingLeft : 0, paddingRight : 0 }}} notitle>
```

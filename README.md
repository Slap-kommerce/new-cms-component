# Download and Run Project
1. Download project and extract zip
2. run ```npm i```


# Overview of Component Build Specs
Every component we integrate into our (CMS) Content Management System must be able to be cusomized in realtime by our users. In order to accomplish this, each component must use three components: the default component, the live-preview component, and the menu component. 

#### The Default Component
The default component is what will be seen on a live website, complete with three screen resolutions: desktop, tablet, mobile.

#### The Live-preview Component
The live-preview component is the same as the default component, with two differences: 
1. It wraps the default-component within another component that scales its width and height to fit in a preview box
2. Its props are set first with the dummy-data, and then later can also be changed dynamically via: ```typescript React.useState()```

#### The Menu Component

1. Create a regular component that is responsive to 

<table><tr><td>
    <img src="images/component-desktop.png">
</td></tr></table>

2. Create a secondary view of the above component to be used by the CMS to preview live changes in the component. In addition, create a component containing the corresponding fields from which those changes occur<br>
<table><tr><td>
    <img src="images/component-cms.png">
</td></tr></table>


# Create CMS Folder Structure
1. Go to ```src/page-plugins/```
2. Create a folder, using Pascal-case, using the component name, for example NewComponentName
3. Within the newly created folder, further create three tsx files:
   * NewComponentName.tsx
   * NewComponentName_Menu.tsx
   * NewComponentName_Preview.tsx









```typescript
<div style={{ width : 700}}>
<ContainerTitled sx={{ container : { paddingLeft : 0, paddingRight : 0 }}} notitle>
```

# Job Overview
Every component we integrate into our (CMS) Content Management System must be able to be cusomized in realtime by our users. In order to accomplish this, each component is itself comprised of three components: the default component, the live-preview component, and the menu component. 

### The Default Component
The default component is what will be seen on a live website, complete with three screen resolutions: desktop, tablet, mobile.

### The Live-preview Component
The live-preview component is the same as the default component, with two differences: 
1. It wraps the default-component within another component that scales its width and height to fit in a preview box
2. Its props are set first with the dummy-data, and then later can also be changed dynamically via:
```typescript
React.useState()
```

### The Menu Component
The menu component a secondary component that contains a set of fields and/or buttons that can be used to change the props values of the live-preview component. 

#### Example Component 
This is what visitors to client pages will see
<table><tr><td>
    <img src="images/component-desktop.png">
</td></tr></table>

#### Example Live-preview and Menu Component 
This is what clients will see when they want to modify their pages
<table><tr><td>
    <img src="images/component-cms.png">
</td></tr></table>

As you can see in the image above, the values that are entered into the fields correspond to the values in the live-preview component. After a client is happy with the changes they see on their screen, they will then hit the save button (which in the live version will save thier changes to the database), If you would like to see a live preview of this, go to ```http://localhost:xxxx/page-editor```, where xxxx is the port number you're using. 

# Download and Run Project
1. Download project and extract zip
2. run ```npm i```
3. run ```npm start```
   
# Create Compatible File Structure
The first step in creating a new component that can integrate into our CMS is setting up the folder structure.

1. Go to ```src/page-plugins/```
2. Create a folder, using Pascal-case, using the component name, for example NewComponentName
3. Within the newly created folder, further create three tsx files:
   * NewComponentName.tsx
   * NewComponentName_Menu.tsx
   * NewComponentName_Preview.tsx
  
# Create Default Component
# Create Preview Component
# Create Menu Component










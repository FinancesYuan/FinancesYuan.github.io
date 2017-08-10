 Step 4: Edit your first Angular component

The CLI created the first Angular component for you. This is the root component and it is named app-root. You can find it in ./src/app/app.component.ts.

Open the component file and change the title property from Welcome to app!! to Welcome to My First Angular App!!:
src/app/app.component.ts

      

export class AppComponent {
  title = 'My First Angular App';
}

    

The browser reloads automatically with the revised title. That's nice, but it could look better.

Open src/app/app.component.css and give the component some style.
src/app/app.component.css

      

h1 {
  color: #369;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 250%;
}

    

Output of QuickStart app 

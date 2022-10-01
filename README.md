### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### `npm run electron:serve`

Runs the app in the development mode.\
Opens [http://localhost:3000](http://localhost:3000) in a windows browser application view.



The Christian's Recipe Finder Logo is a shortcut back to the home screen.

As im using a free API plan from spoonacular I have 150 quota daily. To limit the possibility of the Daily limit being reached whislt the app is in use
I have put in place features that check the local cache for data before preforming a request to save and be conservative of the quota.

This code and theese files are not all visible and accesable from the brower's developter tools information section. So for the code to be read and understood
it will have to travel alongside the Windows executable application file (which is only 1 file, so it is a very practicle of transportation).

If not using the windows executable file other methods of starting up the app are shown at the top of the page. Theese are commands run through terminal.

### `npm start`
Opens up the application in a browser form on google, chrome, Edge, etc.

### `npm run electron:serve`
Uses electron to open the app in a windows application form rather than a browser. 

Enjoy your Recipe!
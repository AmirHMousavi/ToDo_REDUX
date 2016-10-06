For just visitng the report created by [Plato](https://github.com/es-analysis/plato) go to report folder in each project and open index.html file. this report is generated from the transpiled code in `./dist/app`  folder after the build

* for angular report [click here] (https://github.com/AmirHMousavi/ToDo_REDUX/blob/master/angular2-redux-sample-app/report/index.html)
* for react report [click here] (https://github.com/AmirHMousavi/ToDo_REDUX/blob/master/react-redux-sample-app/report/index.html)

Plato supports es6 by updating eslint and using fork of escomplex

[Codelyzer](https://github.com/mgechev/codelyzer) is a static analyzer but mostly contain linting rules especific for Angular2 and does not provide any visualization of measuremnts

to Run projects cd to each project and (requires globally installed npm & gulp):

 - `npm install`
 - `gulp tsd`
 - `gulp ts-build`
 - `gulp serve`

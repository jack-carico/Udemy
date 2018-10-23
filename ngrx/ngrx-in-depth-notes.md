
## Open questions
* look into patterns for handling 


https://www.udemy.com/ngrx-course



## NgRx Store (Section 2)

### Section 2.8
context src/app/auth
scaffolding: ng generate action auth/Auth
@ngrx/store
* action enumerations
* action classes e.g. Login
* dispatching actions to the store.

### Section 2.9


### Section 2.10 store ngrx dev tools
Redux DevTools
* action log
  * store initialization
* 

### S2.11 First Reducer
begin to define AppState (the store)

### S2.12 store initial state
application startup mechanism, init action? or just a method.

### S2.13 ngrx reducer schematics
ng generate reducer Auth --flat=false --module auth/auth.module.ts

### S2.15 accessing store data and using it.
store is observable.
ngOnInit subscribe to store.
rxjs map and other operators could be used to shape the state data. 

### S2.16 ngrx selectors
memoization
selectors createSelector() @ngrx/store
select operator @ngrx/store

### S2.17 authn guard implementation.

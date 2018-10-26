
## Open questions
* look into patterns for handling 


https://www.udemy.com/ngrx-course

NgRx base documentation: https://github.com/ngrx/platform/tree/master/docs


## NgRx Store (Section 2)

Store basic patterns: https://github.com/ngrx/platform/blob/master/docs/store/README.md 

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

## S3 NgRx Effects library
store and side-effects. 

### S3.18 local storage
!! exactly what I want to know how to do. !!

monitoring Action(s) against the store. 
terms: 
* Effects service
* @ngrx/effects

snippets:
* ng generate effect auth/AuthEffect --module auth/auth.module.ts

### S3.19 


ngrx store freeze.
time-travelling debugging: ngrx router store.

ngrx-store-freeze github: bandonroberts/ngrx-store-freeze (used in dev mode only.)



## S4 NgRx Entity

first entity "Course"

Action design 

async pipe?

ngOnInit => store init actions / side-effects.
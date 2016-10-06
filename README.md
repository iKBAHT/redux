### What is it?

Fork of [redux](https://github.com/reactjs/redux)

### Changes in this fork

Reducers registred through [combineReducers](http://redux.js.org/docs/api/combineReducers.html#combinereducersreducers) function will be called with third argument - common [store](http://redux.js.org/docs/basics/Store.html#store)

### Why

* [redux/issues/749](https://github.com/reactjs/redux/issues/749)
* [redux.js.org/docs/faq](http://redux.js.org/docs/faq/Reducers.html#how-do-i-share-state-between-two-reducers-do-i-have-to-use-combinereducers)

# React Hot Module
https://github.com/gaearon/react-transform-boilerplate

# React Big Boy Template
https://github.com/kriasoft/react-starter-kit/tree/master/src/public

# Redux Asynch. actions
Also called: Effects. Can be used as base for creating statless dependencies.
* https://github.com/reactjs/redux/issues/1528
* https://github.com/yelouafi/redux-saga
* https://github.com/gaearon/redux-thunk
* http://stackoverflow.com/questions/35411423/how-to-dispatch-a-redux-action-with-a-timeout/35415559#35415559

# Redux Namespacing
Based on discussion on redux github issue page, best way is to use higher order reducerd and compose them with actions and bind
namespace id to those actions.
https://github.com/reactjs/redux/issues/786
Forms use similar solution to bind properties to a given form:
* https://github.com/erikras/redux-form
* http://stackoverflow.com/questions/36303028/react-redux-displaying-multiple-components-sharing-same-actions-but-with-diff

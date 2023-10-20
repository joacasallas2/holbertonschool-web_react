## React Redux Connectors and Providers ##

## Learning Objectives ##

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

### General ###
* Redux connectors and how to use them  
* The different functions you can pass to a connector (mapStateToProps, mapDispatchToPros)  
* How to map an action creator to a component using a connector  
* How to map an async action creator to a component with Redux Thunk  
* What Redux Providers are and how to set up your app’s store  
* How you can improve a connector’s performance using Reselect  
* How to use Redux’s dev tools to debug the state of your application  

## Tasks ##  
0. [task_0/dashboard/src/App/App.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_0/dashboard/src/App/App.js)
0. [task_0/dashboard/src/index.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_0/dashboard/src/index.js)
0. [task_0/dashboard/src/App/App.test.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_0/dashboard/src/App/App.test.js)
0. [task_1/dashboard/src/App/App.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_1/dashboard/src/App/App.js)
0. [task_1/dashboard/src/App/App.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_1/dashboard/src/App/App.js)
0. [task_1/dashboard/src/App/App.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_1/dashboard/src/App/App.js)
0. [task_1/dashboard/src/App/App.test.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_1/dashboard/src/App/App.test.js)
0. [task_2/dashboard/src/index.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_2/dashboard/src/index.js)
0. [task_2/dashboard/src/App/App.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_2/dashboard/src/App/App.js)
0. [task_2/dashboard/src/Footer/Footer.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_2/dashboard/src/Footer/Footer.js)
0. [task_2/dashboard/src/Header/Header.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_2/dashboard/src/Header/Header.js)
0. [task_2/dashboard/src/reducers/uiReducer.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_2/dashboard/src/reducers/uiReducer.js)
0. [task_2/dashboard/src/App/App.test.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_2/dashboard/src/App/App.test.js)
0. [task_2/dashboard/src/Footer/Footer.test.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_2/dashboard/src/Footer/Footer.test.js)
0. [task_2/dashboard/src/Header/Header.test.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_2/dashboard/src/Header/Header.test.js)
0. [task_2/dashboard/src/reducers/uiReducer.test.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_2/dashboard/src/reducers/uiReducer.test.js)
0. [task_3/dashboard/src/index.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_3/dashboard/src/index.js)
0. [task_4/dashboard/src/reducers/rootReducer.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_4/dashboard/src/reducers/rootReducer.js)
0. [task_4/dashboard/src/index.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_4/dashboard/src/index.js)
0. [task_4/dashboard/src/App/App.test.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_4/dashboard/src/App/App.test.js)
0. [task_4/dashboard/src/reducers/rootReducer.test.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_4/dashboard/src/reducers/rootReducer.test.js)
0. [task_5/dashboard/src/actions/notificationActionCreators.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_5/dashboard/src/actions/notificationActionCreators.js)
0. [task_5/dashboard/src/reducers/notificationReducer.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_5/dashboard/src/reducers/notificationReducer.js)
0. [task_5/dashboard/src/Notifications/Notifications.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_5/dashboard/src/Notifications/Notifications.js)
0. [task_5/dashboard/src/App/App.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_5/dashboard/src/App/App.js)
0. [task_5/dashboard/src/reducers/notificationReducer.test.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_5/dashboard/src/reducers/notificationReducer.test.js)
0. [task_5/dashboard/src/App/App.test.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_5/dashboard/src/App/App.test.js)
0. [task_5/dashboard/src/Notifications/Notifications.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_5/dashboard/src/Notifications/Notifications.js)
0. [task_5/dashboard/src/Notifications/Notifications.test.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_5/dashboard/src/Notifications/Notifications.test.js)
0. [task_5/dashboard/src/actions/notificationActionCreators.test.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_5/dashboard/src/actions/notificationActionCreators.test.js)
0. [task_6/dashboard/src/Notifications/Notifications.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_6/dashboard/src/Notifications/Notifications.js)
0. [task_6/dashboard/src/Notifications/Notifications.test.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_6/dashboard/src/Notifications/Notifications.test.js)
0. [task_7/dashboard/src/selectors/courseSelector.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_7/dashboard/src/selectors/courseSelector.js)
0. [task_7/dashboard/src/selectors/courseSelector.test.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_7/dashboard/src/selectors/courseSelector.test.js)
0. [task_7/dashboard/src/actions/courseActionCreators.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_7/dashboard/src/actions/courseActionCreators.js)
0. [task_7/dashboard/src/actions/courseActionCreators.test.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_7/dashboard/src/actions/courseActionCreators.test.js)
0. [task_7/dashboard/src/CourseList/CourseList.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_7/dashboard/src/CourseList/CourseList.js)
0. [task_7/dashboard/src/CourseList/CourseList.test.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_7/dashboard/src/CourseList/CourseList.test.js)
0. [task_8/dashboard/src/selectors/notificationSelector.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_8/dashboard/src/selectors/notificationSelector.js)
0. [task_8/dashboard/src/Notifications/Notifications.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_8/dashboard/src/Notifications/Notifications.js)
0. [task_8/dashboard/src/Notifications/Notifications.test.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_8/dashboard/src/Notifications/Notifications.test.js)
0. [task_9/dashboard/src/Notifications/Notifications.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_9/dashboard/src/Notifications/Notifications.js)
0. [task_9/dashboard/src/Notifications/Notifications.test.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_9/dashboard/src/Notifications/Notifications.test.js)
0. [task_9/dashboard/src/Notifications/NotificationsContainer.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_9/dashboard/src/Notifications/NotificationsContainer.js)
0. [task_9/dashboard/src/Notifications/NotificationsContainer.test.js](https://github.com/joacasallas2/holbertonschool-web_react/blob/main/react_redux_connectors_and_providers/task_9/dashboard/src/Notifications/NotificationsContainer.test.js)  


## Autor:  joacasallas :information_desk_person:  
contact:  joacasallas@gmail.com  



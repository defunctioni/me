# Stateless vs Stateful

## Stateless Example IRL: 
Stateless transactions are like vending machines: a single request and a response.

## Stateless Example Application:
Doing a search online. You type your query into a search engine and press enter. If your transcation is interrupted, you just start a new one.

## More Stateless:
The state of an application is its condition of being at a given moment in time.
Whether something is stateful or stateless depends on how long the state of interaction with it is being recorded and how that info needs to be stored. 

* A stateless process or application can be understood in isolation. There is no stored knowledge or reference to past transactions. 
Each transaction is made as if it were the first time. Stateless applications provide one service/function and use CDN, web, or print servers to process these short-term requests. 

## Stateful Example IRL: 
Having an ongoing periodic conversation with the same person. 

## Stateful Example Application: 
Online banking, email. Stateful apps track things like window location, setting preferences, and recent activity. 

* Stateful applications/processes are those that can be returned to again and again. They're performed with the context of previous transactions and the current transaction may be affected by what happened during previously transactions. 
The majority of applications we use day to day are stateful, but as tech advances, microservices and containers make it easier to build and deploy apps in the cloud.

https://www.redhat.com/en/topics/cloud-native-apps/stateful-vs-stateless

#cloud-native#definitions

# associated Firebase data with Users

associated Firebase data with Users [How to Connect Firebase Users to their Data - 3 Methods](https://youtu.be/2ciHixbc4HE)

* Keep data shallow in NoSQL vs SQL
* use auth state to get current user id. And then can do queries based on that auth state, for items nested under that user id.
* firebase security rules on firestorm

Other option

* adding user id on the item 

Multiple users



### ADR around reasoning to design of schema and security

{% embed url="https://github.com/bbc/digital-paper-edit-firebase/blob/master/docs/ADR/2019-12-02-nosql-schema-security.md" caption="ADR around the NoSQL Schema" %}

### Example of implementation

{% embed url="https://github.com/bbc/digital-paper-edit-firebase/blob/master/firestore.rules" caption="Security Rules" %}




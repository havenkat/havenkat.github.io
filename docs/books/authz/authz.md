## Authorization

Managing centralized access control decisions across different systems and applications. 

- Benefits for Security:
Centralized Policy Authoring and managing: Hybrid authorization allows defining and enforcing access control policies from a central location. 

- Fine Grained Access Control: 
Granular control over user permissions becomes possible. One can define access based on user roles, attributes, and specific resource types, enhancing security and minimizing data exposure.

##### Policy
Policy is a schema which holds the relationship of 

    - who .
    - On what .
    - How .

```
{
    Policy = (Subject,Resource(s),Role(s)
}

Subject = (User,functionalId, Groups)

Resource(s) = Attributes Of Business Entiry

Role(s) = Collection Permissions, which is allowed on each Resource.

Permission(s) = Service.resource.action ex:- Order.PendingOrders.view

```

----
[Home](../README.md)
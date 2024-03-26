# Policy Decision Point

- A Policy Decision Point (PDP) is a crucial component in an attribute-based access control (ABAC) system. It’s responsible for making decisions about access requests based on predefined policies. 

- Receiving aIsAuthorised()  Request: The PDP receives an access verification request from the Policy Enforcement Point (PEP).

- Evaluating the Request: It evaluates the request against the authorization policies that apply to the resource being accessed explained as Attribute.

- Making a Decision: Based on this evaluation, the PDP decides whether to permit or deny the request.

- Sending the Decision: The decision is then communicated back to the PEP, which enforces it.

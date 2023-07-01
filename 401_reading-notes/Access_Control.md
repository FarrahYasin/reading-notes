# Reading: Access Control (ACL)

**Access Control (ACL)** 💻📕

  ***why this topic matters as it relates to what you are studying in this module?***
 to ensuring the security and protection of systems and resources,it is important for managing and controlling who has access to sensitive information, files, or applications within an organization. 
 
---

#### 5 steps to RBAC

**1.** **What is Role Based Access Control (RBAC) and why do we care?**
**(RBAC)Role Based Access Control:** is a security model this model provides a structured method for managing access to resources within an application

**2.** **Describe a Role/Permission heirarchy that you might implement using RBAC**
**Admin, Manager, Employee, Guest**

1. Admin role: Admin has full control over the system.

2. Manager role: Manager typically has permissions to manage specific departments within the system,it can view and modify data that related to their respective areas.

3. Employee role: Employee has limited access ,the employee can view and update relevant data within their assigned department but he does not have administrative privileges.

4. Guest role: Guest has minimal acces, It may only have read-only access to certain public information within the system.

**3.** **What approach might you take to implement RBAC?**
1. determine each role in the system by analyze the system structure, and access requirements to determine the different roles that exist within the system.
2. determine permissions by determine the specific operations that can be performed within the system, also determine  permissions to roles based on functional requirements.
3. assign the roles: Assign users to the relevant roles based on their job requirements and their job responsibilities also.

---


#### wiki - RBAC

**1.** **If Authentication is “you are who you say you are,” what is Authorization?**
Authorization is "what you are allowed to do?"

**2.** **Name three primary rules defined for RBAC.**
**1. Users can perform** actions only if they have been assigned or selected a role that includes the necessary permissions for those actions. Users don't have direct permissions; they acquire them through their assigned roles.

**2. Role authorization:** Users' active roles must be authorized for them. This rule ensures that users can only take on roles for which they are authorized, preventing unauthorized access.

**3. Permission authorization:** Users can exercise permissions only if those permissions are authorized for their active roles. This rule ensures that users can only perform actions for which they have explicit authorization.

**3.** **Describe RBAC to a non-technical friend.**
RBAC is controls access to resources based on predefined roles and permissions. In RBAC, users are assigned roles, these permissions determine what actions they can take within the system. By organizing users into roles, RBAC ensures that each person has the appropriate level of access for their tasks while keeping sensitive information secure. It simplifies access management by grouping permissions into roles, making it easier to control and monitor who can do what in the system.

---

#### RBAC tutorial

**1.** **What Are access rights Associated with? The User? or The Role? Explain.**
Access rights in a Role-Based Access Control (RBAC) system are associated with the role, not the individual user. In RBAC, roles are created based on job functions or responsibilities within the system. Each role is assigned a set of permissions that define what actions or what operations can be performed in the system. Users are then assigned one or more than one roles, and their access rights are determined by the permissions associated with those roles. This approach allows for easier management of access control.

**2.** **Access Rights, or Authorization, is activated after a user successfully does what?**
Access rights(authorization) are activated after a user successfully authenticates themselves.



**3.** **Explain how RBAC might benefit a business.**

1. Improved Security, RBAC grants access rights based on job roles in the system,This helps protect sensitive information from the risks of unauthorized access.
2. Enhances productivity: RBAC helps improve efficiency and reduce problems caused by unauthorized actions and operations, it streamline workflows efficient.


---

## Things I want to know more about:

I want to learn more information about Access Control(ACL).
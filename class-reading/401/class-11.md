### Why is access control important?\

Access controls are important because it limits the user interactability. THis is important for many factors, most importantly the protections of sensative user data. We dont want access to everyones secure data being accessed by every user in our application, especially as out applications scales. Take a banking application for example. You wouldnt want every user to have access to your banking profile, access to transfers and withdrawls.. We need to set user access controls to protect user safety and data security.

### Describe an application that would need access control.

Bank of America Mobile app. -> Limits user access tot heir specific account and profile. and then limits further if this account is < 18 or is co-signed and has user access control limits.

### What is a role used for?

A role sets capabilities for a user and defignes what each role in the applications can access. A role dictates the Authorizations limits and in turn sets up an internal check for which to run your access control checks.

### Why is role based access control more scalable than discretionary or mandatory access control?

Roles are more scalable because the access controls are pre-determined by each role and therefore the creationg of a new account is easily assigned a pre-determined role. There user role is locked to a single user assignment and the permissions cannot be altered, however for scalable enterprise level applciations this isnt necessarily that bif og an issue. this would be more of an issue for Top Secret applications that require STRICT user permissions ie. government in which case they would opt for Mandatory Access controls which is controlled soley by the system administrator who then passes access accordinlgy down in a hierarchy. This wouldnt be scalably to a million or multi-million user company who releases updates and patches regularly.

## Authorization: User Access COntrols which set user capabilities within an application.

## Roles has pre-determined assigned capabilities which allow differing level of access.

## Capabilities are the actions a user can take within an application based on their role/hierarchy Role.

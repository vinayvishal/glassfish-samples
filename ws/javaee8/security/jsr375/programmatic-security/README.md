The Java EE platform defines a declarative security model for protecting application resources. The
declared constraints on access are then enforced by the container. In some cases the declarative model
is not sufficient; for example, when a combination of tests and constraints is needed that is more
complex than the declarative model allows for. Programmatic security allows an application to
perform tests and grant or deny access to resources.
This specification provides an access point for programmatic security — a security
context — represented by the SecurityContext interface.
In this version of the specification, the SecurityContext MUST be available in the Servlet container and
the EJB container. Appl

---

Enterprises having secure resources need to restrict access to these resources to users with right credentials.

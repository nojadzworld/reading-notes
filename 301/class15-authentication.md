# Authentication

## What is OAuth

What is OAuth?
**OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential.**

Give an example of what using OAuth would look like.
**The simplest example of OAuth is when you go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon.**

How does OAuth work? What are the steps that it takes to authenticate the user?
**The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
The first site gives this token and secret to the initiating user’s client software.
The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
The user approves (or their software silently approves) a particular transaction type at the first website.
The user is given an approved access token (notice it’s no longer a request token).
The user gives the approved access token to the first website.
The first website gives the access token to the second website as proof of authentication on behalf of the user.
The second website lets the first website access their site on behalf of the user.
The user sees a successfully completed transaction occurring.
OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons).**
What is OpenID?
**OpenID would serve as a single sign-in, vouching for the identities of users.**

## Authorization and Authentication flows

What is the difference between authorization and authentication?
**Auth0 uses the OpenID Connect (OIDC) Protocol and OAuth 2.0 Authorization Framework to authenticate users and get their authorization to access protected resources. During authentication, mobile and native applications can use the Authorization Code Flow, but they require additional security**

What is Authorization Code Flow?
**exchanges an Authorization Code for a token.**

What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
**an extension to the OAuth 2.0 authorization framework that enhances security for mobile and native applications.**

What is Implicit Flow with Form Post?
**The Implicit Flow with Form Post is an OAuth 2.0 authorization flow that is commonly used in client-side applications, such as single-page web applications (SPA).**
What is Client Credentials Flow?
**The Client Credentials Flow is an OAuth 2.0 authorization flow that is used by clients to obtain an access token when the client is acting on its own behalf, rather than on behalf of a user. In this flow, the client application sends its own credentials (client ID and client secret) to the authorization server, which then returns an access token that can be used to access protected resources.**

What is Device Authorization Flow?
**The Device Authorization Flow is an OAuth 2.0 authorization flow that is used by devices that do not have a browser or cannot enter credentials directly. Examples include smart TVs, streaming media players, and Internet of Things (IoT) devices.**

What is Resource Owner Password Flow?
**The Resource Owner Password Flow is an OAuth 2.0 authorization flow that is used when the user has a trust relationship with the client application and is willing to share their username and password with the client application**
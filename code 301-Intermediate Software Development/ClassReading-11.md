# Authentication

[home](/README.md)

# Reading
## What is OAuth

### What is OAuth?
It is an open standard authorization protocol or framework that decribes how unrelated servers and services can safely allow access to their assets whith out sharing the intitial single logon credintal.

### Give an example of what using OAuth would look like.
So you would essentially be using a third party to authnticate you to seamlessly log in to a handful of other websites/apps. It is machines logginging into machines on behalf of humans.


### How does OAuth work?What are the steps that it takes to authenticate the user?
<ol>
<li>The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.</li>
<li>The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.</li>
<li>The first site gives this token and secret to the initiating user’s client software.</li>
<li>The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).</li>
<li>If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.</li>
<li>The user approves (or their software silently approves) a particular transaction type at the first website.</li>
<li>The user is given an approved access token (notice it’s no longer a request token).</li>
<li>The user gives the approved access token to the first website.</li>
<li>The first website gives the access token to the second website as proof of authentication on behalf of the user.</li>
<li>The second website lets the first website access their site on behalf of the user.</li>
<li>The user sees a successfully completed transaction occurring</li>
<li>OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons).</li>
</ol>

### What is openID?
It is for humans logging into machines.


## Authorization and Authentication Flows


### What is the difference between authorization and authentication?
Authentication confirms that users are who they say they are. Authorization gives these users permission to access a resource.

### What is authorization code flow?
Flow that exchanges an authorization code for a token.

### What is Authorzation code flow with proof key for code exchange(PKCE)?
It is very similar to authorization code flow but has a secret created by the calling application that is then verified by the authorization server.

### What is implicit flow with form post?
It is intended for public clients or applications which are unable to securely store client secrets.

### what is client credentials flow?
A system that authenticates and authorizes the app rather than a user. MZM apps pass along their client ID and client secret to authenticate themselves and get a token.

### What is Device Authorization flow?
The device aks the user to go to a link on their computer,phone and authorize the device. It avoids a poor user experience for devices that do not have an easy way to enter text.

### What is a resource owner password flow?
Flow that requests that users provide credentials (username and password), typically using an interactive form. Should only be used when redirect flows cannot be used.

## Things I want to know more about

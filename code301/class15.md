# Class 15

[Journal Home](README.md)

Current Readings:

1. [What is OAuth](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)
2. [Authorization and Authentication flows]()

## Reading Notes

### What is OAuth

1. OAuth is an authorization service that unrelated websites can used to communicate with one another on behalf of a user without directly sharing the users login information. This means the user does not need to login multiple times even though their service requires visiting several unassociated websites or applications.
2. Theoretically, you could log into facebook and say that you want to access files in google docs. You could be posting a resume, or something. Google docs could be opened by facebook via OAuth and as a user you wouldn't need to sign into your google account.
3. The user wishes to make a connection between two sites that they already have authorization for. One of the websites will access a second and then a cascade occurs. The endpoint is a user that can navigate services of an application or service through another one. Neither of the additional two sites will require sharing of authentication with the other.
4. OpenID is an authentication technology that OAuth uses for its services.

### Authorization and Authentication flows

1. Authorization is between the client and the website. While authentication is between two separate websites that are associated with user. In particular, those two websites have previous authorization from the user.
2. This is the process of the user submitting authorization that allows them to access protected information.
3. This is used for single page sites and on device applications.
4. Implicit flow uses only an ID for the verification process. This is no longer considered best practice for secure authorization.
5. This is used for M2M communication and is the authentication flow that is used from an external technology to another.
6. This is used when a device is better suited to verify their identity by not typing in credentials. This can arise for different reasons, but however it does arise, the device uses another way to verify the permission.
7. This is used for highly trusted sites and is not recommended to be used according to the article.

### Things I want to know more about

I'm still unsure how the implement AuthO in practice. This will be a good thing to either figure out during the final project or during code 401.

&copy; 2022, NoMichi

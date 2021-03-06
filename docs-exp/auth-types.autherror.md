<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/auth-types](./auth-types.md) &gt; [AuthError](./auth-types.autherror.md)

## AuthError interface


<b>Signature:</b>

```typescript
export interface AuthError extends FirebaseError 
```
<b>Extends:</b> FirebaseError

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [appName](./auth-types.autherror.appname.md) | string | The name of the Firebase App which triggered this error. |
|  [email](./auth-types.autherror.email.md) | string | The email of the user's account, used for sign-in/linking. |
|  [phoneNumber](./auth-types.autherror.phonenumber.md) | string | The phone number of the user's account, used for sign-in/linking. |
|  [tenantid](./auth-types.autherror.tenantid.md) | string | The tenant ID being used for sign-in/linking. If you use <code>signInWithRedirect</code> to sign in, you have to set the tenant ID on [Auth](./auth-types.auth.md) instance again as the tenant ID is not persisted after redirection. |


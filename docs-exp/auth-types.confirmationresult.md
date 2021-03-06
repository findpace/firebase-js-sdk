<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/auth-types](./auth-types.md) &gt; [ConfirmationResult](./auth-types.confirmationresult.md)

## ConfirmationResult interface

A result from a phone number sign-in, link, or reauthenticate call.

<b>Signature:</b>

```typescript
export interface ConfirmationResult 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [verificationId](./auth-types.confirmationresult.verificationid.md) | string | The phone number authentication operation's verification ID. This can be used along with the verification code to initialize a phone auth credential. |

## Methods

|  Method | Description |
|  --- | --- |
|  [confirm(verificationCode)](./auth-types.confirmationresult.confirm.md) | Finishes a phone number sign-in, link, or reauthentication. |


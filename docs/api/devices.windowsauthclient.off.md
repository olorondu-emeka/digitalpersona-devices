<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@digitalpersona/devices](./devices.md) &gt; [WindowsAuthClient](./devices.windowsauthclient.md) &gt; [off](./devices.windowsauthclient.off.md)

## WindowsAuthClient.off() method

Deletes an event handler for the event.

<b>Signature:</b>

```typescript
off<E extends Event>(event?: string, handler?: Handler<E>): this;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  event | <code>string</code> | a name of the event to subscribe. |
|  handler | <code>Handler&lt;E&gt;</code> | an event handler added with the [WindowsAuthClient.on()](./devices.windowsauthclient.on.md) method. |

<b>Returns:</b>

`this`

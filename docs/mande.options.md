<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [mande](./mande.md) &gt; [Options](./mande.options.md)

## Options interface

Allowed options for a request. Extends native `RequestInit`<!-- -->.

**Signature:**

```typescript
export interface Options<ResponseAs extends ResponseAsTypes = ResponseAsTypes> extends RequestInit 
```
**Extends:** RequestInit

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [headers?](./mande.options.headers.md) |  | Record&lt;string, string&gt; | _(Optional)_ Headers sent alongside the request |
|  [query?](./mande.options.query.md) |  | any | _(Optional)_ Optional query object. Does not support arrays. Will get stringified |
|  [responseAs?](./mande.options.responseas.md) |  | ResponseAs | _(Optional)_ What kind of response is expected. Defaults to <code>json</code>. <code>response</code> will return the raw response from <code>fetch</code>. |


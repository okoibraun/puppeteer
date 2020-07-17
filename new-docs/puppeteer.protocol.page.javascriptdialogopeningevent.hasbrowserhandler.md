<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Page](./puppeteer.protocol.page.md) &gt; [JavascriptDialogOpeningEvent](./puppeteer.protocol.page.javascriptdialogopeningevent.md) &gt; [hasBrowserHandler](./puppeteer.protocol.page.javascriptdialogopeningevent.hasbrowserhandler.md)

## Protocol.Page.JavascriptDialogOpeningEvent.hasBrowserHandler property

True iff browser is capable showing or acting on the given dialog. When browser has no dialog handler for given target, calling alert while Page domain is engaged will stall the page execution. Execution can be resumed via calling Page.handleJavaScriptDialog.

<b>Signature:</b>

```typescript
hasBrowserHandler: boolean;
```
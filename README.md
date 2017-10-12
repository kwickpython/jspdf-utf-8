# jspdf-utf-8

**An AddOn to solve UTF-8 fonts in client-side JavaScript PDF creation.**

You can [catch me on twitter](http://twitter.com/kwickpos):  or head over to [my company's website](https://kwickpos.com).

## [Live PDF](http://tjin.kwickpos.com/) | [Documentation](https//kwickpos.com/opensource/utf8pdf)

## Creating your first document


Then you're ready to start making your document:

```javascript
// example with jspdf
var pdf = new jsPDF()
pdf.utext=utf8text;
pdf.utext(10,20,'Hello 你好.')

pdf.text('Hello world!', 10, 10)
pdf.utext('Hello world!', 10, 10)

pdf.save('a4.pdf')
```

Great! Now give us a Star :)

embedded fonts for client side PDF(pdfkit, jspdf..), UTF8 encode, multibyte characters language, chinese...

Not really a embedded solution, but gets the job done much faster. Loading a giant font matrixs is not fun. Our goal is to using the client machine to its maximum, not to wasting our bandwidth.

So, with this add on, we can have client computer build all the required fonts, keep them in session storage.


🏡 To find out more about my projects and me-as-a-person, go and visit my website at [noahdoersing.com](https://noahdoersing.com).

[![](stuff.png)](https://noahdoersing.com)

📫 Want to get in touch? Feel free to drop me an email to the address that the following JavaScript snippet evaluates to.

```js
((crypt) => {
    const rot13 = c => {
        c = c.codePointAt(0);
        let d = c + 13;
        if (d > (c <= 90 ? 90 : 122)) {
            d -= 26;
        }
        return String.fromCodePoint(d);
    }
    const backwards = s => s.split("").reverse().join("");
    return backwards(crypt.replace(/[a-z]/gi, rot13));
})("zbp.tavferbqunba@vu");
```

🖋 Your physical mailbox is hungry for a [pen-plotted postcard](https://github.com/doersino/genuary2022)? Well, [toss me a coin](https://paypal.me/noah) and make sure to put down your address in the message field!

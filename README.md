# DataProx

A tool to run data: URLs unrestricted.

## What is a data URL proxy?

A data URL proxy, or "Data Proxy", is a proxy that only allows the viewing of data:text/html URLs.

Data Proxies tend to consist of:

1. An iframe
2. ... Thats it.

But WHY an iframe?

because iframes have full access to data urls no matter what it is.

What browsers support data proxies?

Data urls can be accessed by:

|Browser   |Version   |Can access data: urls?   |
|----------|----------|-------------------------|
|Chrome    |148       |Yes                      |
|Edge      |145       |Yes                      |
|Safari    |26.4      |Yes                      |
|FireFox   |151       |Yes                      |
|Opera     |125       |Yes                      |
|IE        |11        |Maybe?                   |
|S. Int.   |29        |Yes                      |

So it can basically be used by any browser (Dont know if Internet Explorer works.)

Can i learn more about data urls?

Sure! The [MDN Docs](https://developer.mozilla.org/en-US/docs/Web/URI/Reference/Schemes/data) have all the information you need.

Why would you make this?

Because i like data URLs.

## Registering a site

Registering a site to DataProx is simple.

fork this repo, add your site in registry.json, make a pull request.

! NOTE ! Make sure the site is a data URL. 

## Converting HTML code to Base64 encryption

I would recommend using [Base64 Guru](https://base64.guru/converter/encode/html). Simple and easy to use

## Contributing

Pull requests are welcome! you can request to add/edit a feature.

## License

[MIT License](https://choosealicense.com/licenses/mit/)

Copyright (c) 2026 MintSD

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

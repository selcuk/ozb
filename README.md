# ozb
A command line viewer for OzBargain.com.au.

## Installation

This is a simple `bash` script. Simply download it and copy to somewhere on the path and make it 
executable. For example:

    cp ozb /usr/local/bin
    chmod 755 /usr/local/bin/ozb

## Usage
Running the `ozb` command without any arguments will fetch the current **Front Page Deals** 
(deals that are relatively new and have been voted up by the users) and **New Deals** 
(the latest deals, regardless of the number of votes). For example:

    $ ozb
       ___     ___                     _      
      / _ \ __| _ ) __ _ _ _ __ _ __ _(_)_ _  
     | (_) |_ / _ \/ _` | '_/ _` / _` | | ' \ 
      \___//__|___/\__,_|_| \__, \__,_|_|_||_|
                            |___/
    Front Page Deals
    - Russell Hobbs Addison Kettle $63 Delivered @ Amazon AU
    - Seiko Orange Samurai SRPC07 $287.71 Delivered @ Amazon AU
    - Free Delivery with $25 Minimum Spend @ McDonald’s via Uber Eats
    - Sommersault Palm Beach Sunshelter $5 @ Bunnings
    - Refer-a-Friend now $10 Each (was $5) @ Cashrewards
    New Deals
    - 2 Months Half Price Storage @ Wilson Storage
    - Free Book - Event Streams in Action at Manning
    - Ugg Australia Mini Boots $51 (Usually $186) @ Ugg-Express-Australia eBay
    - Russell Hobbs Addison Kettle $63 Delivered @ Amazon AU
    - Huawei GT2 Sport Smart Watch (42mm, Black) $219 @ JB Hi-Fi

The actual output should be longer and more colourful than the markdown formatted text above. 
You can also search for a specific product by passing its 
[tag](https://www.ozbargain.com.au/tag/) as a command line argument:
    
    $ ozb iphone-xs
       ___     ___                     _      
      / _ \ __| _ ) __ _ _ _ __ _ __ _(_)_ _  
     | (_) |_ / _ \/ _` | '_/ _` / _` | | ' \ 
      \___//__|___/\__,_|_| \__, \__,_|_|_||_|
                            |___/
    iphone-xs Deals
    - iPhone XS Gold 512GB $1289 + Free Express Delivery @ Green Gadgets
    - iPhone XS 256GB (Space Grey) $1128 + 20,000 Points @ Telstra Plus
    - iPhone XS 64GB $499 Upfront on $65/M for 12months Contract @ JB Hi-Fi
    - Apple iPhone XS 64GB $999, 256GB $1149 (Expired) @ JB Hi-Fi
    - iPhone XS 64GB $999, XS 256GB $1149, XS 512GB $1349 (Save $100) @ JB Hi-Fi


## Compatibility

Tested on macOS 10.15 (Catalina) and Ubuntu Linux 18.04

## Todo

- Show upvotes/downvotes
- Hide expired/out of stock deals
- Show date and time the deal was submitted

## License

MIT License

Copyright (c) 2020 Selcuk Ayguney

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

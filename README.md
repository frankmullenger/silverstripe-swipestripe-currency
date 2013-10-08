# SwipeStripe Currency

## Maintainer Contact
SwipeStripe  
[Contact Us](http://swipestripe.com/support/contact-us)

## Requirements
* SilverStripe 3.1.*
* SwipeStripe 2.1.*

## Documentation
Multiple currency support. Base currency is used to process orders with the payment gateway.

## Installation Instructions
1. Place this directory in the root of your SilverStripe installation, rename the folder 'swipestripe-currency'.
2. Visit yoursite.com/dev/build?flush=1 to rebuild the database.

## Usage Overview
1. Create exchange rates in the Shop settings area, make sure there is an exchange rate for the base currency with a 1:1 ratio.
2. Add $CurrencyForm to your template

## License
	Copyright (c) 2011 - 2013, Frank Mullenger
	All rights reserved.

	Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

			* Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
			* Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the 
				documentation and/or other materials provided with the distribution.
			* Neither the name of SilverStripe nor the names of its contributors may be used to endorse or promote products derived from this software 
				without specific prior written permission.

	THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE 
	IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE 
	LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE 
	GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, 
	STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY 
	OF SUCH DAMAGE.
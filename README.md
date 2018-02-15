# Google Closure Compiler for Composer
## What is the Google Closure Compiler?
From [Google](https://developers.google.com/closure/compiler/):
> The Closure Compiler is a tool for making JavaScript download and run faster. It is a true compiler for JavaScript. Instead of compiling from a source language to machine code, it compiles from JavaScript to better JavaScript. It parses your JavaScript, analyzes it, removes dead code and rewrites and minimizes what's left. It also checks syntax, variable references, and types, and warns about common JavaScript pitfalls.


## Why does this repository exist?
If you don't want to commit the big (~6mb) compiler jar-file into your repository and want to install it
via composer then this package is for you. It's the latest compiled jar-binary of the Google Closure Compiler
which can be easily installed via Composer and added into your project on the fly.

I didn't change anything in the binary. All copyrights belong to Google.

## Installation
[![Packagist](https://img.shields.io/packagist/v/stalinko/google-closure-compiler.svg)](https://packagist.org/packages/stalinko/google-closure-compiler)

`composer require stalinko/google-closure-compiler`

## Usage

Read the [Google Docs](https://developers.google.com/closure/compiler/docs/gettingstarted_app) about how to use it.

Here is just a simple example:

`java -jar vendor/stalinko/google-closure-compiler/compiler.jar --js hello.js --js_output_file hello-compiled.js`

## License
This library contains the Closure Compiler from Google. The file `compiler.jar` is the result of 
unpacking the Google-supplied [Zip file](http://closure-compiler.googlecode.com/files/compiler-latest.zip).

## Feedback
Any feedback is welcome; use Github for communication.
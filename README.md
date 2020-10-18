# node-red-contrib-twin-bcrypt

## Introduction
A node that can be used for encrypting user passwords 

## Features

 * encrypt
 * verify

Uses **[twin-bcrypt.js](https://github.com/fpirsch/twin-bcrypt)**

## Options

  * **field**: field to encrypt or to verify against (string) *

  * **verify**: field to verify (hash) *

The field specified will be replaced with the encrypted version if the action is set to encrypt.

## Outputs

`msg.match` will be either true or false

## Credits
Fork of **[node-red-contrib-bcrypt](https://github.com/wstam88/node-red-contrib-bcrypt)**
Based on work started by Shane Girish at bcrypt-nodejs (MIT-licensed) which is itself based on javascript-bcrypt (New BSD-licensed)

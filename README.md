
# Simplest password checker

Check your password Strong or Weak
## Conditions for a Strong Password
Min 1 uppercase letter.

Min 1 lowercase letter.

Min 1 special character.

Min 1 number.

Min 8 characters.

Max 30 characters





## Installation

npm i checksee
## Usage

const checksee = require('checksee') 

const result = checksee('Checksee$#1234')

console.log(result)

output : Strong


const checksee = require('checksee') 

const result = checksee('hvfbdv')

console.log(result)

output : Weak
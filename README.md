# Simple Regex

## Installation 
For npm users `npm i simple-regex`
For yarn users `yarn add simple-regex`

## Usage
To test a variable against a Regex expression: 

`SimpleRegex.MobileNumber.Econet.test(<your-variable>)`. This will return a `boolean` which indicates whether your variable matches the Regex Pattern.

You can also inject the Regex Pattern into HTML form fields. An example of this pattern in ReactJS 
`<input type="text" name="number_plate" pattern={SimpleRegex.NumberPlate} title="Zimbabwean Number Plate">`


### Available Patterns

`SimpleRegex.MobileNumber.Econet` Pattern for Econet Mobile Numbers
`SimpleRegex.MobileNumber.Telecel` Pattern for Telecel Mobile Numbers
`SimpleRegex.MobileNumber.Netone` Pattern for Netone Mobile Numbers
`SimpleRegex.NumberPlate` Pattern for Zimbabwean National Vehicle Registration Numbers
`SimpleRegex.PassportNumber` Pattern for Zimbabwean Passport Numbers
`SimpleRegex.NationalId` Pattern for Zimbabwean National Identification Numbers 
`SimpleRegex.EmailAddress` Pattern for Email Addresses
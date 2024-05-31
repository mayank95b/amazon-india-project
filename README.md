# amazon-india-project





### Data Attribute

- is just another HTML attribute
- allows us to attach any information to an element.

#### Syntax

    attribute_name="attribute_value"

Example

    data-product-name="${product.name}">

## Modules

Modules are used to organize our code in a better way. 

it helps us avoid naming conflicts

### Create a Module

1. Create a file

2. Don't load the file with <Script>

### Get a Varaible Out of a File

1. Add type="module" attribute

2. Export

3. Import


## External Libraries

### dayjs

Day.js is a minimalist JavaScript library that parses, validates, manipulates, and displays dates and times for modern browsers with a largely Moment.js-compatible API.

Calling dayjs() with parameters returns a fresh Day.js object with the current date and time.

    var = now = dayjs()


#### List of all available formats

| Format        | Output            |  Description      |
| ------       |   -----------      | ----------        |
|    YY        |       18           | Two-digit year    |
|   YYYY       |    2018            |  Four-digit yeay  |
|   M          |    1-12            |  The month, beginning at 1|
|   MM         |  01-12             |  Yhe month, 2-digits |


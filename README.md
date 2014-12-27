# ampersand-hoodie-collection

Bundles in ampersand-hoodie-mixin to provide an ampersand-collection that uses Hoodie for storage.

## install
```
npm install ampersand-hoodie-collection
```

## example

var AmpersandHoodieCollection = require('./ampersand-hoodie-collection');
var Person = require('./person');

module.exports = AmpersandHoodieCollection.extend({
    model: Person,
    HOODIE_TYPE: 'person'
});

## usage

The only critical usage note is that implementing classes must declare a value for the HOODIE_TYPE property.
In the example above, the HOODIE_TYPE property states that this model will be represented in Hoodie as a "person" type.

## changelog


## credits

Thanks to the Ampersand and Hoodie groups!

## license

MIT

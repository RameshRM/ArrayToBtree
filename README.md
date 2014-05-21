ArrayToBtree [![Build Status](https://travis-ci.org/RameshRM/ArrayToBtree.svg?branch=master)](https://travis-ci.org/RameshRM/ArrayToBtree)
===============

#### Summary

```ArrayToBtree``` is a javcript implementation of building a "Binary tree" from an "Un-Ordered" array.  The Tree is not a fully weighted binary tree, but provides an API to convert an array to a tree datastructure.

#### Sample Usage

```javascript
var tree = require('array-to-btree');
var inputList = [3,5,8,9,11,12,13,15];
function build(input){
   return tree.toBTree(input);
}
```

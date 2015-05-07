Some vec4 functions from [gl-matrix]](http://github.com/toji/gl-matrix).


## Usage

### `vec4 = require('gl-vec4')`

Will load all of the module's functionality and expose it on a single
object. Note that any of the methods may also be required directly
from their files.

For example, the following are equivalent:

``` javascript
var set = require('gl-vec4').set
var set = require('gl-vec4/set')


## API

  - [create()](#create)
  - [set()](#setoutvec4xnumberynumberznumberwnumber)
  - [transformMat4()](#transformmat4outvec4avec4mmat4)

## create()

  Creates a new identity mat4

## set(out:vec4, x:Number, y:Number, z:Number, w:Number)

  Set the components of a vec4 to the given values

## transformMat4(out:vec4, a:vec4, m:mat4)

  Transforms the vec4 with a mat4.
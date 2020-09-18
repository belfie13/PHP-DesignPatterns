# B13 PHP Design Patterns

mostly direct from the manual designed from the php language.

⚠️ see last heading 'Algorithms'


## Classes and Objects

- [ ] visibility (`public`, `protected`, `private`)
- [ ] `abstract`
- [ ] `final`
- [ ] `static`
- [ ] magic methods
- [ ] interfaces
- [ ] cloning
- [ ] typehinting
- [ ] return types
- [ ] nullable types
- [ ] references
- [ ] variable length arguments

`$this` is a reference to the calling object within an object cont4xt
`$this` possibly references another object if `static` method context of a second object.
`new` create an instance of the `class`


### properties (constants / variables) and methods (functions)

define constants for
- value access keys
- identifiers (url...)


### extending other classes

`extends` inherit base functionality
- methods and properties with same name


#### overriding inheritance

- `final` prevents overrides
- `parent::` to access overridden implementations
- `abstract` requires implementation


### implementing interfaces

- constants cannot be overridden
- `extends` multiple interfaces in comma-separated list


### using traits

- included as if it were defined in the `class`?
- use multiple traits
- alias method name conflicts
- method priority: `class`, `trait`, `parent`


# Algorithms

* int = `interface`
* cls = `class`
* obj = `object`
* mth = `method`
* var = `variable`
* trt = `trait`
* ext = `extends`
* fin = `final`
* abs = `abstract`

- int {mth} -> cls

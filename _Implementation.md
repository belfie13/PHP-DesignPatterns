# B13 PHP Design Patterns

mostly direct from the manual designed from the php language.

⚠️ see last heading 'Algorithms'


## Classes and Objects

- [ ] visibility (`public`, `protected`, `private`)
- [ ] `abstract`
- [ ] `final`
- [ ] `static`
- [ ] magic methods
- [ ] interfaces (patterns and inheritance)
- [ ] cloning (deep vs. shallow)
- [ ] typehinting (parameter and return types)
- [ ] nullable / mixed types
- [ ] references
- [ ] variable length arguments

`$this` is a reference to the calling object within an object cont4xt
`$this` possibly references another object if `static` method context of a second object.
`new` create an instance of the `class`


### properties (constants / variables) and methods (functions)

define constants for any static values:
- value access keys
- identifiers (url...)
- standardized values that must only change or be added in new versions of software
- not dynamic
  - template element names/ids


### extending other classes

- `extends` inherit base functionality
- methods and properties with same name


#### overriding inheritance

- `final` prevents overrides
- `parent::` to access overridden implementations
- `abstract` requires implementation


### implementing interfaces

- `const` declarations cannot be overridden
- `interface` `extends` multiple `interface`s in _comma-separated_ list


### using traits

- included as if its members were defined in the `class`
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
- cls -> trt Logger

# TypeMap Revitalized

An updated version of the crate [typemap](https://github.com/reem/rust-typemap) which is a hashmap whose keys are defined by types.

Original code created by: [Acdenissk](https://github.com/acdenissk)

Crate created by: [kingbri](https://github.com/bdashore3)

## Documentation

Documentation is located [here](https://docs.rs/typemap_rev)

## Example

```rust
use typemap_rev::{ TypeMap, TypeMapKey };

struct Number;

impl TypeMapKey for Number {
    type Value = i32;
}

let mut map = TypeMap::new();
map.insert::<Number>(42);
```

## Help/Support

Join the Serenity-rs Discord server here: [https://discord.gg/9X7vCus](https://discord.gg/9X7vCus) and feel free to ask your questions!
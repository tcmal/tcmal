```rust
let person = PersonBuilder::new()
               .name("Aria")
               .alias("tcmal")
               .website("aria.rip")
               .country(Countries::Scotland)
               .language(Language::Rust, Level::Great)
               .language(Language::Nix, Level::Great)
               .language(Language::Python, Level::Good)
               .language(Language::Js, Level::Good)
               .build();
```

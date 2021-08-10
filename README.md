```rust
let person = PersonBuilder::new()
               .name("Oscar")
               .alias("tcmal")
               .pronouns(Pronouns::TheyThem)
               .website("tcmal.xyz")
               .country(Countries::Scotland)
               .language(Language::Rust, Level::Good)
               .language(Language::Python, Level::Great)
               .language(Language::Js, Level::Great)
               .build();
```

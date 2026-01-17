# Hi there, I'm Anar.

```Rust
fn main() {
    let firstname = "Anar";
    let lastname = "Enkhzol";
    let alias = "Aukovien";
    let age = "24";
    let interests = [
        "Cybersecurity", "OSINT", "Web Exploit",
        "Reverse Engineering", "Cooking"
    ];
    
    let social = "@Aukovien";

    println!(r#"{} "{}" {} | Age: {}"#, firstname, alias, lastname, age);
    println!("Interests: {:?}", interests);
    println!("Social: {}", social);
}
```

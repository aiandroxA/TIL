cargoはbundler的なポジション

`cargo add actix-web`を実行する or `Cargo.toml`に下記を入力

```
[package]
name = "rusty_chiba"
version = "0.1.0"
edition = "2021"

[dependencies]
actix-web = "4.9.0"
```

`cargo add tokio --features full`は、機能を指定する。特に指定しなかったらミニマム機能。

---

コードが書けたら`cargo run`で、コンパイル & mainの実行

```rs
#[cfg(test)]
mod endotestdayo {
    #[test]
    fn it_works() {
        assert_eq!(2 + 2, 4);
    }
}
```

`#`付きの行は、コンパイラに対する命令と捉えてもいい。



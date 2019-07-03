Extract `rustup-init.xz`. To install `rustup` configured to not install docs by
default, run:

> rustup-init --profile=minimal

(`rustup-init --help` will help you)

After installing, please run `rustup dump-testament`, and verify that the output is:

```
Rustup version renders as: 1.18.3+119 (b5787936d 2019-07-03)
Current crate version: 1.18.3
Built from branch: profiles
Commit info: 1.18.3+119 (b5787936d 2019-07-03)
Working tree is clean
```

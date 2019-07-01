Extract `rustup-init.xz`. To install `rustup` configured to not install docs by
default, run:

> rustup-init --profile=minimal

(`rustup-init --help` will help you)

After installing, please run `rustup dump-testament`, and verify that the output is:

```
Rustup version renders as: 1.18.3+97 (c2dccd630 2019-07-01)
Current crate version: 1.18.3
Built from branch: profiles
Commit info: 1.18.3+97 (c2dccd630 2019-07-01)
Working tree is clean
```

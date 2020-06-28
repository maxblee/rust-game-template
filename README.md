# `game-template`

This is a template for [`cargo-generate`](https://github.com/ashleygwilliams/cargo-generate). I'm using it as I learn about game development in Rust, so right now, it is *very light* on detail. Eventually, I'll flush it out a bit more.

## Setting up a project.

In order to set up a game, you have to do two things. First, type

```sh
cargo generate --git https://github.com/maxblee/rust-game-template.git
```

and follow the instructions. (Or add the `--name` option).

Second, go into `.github/workflows/release.yml` and change the release name. (You can find this by grepping for `TODO`.)

Eventually, I might remove the second requirement, but it requires changes to the GitHub workflows or to `cargo-generate`.
## License

This template is licensed under MIT. Copyright 2020, Max Lee.

It follows the design from [`cargo-generate`](https://github.com/ashleygwilliams/cargo-generate) and borrows code for the Github Workflows from [Github Actions for Rust binaries](https://github.com/paskausks/rust-bin-github-workflows) and [Release Action](https://github.com/ncipollo/release-action), with only a few minor modifications.
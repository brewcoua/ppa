# `brewcoua/ppa`

PPA repositories for my packages and other automated repositories.

## Usage

```bash
curl -SsL https://ppa.brewen.dev/ubuntu/KEY.gpg | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/brewcoua.gpg > /dev/null
sudo curl -SsL -o /etc/apt/sources.list.d/brewcoua.list https://ppa.brewen.dev/ubuntu/brewcoua.list

# Update package list and install whichever package you want
sudo apt update && sudo apt install <package> # e.g. discord
```

## Disclaimer

I do not own some of the packages in this repository. I am not responsible for any issues that may arise from using these packages. Use at your own risk.

Regardless, this repository is merely a mirror for a more convenient installation process.

## License

This project is licensed under either of the following, at your option:

- Apache License, Version 2.0, ([LICENSE-APACHE](LICENSE-APACHE) or http://www.apache.org/licenses/LICENSE-2.0)
- MIT License ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in the work by you,
as defined in the Apache-2.0 license, shall be dual licensed as above, without any additional terms or conditions.

Any packages in this repository are licensed under their respective licenses. In the case of a conflict, the license of the package will take precedence.
For example, the `discord` package is licensed under the Discord Terms of Service, which can be found [here](https://discord.com/terms).

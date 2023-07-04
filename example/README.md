# Flux Burst Example

This is an example that will perform a burst, however without a local cluster
we will just be running the burst as an isolated cluster. In the context of
a real burst we would provide a broker config (broker.toml) that points back
to the host it bursted from. I made this example primarily to test the plugin
without needing to be in the context of the operator.

## Usage

Before running, be sure to have credentials in `$HOME/.aws/config`
Run the faux burst, using the defaults and in mock mode.

```bash
$ python run-burst.py --mock
```

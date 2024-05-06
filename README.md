## Command line options

| Option    | Description                        | Default       |
|-----------|------------------------------------|---------------|
|`--fortune`| Fortune file, one fortune per line | ./fortune.txt |
|`--static` | Static assets directory            | ./static      |
|`--port`   | Port to bind to                    | 3000          |

## Versions and Container Images
The release version corresponds to the container image version

## Public key

The public key to verify the image is in the repository `cosign.pub`. To verify the image use [cosign](https://github.com/sigstore/cosign)

```
cosign verify --key cosign.pub ghcr.io/chukmunnlee/go-fortune:<tag>
```

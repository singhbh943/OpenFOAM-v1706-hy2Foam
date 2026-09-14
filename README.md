# OpenFOAM-v1706 + hyStrath/hy2Foam

Validated complete environment containing:

- OpenFOAM-v1706
- ThirdParty-v1706
- hyStrath
- hy2Foam
- partialCatalyticWall
- fullyCatalyticWall
- superCatalyticWall
- associated run/test cases

The complete validated environment is provided through GitHub Releases as a split .tar.gz archive.

## Restore

Download both archive parts and the SHA256SUMS file.

Verify:
    sha256sum -c OpenFOAM-v1706-hy2Foam-validated-20260914.SHA256SUMS

Reconstruct:
    cat OpenFOAM-v1706-hy2Foam-validated-20260914.tar.gz.part-* > OpenFOAM-v1706-hy2Foam-validated-20260914.tar.gz

Check:
    gzip -t OpenFOAM-v1706-hy2Foam-validated-20260914.tar.gz

Extract:
    tar -xzf OpenFOAM-v1706-hy2Foam-validated-20260914.tar.gz

## Documentation

See the complete validated reproduction guide:

[OpenFOAM-v1706 + hyStrath/hy2Foam Reproduction Guide](docs/OpenFOAM-v1706_hy2Foam_Validated_Reproduction_Guide.pdf)

## Complete Environment

Download the validated environment from:

https://github.com/singhbh943/OpenFOAM-v1706-hy2Foam/releases/tag/v1.0.0-validated

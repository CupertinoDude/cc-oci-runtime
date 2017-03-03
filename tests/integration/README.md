## cc-oci-runtime integration tests

### Docker

First the Docker integration tests need to be enabled:

```
./autogen.sh --enable-docker-tests
```

Then to run the Docker integration tests:

```
sudo -E make docker-tests
```

### CRI-O

First the CRI-O integration tests need to be enabled:

```
./autogen.sh --enable-crio-tests
```

Then to run the Docker integration tests:

```
sudo -E make crio-tests
```

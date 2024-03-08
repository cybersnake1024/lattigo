# Introduction

This is the code for protecting privacy using single-party and multi-party homomorphic encryption via Lattigo Library.

### Testing performance among different block size choices
```bash
$ go run .\blocksize_choices\test_blocks.go
```

### Testing privacy metrics like entropy, transition
```bash
$ go run .\privacy_metrics\test_metrics.go
```

### Testing attack success rate
```bash
$ go run .\asr\test_asr.go
```
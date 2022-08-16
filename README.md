# :package:  JWT smithy

Simple cli tool for jwt keys generation

---

## :arrow_down: Installation

### :snake: PIP

```bash
pip install jwt_smithy
```

### :honey_pot: Poetry

```bash
poetry add jwt_smithy
```

## :cake: How to use it

### Generate rs256 keypair
```bash
smithy rsa
```

### Generate ec256 keypair
```bash
smithy ecdsa
```

### Generate sh256 key
```bash
smithy shmac
```

### Show command list
```bash
smithy --help
```
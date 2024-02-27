### [<- Return](../../)

# Lab 10

`hash_value.py`:

first time:

```bash
The hash for 1 is: 1
The hash for 1.0 is: 1
The hash for 3.14 is: 1846836513
The hash for Python is: 1351405614
The hash for a tuple of vowels is: -1435801780
The hash for an object of person is: -44800423
```

second time:

```bash
The hash for 1 is: 1
The hash for 1.0 is: 1
The hash for 3.14 is: 1846836513
The hash for Python is: 403235973
The hash for a tuple of vowels is: -474146146
The hash for an object of person is: -638098916
```

`snakecoin.py`:

```bash
Block #1 has been added to the blockchain!
Hash: 3cff7aed0b1c6c152475ff0e1d9c57496eff533e7b1a6b09412a3a2ad05c009e

Block #2 has been added to the blockchain!
Hash: 5aca907f2d51ebdea286cca712db48a29e1536c3d8d728f2bb214264920c109f

Block #3 has been added to the blockchain!
Hash: c69980571a846f9a76de723b5f556434411a6ee02ff79a7c9981175d963061de

Block #4 has been added to the blockchain!
Hash: 8e73bb4d0a0074a22b14915955ea6c892856421287b735cc24421fa6a6e6008e

Block #5 has been added to the blockchain!
Hash: ff955f6c950705eec7edbd460a99ab1db8f91a3737f483ec8bb463448fd4dab8

Block #6 has been added to the blockchain!
Hash: 176189e430b149577a2ecb7a207b6805eeab0592c05a229aebfb4f62ac5d2513

Block #7 has been added to the blockchain!
Hash: 48a7e19d679e6fdc23b77da2858428f87df3f1a54abc5cd32e5ba8c48a1fde04

Block #8 has been added to the blockchain!
Hash: e306940673aa9fb5b4979fb7d5455e4f4bb9cec73c7af1ede4f38a698eb07ed1

Block #9 has been added to the blockchain!
Hash: d76f8f28eaa0f1c5f302e248c019e17f29dd091a35d57eaafbdf5c945f5df08b

Block #10 has been added to the blockchain!
Hash: ef373cef0d10b56f99343a5040e58372a251323a611a80063c1adaf8ea2b8fcc

Block #11 has been added to the blockchain!
Hash: cebcb4eb94bf5b65a9343cad3d19b04d0b8ea7b6599ad4edaf3525971743d6bf

Block #12 has been added to the blockchain!
Hash: 1b103628498da402d2c5f7d6c631262ea6034baf74e4cb0ac48d630cc5d42231

Block #13 has been added to the blockchain!
Hash: 822d0f06b1c4c030498725f6bb48f1028c272de1f8cec509febb3e0d602f7103

Block #14 has been added to the blockchain!
Hash: 5202d5ee5933a1c0b902f0c884caa5f8c2ac36d537ac341254295be328551fe6

Block #15 has been added to the blockchain!
Hash: b8d5ed99382f0d1d3d9acb0f6dd5ed40cb67b55e6d9dfb1d15a376f0b1951243

Block #16 has been added to the blockchain!
Hash: 3ec9037c3cd78d6641392a52546a215f76fed53413b77c74521feef608ab5e3d

Block #17 has been added to the blockchain!
Hash: 1e201c62d370283271a3b32239b460fd329c9b186c169f8fb3c809012706d8cf

Block #18 has been added to the blockchain!
Hash: 268d20c9cb61a4b57bf7ad44bdbcf86781a1dbea955e77aa048aea1ee435aaf7

Block #19 has been added to the blockchain!
Hash: c80fdfd147e71d06b4a428295b9a3184b189d0108b341866a6a63ebf4ed92fdd

Block #20 has been added to the blockchain!
Hash: 886c5290b3aeb3d1ec1def1bffed5889d19b66f51a341981035f686fd37e874b
```

```bash
ryan@rpi:~ $ curl localhost:5000/mine
{"index": 1, "timestamp": "2024-02-26 22:09:17.191811", "data": {"proof-of-work": 18, "transactions": [{"from": "akjflw", "to": "fjlakdj", "amount": 3}, {"from": "network", "to": "q3nf394hjg-random-miner-address-34nf3i4nflkn3oi", "amount": 1}]}, "hash": "62d0370c99bda9fe024cad8bd060a479202097270bad4fd1c571a07d6ba3276a"}
```

### Post!

![IMG_20240226_221648890](https://github.com/redassser/Design-6/assets/40395425/8028c7a7-2540-45a0-99ff-0728886d3fae)

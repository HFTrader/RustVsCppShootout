# RustVsCppShootout

I guess the main holdout on this set of tests is how to structure this such that the benchmarks for Rust vs C++ are lined up in the results somehow. 

Are we having two separate directories with the same file structure like 

```bash
RustVsCppShootout/
├── cpp
│   ├── test01
│   └── test02
└── rust
    ├── test01
    └── test02
```

Or we can somehow structure it like this? Would the benchmarks allow? 
```bash
RustVsCppShootout/
├── cpp
│   ├── test01
│   └── test02
└── rust
    ├── test01
    └── test02
```

On C++ I'd suggest going for Google Benchmarks and on Rust? 
How can we glue the results? Cucumber? 

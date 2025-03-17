# eBPF C Template

A simplified eBPF project template based on libbpf-bootstrap, designed for larger projects.

## Prerequisites

- Git
- bpftool
- clang
- gcc

## Setup

1. Initialize git submodules:
```bash
git submodule init
git submodule update
```

2. Generate vmlinux:
```bash
cd tools
./gen_vmlinux.sh
```

## Build and Run

1. Compile the project:
```bash
make
```

2. Run the program:
```bash
sudo ./build/bootstrap
```
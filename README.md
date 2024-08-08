# banking-trace-tool
Personal utility tool for scanning through Solana banking-trace data

# How to install

## 1. Clone the repo

## 2. Change to the repo directory

## 3. Install the tool 
This assumes you already have rust and cargo installed.

```bash
cargo install --path .
```

# Usage
```bash
banking-trace-tool --path <PATH> <COMMAND>

Commands:
  account-usage     Get account usage statistics for a given slot range
  graphia-input     Write graphia json input file for a given slot
  slot-ranges       Get the ranges of slots for data in diectory
  update-alt-store  Update Address-Lookup-Table store for tables used in a given slot-range
  help              Print this message or the help of the given subcommand(s)

Options:
  -p, --path <PATH>  The path to the banking trace event file directory
  -h, --help         Print help
```

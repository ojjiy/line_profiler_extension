## What this program can do
Aggregate statistics of execution time analysis by the greatest tool [line_profiler](https://github.com/rkern/line_profiler).

## Benefit
- Unite multi-thread results
- Unite repetitive results without any modification to source code

## Installation
```bash
$ pip install git+https://github.com/ojjiy/line_profiler_extension.git
```

## Usage
```bash
$ reshape.py [files to be aggregated] [folders which contain files to be aggregated] [--color]
```

## Verification
```bash
$ reshape.py ./inputs --colorize
$ less -R ./result.txt
```

## Change
### 1.0
initial release

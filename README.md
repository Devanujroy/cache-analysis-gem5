# Cache Design Analysis using gem5

## Objective
To analyze how cache parameters affect system performance.

## Parameters Tested
- Cache Size: 256KB vs 512KB
- Associativity: 1-way, 2-way, 4-way
- Block Size: 32B vs 64B

## Metrics Observed
- CPI
- L1 Cache Miss Rate
- L2 Cache Miss Rate

## Methodology
Simulations were run using gem5 with controlled parameter variation. Only one parameter was changed at a time.

## Results
(Add graphs or tables here)

## Key Insights
- Higher associativity reduces conflict misses
- Larger cache size reduces miss rate
- Block size impacts spatial locality

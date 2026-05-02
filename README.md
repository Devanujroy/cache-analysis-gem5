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
Simulation results showed clear trends across different cache configurations. Increasing cache size from 256KB to 512KB reduced overall miss rate and improved CPI. Higher associativity significantly reduced conflict misses, especially in smaller cache sizes. Increasing block size improved spatial locality but slightly increased miss penalty in some cases.

## Key Insights
- Higher associativity reduces conflict misses
- Larger cache size reduces miss rate
- Block size impacts spatial locality

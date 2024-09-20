# Benchmark Results: ToFloat

Number of images: 1000

## CPU Information

- CPU: Apple M1 Pro
- Frequency: Current: 3228.00 MHz, Min: 600.00 MHz, Max: 3228.00 MHz
- Physical cores: 10
- Total cores: 10

## Package Versions

| Python                                   | albucore   | opencv-python-headless   | numpy   | torchvision   |
|:-----------------------------------------|:-----------|:-------------------------|:--------|:--------------|
| 3.8.19 (default, Mar 20 2024, 15:27:52)  | 0.0.12     | 4.10.0.84                | 1.24.4  | 0.19.1        |
| [Clang 14.0.6 ]                          |            |                          |         |               |

## Performance (images/second)

Raw data:
           albucore         lut      opencv       numpy torchvision
ToFloat  4110 ± 601  2307 ± 242  1760 ± 191  2032 ± 492  2714 ± 170

|         | albucore   | lut        | opencv     | numpy      | torchvision   |
|:--------|:-----------|:-----------|:-----------|:-----------|:--------------|
| ToFloat | 4110 ± 601 | 2307 ± 242 | 1760 ± 191 | 2032 ± 492 | 2714 ± 170    |
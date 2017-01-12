**Baseline**

|               |  O0  |  O1  |  O2  |  O3  |  Ofast
|---------------|------|------|------|------|-------
|g++ 6.2.1      |  26  |  4   |  4   |  4   |  4
|clang++ 3.9.0  |  22  |  4   |  4   |  4   |  4





**Template parameter**

|               |  O0              |  O1             |  O2           |  O3           |  Ofast
|---------------|------------------|-----------------|---------------|---------------|-------------
|g++ 6.2.1      |  152 *(+484.%)*  |  4 *(+0.0%)*    |  4 *(+0.0%)*  |  4 *(+0.0%)*  |  4 *(+0.0%)*
|clang++ 3.9.0  |  129 *(+486.%)*  |  38 *(+850.%)*  |  4 *(+0.0%)*  |  4 *(+0.0%)*  |  4 *(+0.0%)*





**`function_view`**

|               |  O0              |  O1              |  O2             |  O3             |  Ofast
|---------------|------------------|------------------|-----------------|-----------------|---------------
|g++ 6.2.1      |  753 *(+2796%)*  |  68 *(+1600%)*   |  7 *(+75.0%)*   |  19 *(+375.%)*  |  19 *(+375.%)*
|clang++ 3.9.0  |  591 *(+2586%)*  |  278 *(+6850%)*  |  14 *(+250.%)*  |  14 *(+250.%)*  |  14 *(+250.%)*





**`std::function`**

|               |  O0               |  O1              |  O2              |  O3              |  Ofast
|---------------|-------------------|------------------|------------------|------------------|----------------
|g++ 6.2.1      |  1368 *(+5161%)*  |  182 *(+4450%)*  |  133 *(+3225%)*  |  153 *(+3725%)*  |  153 *(+3725%)*
|clang++ 3.9.0  |  1010 *(+4490%)*  |  521 *(+1292%)*  |  142 *(+3450%)*  |  142 *(+3450%)*  |  142 *(+3450%)*





**Baseline (`inline`)**

|               |  O0  |  O1  |  O2  |  O3  |  Ofast
|---------------|------|------|------|------|-------
|g++ 6.2.1      |  26  |  4   |  4   |  4   |  4
|clang++ 3.9.0  |  22  |  4   |  4   |  4   |  4




**Template parameter (`inline`)**

|               |  O0              |  O1             |  O2           |  O3           |  Ofast
|---------------|------------------|-----------------|---------------|---------------|-------------
|g++ 6.2.1      |  152 *(+484.%)*  |  4 *(+0.0%)*    |  4 *(+0.0%)*  |  4 *(+0.0%)*  |  4 *(+0.0%)*
|clang++ 3.9.0  |  129 *(+486.%)*  |  38 *(+850.%)*  |  4 *(+0.0%)*  |  4 *(+0.0%)*  |  4 *(+0.0%)*





**`function_view` (`inline`)**

|               |  O0              |  O1              |  O2           |  O3           |  Ofast
|---------------|------------------|------------------|---------------|---------------|-------------
|g++ 6.2.1      |  753 *(+2796%)*  |  4 *(+0.0%)*     |  4 *(+0.0%)*  |  4 *(+0.0%)*  |  4 *(+0.0%)*
|clang++ 3.9.0  |  591 *(+2586%)*  |  278 *(+6850%)*  |  4 *(+0.0%)*  |  4 *(+0.0%)*  |  4 *(+0.0%)*





**`std::function` (`inline`)**

|               |  O0               |  O1              |  O2              |  O3              |  Ofast
|---------------|-------------------|------------------|------------------|------------------|----------------
|g++ 6.2.1      |  1368 *(+5161%)*  |  167 *(+4075%)*  |  128 *(+3100%)*  |  128 *(+3100%)*  |  128 *(+3100%)*
|clang++ 3.9.0  |  1010 *(+4490%)*  |  521 *(+1292%)*  |  117 *(+2825%)*  |  117 *(+2825%)*  |  117 *(+2825%)*





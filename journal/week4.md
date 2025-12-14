# Week 4 – CPU and Memory Stress Test

I performed basic stress tests using `stress-ng`.

## Commands

```bash
stress-ng --cpu 2 --timeout 20s
```
![CPU Test](../images/week4_cpu_test.jpeg)

```bash
stress-ng --vm 2 --vm-bytes 256M --timeout 20s
```
![Memory Test](../images/week4_mem_test.jpeg)

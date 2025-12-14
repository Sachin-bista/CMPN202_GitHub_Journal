# Week 5 – Disk Performance Test

This week was dedicated to running disk benchmarking tools using `fio`.

## Command

```bash
fio --name=benchmark --ioengine=libaio --rw=randwrite --bs=4k 
```
![FIO Test](../Images/week5_fio_test.jpeg)

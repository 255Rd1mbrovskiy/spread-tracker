# spread-tracker

![CI](https://github.com/255Rd1mbrovskiy/spread-tracker/actions/workflows/ci.yml/badge.svg)

CLI-утиліта для трекінгу **спреду** та **дисбалансу глибини** на спотових ринках Binance/Bybit.

## Приклад виводу

![Example Output](./docs/photo_2025-09-29_12-41-10.jpg)
> Скрипт показує best bid/ask та спред, а також дисбаланс об’ємів у топ-10 рівнях стакану.  
> Підтримується режим single-shot (`--once`) і стрім з інтервалом.
## Використання
```bash
spread-tracker --exchange binance --symbol BTCUSDT --once
spread-tracker -e bybit -s ETHUSDT -d 20 -i 2

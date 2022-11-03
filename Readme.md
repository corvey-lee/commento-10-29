Redis.conf

- bind option 잘 활용하기
- protected option 활용해야하는지 여부 확인해보기
- password 굳이 설정해 줘야 하는지 확인해보기
- cluster mode는 어떻게 해줘야할지
- cluster는 redis 에서 어떻게 구성할 수 있는지

```
redis-cli --cluster create 10.68.7.6:6379 \
10.68.8.9:6379 \
10.68.1.6:6379 \
10.68.2.14:6379 \
10.68.5.7:6379 \
10.68.3.6:6379 \
10.68.4.8:6379 \
10.68.0.11:6379 \
10.68.6.6:6379 --cluster-replicas 2
```

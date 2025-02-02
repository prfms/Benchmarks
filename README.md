# Проект измерение производительности 

В проекте написан набор бенчмарк-тестов, которые показывают скорость работы разных версий одного и того же метода.
Использован профильный фреймворк [JMH](https://github.com/openjdk/jmh).

## Результаты
| Benchmark                             | Mode | Score  | Units    |
|---------------------------------------|------|--------|----------|
| ReflectionBenchmark.directAccess      | avgt | 0,652  | ns/op    |
| ReflectionBenchmark.lambdaMetafactory | avgt | 6,634  | ns/op    |
| ReflectionBenchmark.methodInvoke      | avgt | 6,009  | ns/op    |
| ReflectionBenchmark.reflection        | avgt | 7,633  | ns/op    |



# startsWith-contains-benchmark

C:\java\open\jdk-18.0.2\bin\java.exe "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA 2022.3.2\lib\idea_rt.jar=57895:C:\Program Files\JetBrains\IntelliJ IDEA 2022.3.2\bin" -Dfile.encoding=UTF-8 -Dsun.stdout.encoding=UTF-8 -Dsun.stderr.encoding=UTF-8 -classpath C:\work\experimental\startsWith-contains-benchmark\target\classes;C:\Users\golsh\.m2\repository\org\springframework\spring-beans\6.0.8\spring-beans-6.0.8.jar;C:\Users\golsh\.m2\repository\org\springframework\spring-core\6.0.8\spring-core-6.0.8.jar;C:\Users\golsh\.m2\repository\org\springframework\spring-jcl\6.0.8\spring-jcl-6.0.8.jar;C:\Users\golsh\.m2\repository\org\openjdk\jmh\jmh-core\1.35\jmh-core-1.35.jar;C:\Users\golsh\.m2\repository\net\sf\jopt-simple\jopt-simple\5.0.4\jopt-simple-5.0.4.jar;C:\Users\golsh\.m2\repository\org\apache\commons\commons-math3\3.2\commons-math3-3.2.jar;C:\Users\golsh\.m2\repository\org\openjdk\jmh\jmh-generator-annprocess\1.35\jmh-generator-annprocess-1.35.jar org.example.Main
# JMH version: 1.35
# VM version: JDK 18.0.2, OpenJDK 64-Bit Server VM, 18.0.2+9-61
# VM invoker: C:\java\open\jdk-18.0.2\bin\java.exe
# VM options: -javaagent:C:\Program Files\JetBrains\IntelliJ IDEA 2022.3.2\lib\idea_rt.jar=57895:C:\Program Files\JetBrains\IntelliJ IDEA 2022.3.2\bin -Dfile.encoding=UTF-8 -Dsun.stdout.encoding=UTF-8 -Dsun.stderr.encoding=UTF-8
# Blackhole mode: compiler (auto-detected, use -Djmh.blackhole.autoDetect=false to disable)
# Warmup: 5 iterations, 10 s each
# Measurement: 5 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 1 thread, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.example.Main.contains

# Run progress: 0,00% complete, ETA 00:50:00
# Fork: 1 of 5
# Warmup Iteration   1: 0,446 ops/ns
# Warmup Iteration   2: 0,447 ops/ns
# Warmup Iteration   3: 0,505 ops/ns
# Warmup Iteration   4: 0,419 ops/ns
# Warmup Iteration   5: 0,416 ops/ns
Iteration   1: 0,410 ops/ns
Iteration   2: 0,407 ops/ns
Iteration   3: 0,407 ops/ns
Iteration   4: 0,418 ops/ns
Iteration   5: 0,431 ops/ns

# Run progress: 3,33% complete, ETA 00:48:44
# Fork: 2 of 5
# Warmup Iteration   1: 0,378 ops/ns
# Warmup Iteration   2: 0,348 ops/ns
# Warmup Iteration   3: 0,405 ops/ns
# Warmup Iteration   4: 0,353 ops/ns
# Warmup Iteration   5: 0,350 ops/ns
Iteration   1: 0,349 ops/ns
Iteration   2: 0,352 ops/ns
Iteration   3: 0,351 ops/ns
Iteration   4: 0,357 ops/ns
Iteration   5: 0,366 ops/ns

# Run progress: 6,67% complete, ETA 00:47:02
# Fork: 3 of 5
# Warmup Iteration   1: 0,446 ops/ns
# Warmup Iteration   2: 0,428 ops/ns
# Warmup Iteration   3: 0,443 ops/ns
# Warmup Iteration   4: 0,427 ops/ns
# Warmup Iteration   5: 0,429 ops/ns
Iteration   1: 0,427 ops/ns
Iteration   2: 0,427 ops/ns
Iteration   3: 0,430 ops/ns
Iteration   4: 0,431 ops/ns
Iteration   5: 0,450 ops/ns

# Run progress: 10,00% complete, ETA 00:45:21
# Fork: 4 of 5
# Warmup Iteration   1: 0,437 ops/ns
# Warmup Iteration   2: 0,330 ops/ns
# Warmup Iteration   3: 0,383 ops/ns
# Warmup Iteration   4: 0,418 ops/ns
# Warmup Iteration   5: 0,418 ops/ns
Iteration   1: 0,422 ops/ns
Iteration   2: 0,418 ops/ns
Iteration   3: 0,424 ops/ns
Iteration   4: 0,427 ops/ns
Iteration   5: 0,443 ops/ns

# Run progress: 13,33% complete, ETA 00:43:40
# Fork: 5 of 5
# Warmup Iteration   1: 0,436 ops/ns
# Warmup Iteration   2: 0,425 ops/ns
# Warmup Iteration   3: 0,494 ops/ns
# Warmup Iteration   4: 0,427 ops/ns
# Warmup Iteration   5: 0,427 ops/ns
Iteration   1: 0,427 ops/ns
Iteration   2: 0,428 ops/ns
Iteration   3: 0,427 ops/ns
Iteration   4: 0,429 ops/ns
Iteration   5: 0,446 ops/ns


Result "org.example.Main.contains":
  0,412 ±(99.9%) 0,023 ops/ns [Average]
  (min, avg, max) = (0,349, 0,412, 0,450), stdev = 0,031
  CI (99.9%): [0,389, 0,435] (assumes normal distribution)


# JMH version: 1.35
# VM version: JDK 18.0.2, OpenJDK 64-Bit Server VM, 18.0.2+9-61
# VM invoker: C:\java\open\jdk-18.0.2\bin\java.exe
# VM options: -javaagent:C:\Program Files\JetBrains\IntelliJ IDEA 2022.3.2\lib\idea_rt.jar=57895:C:\Program Files\JetBrains\IntelliJ IDEA 2022.3.2\bin -Dfile.encoding=UTF-8 -Dsun.stdout.encoding=UTF-8 -Dsun.stderr.encoding=UTF-8
# Blackhole mode: compiler (auto-detected, use -Djmh.blackhole.autoDetect=false to disable)
# Warmup: 5 iterations, 10 s each
# Measurement: 5 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 1 thread, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.example.Main.startsWith

# Run progress: 16,67% complete, ETA 00:41:59
# Fork: 1 of 5
# Warmup Iteration   1: 0,487 ops/ns
# Warmup Iteration   2: 0,473 ops/ns
# Warmup Iteration   3: 0,480 ops/ns
# Warmup Iteration   4: 0,474 ops/ns
# Warmup Iteration   5: 0,475 ops/ns
Iteration   1: 0,473 ops/ns
Iteration   2: 0,472 ops/ns
Iteration   3: 0,471 ops/ns
Iteration   4: 0,462 ops/ns
Iteration   5: 0,455 ops/ns

# Run progress: 20,00% complete, ETA 00:40:18
# Fork: 2 of 5
# Warmup Iteration   1: 0,486 ops/ns
# Warmup Iteration   2: 0,470 ops/ns
# Warmup Iteration   3: 0,472 ops/ns
# Warmup Iteration   4: 0,469 ops/ns
# Warmup Iteration   5: 0,469 ops/ns
Iteration   1: 0,468 ops/ns
Iteration   2: 0,469 ops/ns
Iteration   3: 0,470 ops/ns
Iteration   4: 0,469 ops/ns
Iteration   5: 0,472 ops/ns

# Run progress: 23,33% complete, ETA 00:38:37
# Fork: 3 of 5
# Warmup Iteration   1: 0,491 ops/ns
# Warmup Iteration   2: 0,468 ops/ns
# Warmup Iteration   3: 0,470 ops/ns
# Warmup Iteration   4: 0,470 ops/ns
# Warmup Iteration   5: 0,471 ops/ns
Iteration   1: 0,459 ops/ns
Iteration   2: 0,469 ops/ns
Iteration   3: 0,469 ops/ns
Iteration   4: 0,469 ops/ns
Iteration   5: 0,484 ops/ns

# Run progress: 26,67% complete, ETA 00:36:56
# Fork: 4 of 5
# Warmup Iteration   1: 0,497 ops/ns
# Warmup Iteration   2: 0,492 ops/ns
# Warmup Iteration   3: 0,501 ops/ns
# Warmup Iteration   4: 0,497 ops/ns
# Warmup Iteration   5: 0,498 ops/ns
Iteration   1: 0,496 ops/ns
Iteration   2: 0,479 ops/ns
Iteration   3: 0,480 ops/ns
Iteration   4: 0,479 ops/ns
Iteration   5: 0,465 ops/ns

# Run progress: 30,00% complete, ETA 00:35:15
# Fork: 5 of 5
# Warmup Iteration   1: 0,492 ops/ns
# Warmup Iteration   2: 0,477 ops/ns
# Warmup Iteration   3: 0,482 ops/ns
# Warmup Iteration   4: 0,478 ops/ns
# Warmup Iteration   5: 0,476 ops/ns
Iteration   1: 0,477 ops/ns
Iteration   2: 0,471 ops/ns
Iteration   3: 0,476 ops/ns
Iteration   4: 0,476 ops/ns
Iteration   5: 0,481 ops/ns


Result "org.example.Main.startsWith":
  0,472 ±(99.9%) 0,006 ops/ns [Average]
  (min, avg, max) = (0,455, 0,472, 0,496), stdev = 0,008
  CI (99.9%): [0,466, 0,479] (assumes normal distribution)


# JMH version: 1.35
# VM version: JDK 18.0.2, OpenJDK 64-Bit Server VM, 18.0.2+9-61
# VM invoker: C:\java\open\jdk-18.0.2\bin\java.exe
# VM options: -javaagent:C:\Program Files\JetBrains\IntelliJ IDEA 2022.3.2\lib\idea_rt.jar=57895:C:\Program Files\JetBrains\IntelliJ IDEA 2022.3.2\bin -Dfile.encoding=UTF-8 -Dsun.stdout.encoding=UTF-8 -Dsun.stderr.encoding=UTF-8
# Blackhole mode: compiler (auto-detected, use -Djmh.blackhole.autoDetect=false to disable)
# Warmup: 5 iterations, 10 s each
# Measurement: 5 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 1 thread, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.example.Main.contains

# Run progress: 33,33% complete, ETA 00:33:35
# Fork: 1 of 5
# Warmup Iteration   1: 2,235 ns/op
# Warmup Iteration   2: 2,331 ns/op
# Warmup Iteration   3: 2,208 ns/op
# Warmup Iteration   4: 2,326 ns/op
# Warmup Iteration   5: 2,317 ns/op
Iteration   1: 2,317 ns/op
Iteration   2: 2,319 ns/op
Iteration   3: 2,325 ns/op
Iteration   4: 2,324 ns/op
Iteration   5: 2,184 ns/op

# Run progress: 36,67% complete, ETA 00:31:54
# Fork: 2 of 5
# Warmup Iteration   1: 2,250 ns/op
# Warmup Iteration   2: 2,328 ns/op
# Warmup Iteration   3: 1,988 ns/op
# Warmup Iteration   4: 2,326 ns/op
# Warmup Iteration   5: 2,323 ns/op
Iteration   1: 2,332 ns/op
Iteration   2: 2,330 ns/op
Iteration   3: 2,361 ns/op
Iteration   4: 2,391 ns/op
Iteration   5: 2,263 ns/op

# Run progress: 40,00% complete, ETA 00:30:13
# Fork: 3 of 5
# Warmup Iteration   1: 2,228 ns/op
# Warmup Iteration   2: 2,381 ns/op
# Warmup Iteration   3: 2,051 ns/op
# Warmup Iteration   4: 2,373 ns/op
# Warmup Iteration   5: 2,368 ns/op
Iteration   1: 2,381 ns/op
Iteration   2: 2,372 ns/op
Iteration   3: 2,373 ns/op
Iteration   4: 2,369 ns/op
Iteration   5: 2,201 ns/op

# Run progress: 43,33% complete, ETA 00:28:32
# Fork: 4 of 5
# Warmup Iteration   1: 2,321 ns/op
# Warmup Iteration   2: 2,472 ns/op
# Warmup Iteration   3: 2,254 ns/op
# Warmup Iteration   4: 2,433 ns/op
# Warmup Iteration   5: 2,460 ns/op
Iteration   1: 2,465 ns/op
Iteration   2: 2,445 ns/op
Iteration   3: 2,463 ns/op
Iteration   4: 2,442 ns/op
Iteration   5: 2,394 ns/op

# Run progress: 46,67% complete, ETA 00:26:51
# Fork: 5 of 5
# Warmup Iteration   1: 2,281 ns/op
# Warmup Iteration   2: 2,399 ns/op
# Warmup Iteration   3: 2,339 ns/op
# Warmup Iteration   4: 2,429 ns/op
# Warmup Iteration   5: 2,418 ns/op
Iteration   1: 2,409 ns/op
Iteration   2: 2,410 ns/op
Iteration   3: 2,416 ns/op
Iteration   4: 2,424 ns/op
Iteration   5: 2,136 ns/op


Result "org.example.Main.contains":
  2,354 ±(99.9%) 0,064 ns/op [Average]
  (min, avg, max) = (2,136, 2,354, 2,465), stdev = 0,085
  CI (99.9%): [2,290, 2,417] (assumes normal distribution)


# JMH version: 1.35
# VM version: JDK 18.0.2, OpenJDK 64-Bit Server VM, 18.0.2+9-61
# VM invoker: C:\java\open\jdk-18.0.2\bin\java.exe
# VM options: -javaagent:C:\Program Files\JetBrains\IntelliJ IDEA 2022.3.2\lib\idea_rt.jar=57895:C:\Program Files\JetBrains\IntelliJ IDEA 2022.3.2\bin -Dfile.encoding=UTF-8 -Dsun.stdout.encoding=UTF-8 -Dsun.stderr.encoding=UTF-8
# Blackhole mode: compiler (auto-detected, use -Djmh.blackhole.autoDetect=false to disable)
# Warmup: 5 iterations, 10 s each
# Measurement: 5 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 1 thread, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.example.Main.startsWith

# Run progress: 50,00% complete, ETA 00:25:11
# Fork: 1 of 5
# Warmup Iteration   1: 2,022 ns/op
# Warmup Iteration   2: 2,159 ns/op
# Warmup Iteration   3: 2,134 ns/op
# Warmup Iteration   4: 2,151 ns/op
# Warmup Iteration   5: 2,164 ns/op
Iteration   1: 2,148 ns/op
Iteration   2: 2,171 ns/op
Iteration   3: 2,167 ns/op
Iteration   4: 2,177 ns/op
Iteration   5: 2,141 ns/op

# Run progress: 53,33% complete, ETA 00:23:30
# Fork: 2 of 5
# Warmup Iteration   1: 2,083 ns/op
# Warmup Iteration   2: 2,184 ns/op
# Warmup Iteration   3: 2,151 ns/op
# Warmup Iteration   4: 2,168 ns/op
# Warmup Iteration   5: 2,169 ns/op
Iteration   1: 2,177 ns/op
Iteration   2: 2,116 ns/op
Iteration   3: 2,137 ns/op
Iteration   4: 2,171 ns/op
Iteration   5: 2,105 ns/op

# Run progress: 56,67% complete, ETA 00:21:49
# Fork: 3 of 5
# Warmup Iteration   1: 2,019 ns/op
# Warmup Iteration   2: 2,127 ns/op
# Warmup Iteration   3: 2,140 ns/op
# Warmup Iteration   4: 2,185 ns/op
# Warmup Iteration   5: 2,170 ns/op
Iteration   1: 2,156 ns/op
Iteration   2: 2,158 ns/op
Iteration   3: 2,179 ns/op
Iteration   4: 2,193 ns/op
Iteration   5: 2,271 ns/op

# Run progress: 60,00% complete, ETA 00:20:09
# Fork: 4 of 5
# Warmup Iteration   1: 2,039 ns/op
# Warmup Iteration   2: 2,156 ns/op
# Warmup Iteration   3: 2,126 ns/op
# Warmup Iteration   4: 2,159 ns/op
# Warmup Iteration   5: 2,157 ns/op
Iteration   1: 2,155 ns/op
Iteration   2: 2,161 ns/op
Iteration   3: 2,176 ns/op
Iteration   4: 2,155 ns/op
Iteration   5: 2,138 ns/op

# Run progress: 63,33% complete, ETA 00:18:28
# Fork: 5 of 5
# Warmup Iteration   1: 2,034 ns/op
# Warmup Iteration   2: 2,173 ns/op
# Warmup Iteration   3: 2,141 ns/op
# Warmup Iteration   4: 2,172 ns/op
# Warmup Iteration   5: 2,162 ns/op
Iteration   1: 2,180 ns/op
Iteration   2: 2,180 ns/op
Iteration   3: 2,179 ns/op
Iteration   4: 2,173 ns/op
Iteration   5: 2,132 ns/op


Result "org.example.Main.startsWith":
  2,164 ±(99.9%) 0,023 ns/op [Average]
  (min, avg, max) = (2,105, 2,164, 2,271), stdev = 0,031
  CI (99.9%): [2,140, 2,187] (assumes normal distribution)


# JMH version: 1.35
# VM version: JDK 18.0.2, OpenJDK 64-Bit Server VM, 18.0.2+9-61
# VM invoker: C:\java\open\jdk-18.0.2\bin\java.exe
# VM options: -javaagent:C:\Program Files\JetBrains\IntelliJ IDEA 2022.3.2\lib\idea_rt.jar=57895:C:\Program Files\JetBrains\IntelliJ IDEA 2022.3.2\bin -Dfile.encoding=UTF-8 -Dsun.stdout.encoding=UTF-8 -Dsun.stderr.encoding=UTF-8
# Blackhole mode: compiler (auto-detected, use -Djmh.blackhole.autoDetect=false to disable)
# Warmup: 5 iterations, 10 s each
# Measurement: 5 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 1 thread, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.example.Main.contains

# Run progress: 66,67% complete, ETA 00:16:47
# Fork: 1 of 5
# Warmup Iteration   1: 23,703 ±(99.9%) 0,438 ns/op
# Warmup Iteration   2: 27,045 ±(99.9%) 1,770 ns/op
# Warmup Iteration   3: 24,091 ±(99.9%) 0,279 ns/op
# Warmup Iteration   4: 26,990 ±(99.9%) 0,855 ns/op
# Warmup Iteration   5: 27,625 ±(99.9%) 1,742 ns/op
Iteration   1: 26,455 ±(99.9%) 1,464 ns/op
                 contains·p0.00:   ≈ 0 ns/op
                 contains·p0.50:   ≈ 0 ns/op
                 contains·p0.90:   100,000 ns/op
                 contains·p0.95:   100,000 ns/op
                 contains·p0.99:   100,000 ns/op
                 contains·p0.999:  101,000 ns/op
                 contains·p0.9999: 8235,829 ns/op
                 contains·p1.00:   53952,000 ns/op

Iteration   2: 24,012 ±(99.9%) 0,251 ns/op
                 contains·p0.00:   ≈ 0 ns/op
                 contains·p0.50:   ≈ 0 ns/op
                 contains·p0.90:   100,000 ns/op
                 contains·p0.95:   100,000 ns/op
                 contains·p0.99:   100,000 ns/op
                 contains·p0.999:  101,000 ns/op
                 contains·p0.9999: 300,000 ns/op
                 contains·p1.00:   4496,000 ns/op

Iteration   3: 28,099 ±(99.9%) 2,116 ns/op
                 contains·p0.00:   ≈ 0 ns/op
                 contains·p0.50:   ≈ 0 ns/op
                 contains·p0.90:   100,000 ns/op
                 contains·p0.95:   100,000 ns/op
                 contains·p0.99:   100,000 ns/op
                 contains·p0.999:  101,000 ns/op
                 contains·p0.9999: 15251,226 ns/op
                 contains·p1.00:   81408,000 ns/op

Iteration   4: 29,609 ±(99.9%) 2,492 ns/op
                 contains·p0.00:   ≈ 0 ns/op
                 contains·p0.50:   ≈ 0 ns/op
                 contains·p0.90:   100,000 ns/op
                 contains·p0.95:   100,000 ns/op
                 contains·p0.99:   100,000 ns/op
                 contains·p0.999:  101,000 ns/op
                 contains·p0.9999: 20412,205 ns/op
                 contains·p1.00:   62656,000 ns/op

Iteration   5: 24,685 ±(99.9%) 0,808 ns/op
                 contains·p0.00:   ≈ 0 ns/op
                 contains·p0.50:   ≈ 0 ns/op
                 contains·p0.90:   100,000 ns/op
                 contains·p0.95:   100,000 ns/op
                 contains·p0.99:   100,000 ns/op
                 contains·p0.999:  101,000 ns/op
                 contains·p0.9999: 718,251 ns/op
                 contains·p1.00:   75776,000 ns/op


# Run progress: 70,00% complete, ETA 00:15:06
# Fork: 2 of 5
# Warmup Iteration   1: 23,692 ±(99.9%) 0,462 ns/op
# Warmup Iteration   2: 27,324 ±(99.9%) 1,764 ns/op
# Warmup Iteration   3: 24,294 ±(99.9%) 0,532 ns/op
# Warmup Iteration   4: 24,455 ±(99.9%) 0,568 ns/op
# Warmup Iteration   5: 27,941 ±(99.9%) 2,004 ns/op
Iteration   1: 27,131 ±(99.9%) 1,781 ns/op
                 contains·p0.00:   ≈ 0 ns/op
                 contains·p0.50:   ≈ 0 ns/op
                 contains·p0.90:   100,000 ns/op
                 contains·p0.95:   100,000 ns/op
                 contains·p0.99:   100,000 ns/op
                 contains·p0.999:  101,000 ns/op
                 contains·p0.9999: 11442,368 ns/op
                 contains·p1.00:   65088,000 ns/op

Iteration   2: 24,136 ±(99.9%) 0,271 ns/op
                 contains·p0.00:   ≈ 0 ns/op
                 contains·p0.50:   ≈ 0 ns/op
                 contains·p0.90:   100,000 ns/op
                 contains·p0.95:   100,000 ns/op
                 contains·p0.99:   100,000 ns/op
                 contains·p0.999:  101,000 ns/op
                 contains·p0.9999: 282,724 ns/op
                 contains·p1.00:   10992,000 ns/op

Iteration   3: 28,615 ±(99.9%) 2,344 ns/op
                 contains·p0.00:   ≈ 0 ns/op
                 contains·p0.50:   ≈ 0 ns/op
                 contains·p0.90:   100,000 ns/op
                 contains·p0.95:   100,000 ns/op
                 contains·p0.99:   100,000 ns/op
                 contains·p0.999:  101,000 ns/op
                 contains·p0.9999: 15230,138 ns/op
                 contains·p1.00:   91648,000 ns/op

Iteration   4: 29,092 ±(99.9%) 2,498 ns/op
                 contains·p0.00:   ≈ 0 ns/op
                 contains·p0.50:   ≈ 0 ns/op
                 contains·p0.90:   100,000 ns/op
                 contains·p0.95:   100,000 ns/op
                 contains·p0.99:   100,000 ns/op
                 contains·p0.999:  101,000 ns/op
                 contains·p0.9999: 16570,835 ns/op
                 contains·p1.00:   67840,000 ns/op

Iteration   5: 24,104 ±(99.9%) 0,341 ns/op
                 contains·p0.00:   ≈ 0 ns/op
                 contains·p0.50:   ≈ 0 ns/op
                 contains·p0.90:   100,000 ns/op
                 contains·p0.95:   100,000 ns/op
                 contains·p0.99:   100,000 ns/op
                 contains·p0.999:  101,000 ns/op
                 contains·p0.9999: 200,000 ns/op
                 contains·p1.00:   22080,000 ns/op


# Run progress: 73,33% complete, ETA 00:13:26
# Fork: 3 of 5
# Warmup Iteration   1: 23,751 ±(99.9%) 0,491 ns/op
# Warmup Iteration   2: 27,846 ±(99.9%) 1,927 ns/op
# Warmup Iteration   3: 24,125 ±(99.9%) 0,410 ns/op
# Warmup Iteration   4: 24,225 ±(99.9%) 0,622 ns/op
# Warmup Iteration   5: 23,282 ±(99.9%) 0,298 ns/op
Iteration   1: 23,491 ±(99.9%) 0,358 ns/op
                 contains·p0.00:   ≈ 0 ns/op
                 contains·p0.50:   ≈ 0 ns/op
                 contains·p0.90:   100,000 ns/op
                 contains·p0.95:   100,000 ns/op
                 contains·p0.99:   100,000 ns/op
                 contains·p0.999:  101,000 ns/op
                 contains·p0.9999: 602,019 ns/op
                 contains·p1.00:   22784,000 ns/op

Iteration   2: 24,227 ±(99.9%) 1,058 ns/op
                 contains·p0.00:   ≈ 0 ns/op
                 contains·p0.50:   ≈ 0 ns/op
                 contains·p0.90:   100,000 ns/op
                 contains·p0.95:   100,000 ns/op
                 contains·p0.99:   100,000 ns/op
                 contains·p0.999:  101,000 ns/op
                 contains·p0.9999: 1382,408 ns/op
                 contains·p1.00:   59968,000 ns/op

Iteration   3: 23,386 ±(99.9%) 0,436 ns/op
                 contains·p0.00:   ≈ 0 ns/op
                 contains·p0.50:   ≈ 0 ns/op
                 contains·p0.90:   100,000 ns/op
                 contains·p0.95:   100,000 ns/op
                 contains·p0.99:   100,000 ns/op
                 contains·p0.999:  101,000 ns/op
                 contains·p0.9999: 1400,000 ns/op
                 contains·p1.00:   23680,000 ns/op

Iteration   4: 23,932 ±(99.9%) 0,388 ns/op
                 contains·p0.00:   ≈ 0 ns/op
                 contains·p0.50:   ≈ 0 ns/op
                 contains·p0.90:   100,000 ns/op
                 contains·p0.95:   100,000 ns/op
                 contains·p0.99:   100,000 ns/op
                 contains·p0.999:  101,000 ns/op
                 contains·p0.9999: 299,664 ns/op
                 contains·p1.00:   17792,000 ns/op

Iteration   5: 23,293 ±(99.9%) 0,340 ns/op
                 contains·p0.00:   ≈ 0 ns/op
                 contains·p0.50:   ≈ 0 ns/op
                 contains·p0.90:   100,000 ns/op
                 contains·p0.95:   100,000 ns/op
                 contains·p0.99:   100,000 ns/op
                 contains·p0.999:  101,000 ns/op
                 contains·p0.9999: 365,380 ns/op
                 contains·p1.00:   4000,000 ns/op


# Run progress: 76,67% complete, ETA 00:11:45
# Fork: 4 of 5
# Warmup Iteration   1: 23,357 ±(99.9%) 0,438 ns/op
# Warmup Iteration   2: 23,182 ±(99.9%) 0,252 ns/op
# Warmup Iteration   3: 23,398 ±(99.9%) 0,499 ns/op
# Warmup Iteration   4: 23,378 ±(99.9%) 0,369 ns/op
# Warmup Iteration   5: 23,183 ±(99.9%) 0,243 ns/op
Iteration   1: 23,647 ±(99.9%) 0,623 ns/op
                 contains·p0.00:   ≈ 0 ns/op
                 contains·p0.50:   ≈ 0 ns/op
                 contains·p0.90:   100,000 ns/op
                 contains·p0.95:   100,000 ns/op
                 contains·p0.99:   100,000 ns/op
                 contains·p0.999:  101,000 ns/op
                 contains·p0.9999: 778,650 ns/op
                 contains·p1.00:   35072,000 ns/op

Iteration   2: 23,150 ±(99.9%) 0,257 ns/op
                 contains·p0.00:   ≈ 0 ns/op
                 contains·p0.50:   ≈ 0 ns/op
                 contains·p0.90:   100,000 ns/op
                 contains·p0.95:   100,000 ns/op
                 contains·p0.99:   100,000 ns/op
                 contains·p0.999:  101,000 ns/op
                 contains·p0.9999: 114,860 ns/op
                 contains·p1.00:   6000,000 ns/op

Iteration   3: 23,491 ±(99.9%) 0,855 ns/op
                 contains·p0.00:   ≈ 0 ns/op
                 contains·p0.50:   ≈ 0 ns/op
                 contains·p0.90:   100,000 ns/op
                 contains·p0.95:   100,000 ns/op
                 contains·p0.99:   100,000 ns/op
                 contains·p0.999:  101,000 ns/op
                 contains·p0.9999: 473,240 ns/op
                 contains·p1.00:   92672,000 ns/op

Iteration   4: 25,301 ±(99.9%) 0,990 ns/op
                 contains·p0.00:   ≈ 0 ns/op
                 contains·p0.50:   ≈ 0 ns/op
                 contains·p0.90:   100,000 ns/op
                 contains·p0.95:   100,000 ns/op
                 contains·p0.99:   100,000 ns/op
                 contains·p0.999:  101,000 ns/op
                 contains·p0.9999: 1499,897 ns/op
                 contains·p1.00:   57152,000 ns/op

Iteration   5: 25,842 ±(99.9%) 1,724 ns/op
                 contains·p0.00:   ≈ 0 ns/op
                 contains·p0.50:   ≈ 0 ns/op
                 contains·p0.90:   100,000 ns/op
                 contains·p0.95:   100,000 ns/op
                 contains·p0.99:   100,000 ns/op
                 contains·p0.999:  101,000 ns/op
                 contains·p0.9999: 9955,680 ns/op
                 contains·p1.00:   49664,000 ns/op


# Run progress: 80,00% complete, ETA 00:10:04
# Fork: 5 of 5
# Warmup Iteration   1: 23,478 ±(99.9%) 0,452 ns/op
# Warmup Iteration   2: 23,263 ±(99.9%) 0,571 ns/op
# Warmup Iteration   3: 23,254 ±(99.9%) 0,519 ns/op
# Warmup Iteration   4: 23,329 ±(99.9%) 0,248 ns/op
# Warmup Iteration   5: 23,659 ±(99.9%) 1,082 ns/op
Iteration   1: 24,590 ±(99.9%) 0,737 ns/op
                 contains·p0.00:   ≈ 0 ns/op
                 contains·p0.50:   ≈ 0 ns/op
                 contains·p0.90:   100,000 ns/op
                 contains·p0.95:   100,000 ns/op
                 contains·p0.99:   100,000 ns/op
                 contains·p0.999:  101,000 ns/op
                 contains·p0.9999: 504,760 ns/op
                 contains·p1.00:   55040,000 ns/op

Iteration   2: 25,407 ±(99.9%) 1,218 ns/op
                 contains·p0.00:   ≈ 0 ns/op
                 contains·p0.50:   ≈ 0 ns/op
                 contains·p0.90:   100,000 ns/op
                 contains·p0.95:   100,000 ns/op
                 contains·p0.99:   100,000 ns/op
                 contains·p0.999:  101,000 ns/op
                 contains·p0.9999: 1651,489 ns/op
                 contains·p1.00:   71424,000 ns/op

Iteration   3: 26,995 ±(99.9%) 1,643 ns/op
                 contains·p0.00:   ≈ 0 ns/op
                 contains·p0.50:   ≈ 0 ns/op
                 contains·p0.90:   100,000 ns/op
                 contains·p0.95:   100,000 ns/op
                 contains·p0.99:   100,000 ns/op
                 contains·p0.999:  101,000 ns/op
                 contains·p0.9999: 16042,680 ns/op
                 contains·p1.00:   47872,000 ns/op

Iteration   4: 23,993 ±(99.9%) 0,351 ns/op
                 contains·p0.00:   ≈ 0 ns/op
                 contains·p0.50:   ≈ 0 ns/op
                 contains·p0.90:   100,000 ns/op
                 contains·p0.95:   100,000 ns/op
                 contains·p0.99:   100,000 ns/op
                 contains·p0.999:  101,000 ns/op
                 contains·p0.9999: 363,620 ns/op
                 contains·p1.00:   17376,000 ns/op

Iteration   5: 24,441 ±(99.9%) 1,564 ns/op
                 contains·p0.00:   ≈ 0 ns/op
                 contains·p0.50:   ≈ 0 ns/op
                 contains·p0.90:   100,000 ns/op
                 contains·p0.95:   100,000 ns/op
                 contains·p0.99:   100,000 ns/op
                 contains·p0.999:  101,000 ns/op
                 contains·p0.9999: 2501,740 ns/op
                 contains·p1.00:   80000,000 ns/op



Result "org.example.Main.contains":
  N = 8301485
  mean =     25,169 ±(99.9%) 0,249 ns/op

  Histogram, ns/op:
    [     0,000,  10000,000) = 8301070 
    [ 10000,000,  20000,000) = 204 
    [ 20000,000,  30000,000) = 94 
    [ 30000,000,  40000,000) = 52 
    [ 40000,000,  50000,000) = 36 
    [ 50000,000,  60000,000) = 13 
    [ 60000,000,  70000,000) = 5 
    [ 70000,000,  80000,000) = 6 
    [ 80000,000,  90000,000) = 3 

  Percentiles, ns/op:
      p(0,0000) =        ≈ 0 ns/op
     p(50,0000) =        ≈ 0 ns/op
     p(90,0000) =    100,000 ns/op
     p(95,0000) =    100,000 ns/op
     p(99,0000) =    100,000 ns/op
     p(99,9000) =    101,000 ns/op
     p(99,9900) =   1600,000 ns/op
     p(99,9990) =  36540,196 ns/op
     p(99,9999) =  75172,688 ns/op
    p(100,0000) =  92672,000 ns/op


# JMH version: 1.35
# VM version: JDK 18.0.2, OpenJDK 64-Bit Server VM, 18.0.2+9-61
# VM invoker: C:\java\open\jdk-18.0.2\bin\java.exe
# VM options: -javaagent:C:\Program Files\JetBrains\IntelliJ IDEA 2022.3.2\lib\idea_rt.jar=57895:C:\Program Files\JetBrains\IntelliJ IDEA 2022.3.2\bin -Dfile.encoding=UTF-8 -Dsun.stdout.encoding=UTF-8 -Dsun.stderr.encoding=UTF-8
# Blackhole mode: compiler (auto-detected, use -Djmh.blackhole.autoDetect=false to disable)
# Warmup: 5 iterations, 10 s each
# Measurement: 5 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 1 thread, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.example.Main.startsWith

# Run progress: 83,33% complete, ETA 00:08:23
# Fork: 1 of 5
# Warmup Iteration   1: 23,325 ±(99.9%) 0,976 ns/op
# Warmup Iteration   2: 22,742 ±(99.9%) 0,249 ns/op
# Warmup Iteration   3: 23,905 ±(99.9%) 0,364 ns/op
# Warmup Iteration   4: 26,066 ±(99.9%) 1,304 ns/op
# Warmup Iteration   5: 25,623 ±(99.9%) 0,909 ns/op
Iteration   1: 24,096 ±(99.9%) 0,651 ns/op
                 startsWith·p0.00:   ≈ 0 ns/op
                 startsWith·p0.50:   ≈ 0 ns/op
                 startsWith·p0.90:   100,000 ns/op
                 startsWith·p0.95:   100,000 ns/op
                 startsWith·p0.99:   100,000 ns/op
                 startsWith·p0.999:  101,000 ns/op
                 startsWith·p0.9999: 3399,024 ns/op
                 startsWith·p1.00:   24800,000 ns/op

Iteration   2: 23,759 ±(99.9%) 0,778 ns/op
                 startsWith·p0.00:   ≈ 0 ns/op
                 startsWith·p0.50:   ≈ 0 ns/op
                 startsWith·p0.90:   100,000 ns/op
                 startsWith·p0.95:   100,000 ns/op
                 startsWith·p0.99:   100,000 ns/op
                 startsWith·p0.999:  101,000 ns/op
                 startsWith·p0.9999: 3469,514 ns/op
                 startsWith·p1.00:   56064,000 ns/op

Iteration   3: 22,792 ±(99.9%) 0,268 ns/op
                 startsWith·p0.00:   ≈ 0 ns/op
                 startsWith·p0.50:   ≈ 0 ns/op
                 startsWith·p0.90:   100,000 ns/op
                 startsWith·p0.95:   100,000 ns/op
                 startsWith·p0.99:   100,000 ns/op
                 startsWith·p0.999:  101,000 ns/op
                 startsWith·p0.9999: 400,000 ns/op
                 startsWith·p1.00:   12192,000 ns/op

Iteration   4: 23,123 ±(99.9%) 0,346 ns/op
                 startsWith·p0.00:   ≈ 0 ns/op
                 startsWith·p0.50:   ≈ 0 ns/op
                 startsWith·p0.90:   100,000 ns/op
                 startsWith·p0.95:   100,000 ns/op
                 startsWith·p0.99:   100,000 ns/op
                 startsWith·p0.999:  101,000 ns/op
                 startsWith·p0.9999: 300,000 ns/op
                 startsWith·p1.00:   24800,000 ns/op

Iteration   5: 24,644 ±(99.9%) 0,918 ns/op
                 startsWith·p0.00:   ≈ 0 ns/op
                 startsWith·p0.50:   ≈ 0 ns/op
                 startsWith·p0.90:   100,000 ns/op
                 startsWith·p0.95:   100,000 ns/op
                 startsWith·p0.99:   100,000 ns/op
                 startsWith·p0.999:  101,000 ns/op
                 startsWith·p0.9999: 1598,460 ns/op
                 startsWith·p1.00:   37184,000 ns/op


# Run progress: 86,67% complete, ETA 00:06:43
# Fork: 2 of 5
# Warmup Iteration   1: 22,538 ±(99.9%) 0,330 ns/op
# Warmup Iteration   2: 22,551 ±(99.9%) 0,239 ns/op
# Warmup Iteration   3: 23,454 ±(99.9%) 0,822 ns/op
# Warmup Iteration   4: 22,747 ±(99.9%) 0,462 ns/op
# Warmup Iteration   5: 22,849 ±(99.9%) 0,249 ns/op
Iteration   1: 23,592 ±(99.9%) 0,889 ns/op
                 startsWith·p0.00:   ≈ 0 ns/op
                 startsWith·p0.50:   ≈ 0 ns/op
                 startsWith·p0.90:   100,000 ns/op
                 startsWith·p0.95:   100,000 ns/op
                 startsWith·p0.99:   100,000 ns/op
                 startsWith·p0.999:  101,000 ns/op
                 startsWith·p0.9999: 1383,731 ns/op
                 startsWith·p1.00:   56896,000 ns/op

Iteration   2: 23,912 ±(99.9%) 0,530 ns/op
                 startsWith·p0.00:   ≈ 0 ns/op
                 startsWith·p0.50:   ≈ 0 ns/op
                 startsWith·p0.90:   100,000 ns/op
                 startsWith·p0.95:   100,000 ns/op
                 startsWith·p0.99:   100,000 ns/op
                 startsWith·p0.999:  101,000 ns/op
                 startsWith·p0.9999: 1149,470 ns/op
                 startsWith·p1.00:   29600,000 ns/op

Iteration   3: 26,654 ±(99.9%) 1,808 ns/op
                 startsWith·p0.00:   ≈ 0 ns/op
                 startsWith·p0.50:   ≈ 0 ns/op
                 startsWith·p0.90:   100,000 ns/op
                 startsWith·p0.95:   100,000 ns/op
                 startsWith·p0.99:   100,000 ns/op
                 startsWith·p0.999:  101,000 ns/op
                 startsWith·p0.9999: 11392,000 ns/op
                 startsWith·p1.00:   68480,000 ns/op

Iteration   4: 29,303 ±(99.9%) 2,782 ns/op
                 startsWith·p0.00:   ≈ 0 ns/op
                 startsWith·p0.50:   ≈ 0 ns/op
                 startsWith·p0.90:   100,000 ns/op
                 startsWith·p0.95:   100,000 ns/op
                 startsWith·p0.99:   100,000 ns/op
                 startsWith·p0.999:  101,000 ns/op
                 startsWith·p0.9999: 19769,885 ns/op
                 startsWith·p1.00:   72448,000 ns/op

Iteration   5: 23,683 ±(99.9%) 0,405 ns/op
                 startsWith·p0.00:   ≈ 0 ns/op
                 startsWith·p0.50:   ≈ 0 ns/op
                 startsWith·p0.90:   100,000 ns/op
                 startsWith·p0.95:   100,000 ns/op
                 startsWith·p0.99:   100,000 ns/op
                 startsWith·p0.999:  101,000 ns/op
                 startsWith·p0.9999: 300,000 ns/op
                 startsWith·p1.00:   29600,000 ns/op


# Run progress: 90,00% complete, ETA 00:05:02
# Fork: 3 of 5
# Warmup Iteration   1: 23,165 ±(99.9%) 0,648 ns/op
# Warmup Iteration   2: 26,756 ±(99.9%) 1,879 ns/op
# Warmup Iteration   3: 24,345 ±(99.9%) 0,704 ns/op
# Warmup Iteration   4: 25,152 ±(99.9%) 1,441 ns/op
# Warmup Iteration   5: 27,571 ±(99.9%) 2,122 ns/op
Iteration   1: 27,180 ±(99.9%) 2,039 ns/op
                 startsWith·p0.00:   ≈ 0 ns/op
                 startsWith·p0.50:   ≈ 0 ns/op
                 startsWith·p0.90:   100,000 ns/op
                 startsWith·p0.95:   100,000 ns/op
                 startsWith·p0.99:   100,000 ns/op
                 startsWith·p0.999:  101,000 ns/op
                 startsWith·p0.9999: 13057,208 ns/op
                 startsWith·p1.00:   67840,000 ns/op

Iteration   2: 23,803 ±(99.9%) 0,607 ns/op
                 startsWith·p0.00:   ≈ 0 ns/op
                 startsWith·p0.50:   ≈ 0 ns/op
                 startsWith·p0.90:   100,000 ns/op
                 startsWith·p0.95:   100,000 ns/op
                 startsWith·p0.99:   100,000 ns/op
                 startsWith·p0.999:  101,000 ns/op
                 startsWith·p0.9999: 300,000 ns/op
                 startsWith·p1.00:   40192,000 ns/op

Iteration   3: 26,623 ±(99.9%) 1,686 ns/op
                 startsWith·p0.00:   ≈ 0 ns/op
                 startsWith·p0.50:   ≈ 0 ns/op
                 startsWith·p0.90:   100,000 ns/op
                 startsWith·p0.95:   100,000 ns/op
                 startsWith·p0.99:   100,000 ns/op
                 startsWith·p0.999:  101,000 ns/op
                 startsWith·p0.9999: 16331,363 ns/op
                 startsWith·p1.00:   69120,000 ns/op

Iteration   4: 27,663 ±(99.9%) 2,242 ns/op
                 startsWith·p0.00:   ≈ 0 ns/op
                 startsWith·p0.50:   ≈ 0 ns/op
                 startsWith·p0.90:   100,000 ns/op
                 startsWith·p0.95:   100,000 ns/op
                 startsWith·p0.99:   100,000 ns/op
                 startsWith·p0.999:  101,000 ns/op
                 startsWith·p0.9999: 17470,662 ns/op
                 startsWith·p1.00:   80896,000 ns/op

Iteration   5: 25,483 ±(99.9%) 1,269 ns/op
                 startsWith·p0.00:   ≈ 0 ns/op
                 startsWith·p0.50:   ≈ 0 ns/op
                 startsWith·p0.90:   100,000 ns/op
                 startsWith·p0.95:   100,000 ns/op
                 startsWith·p0.99:   100,000 ns/op
                 startsWith·p0.999:  101,000 ns/op
                 startsWith·p0.9999: 355,599 ns/op
                 startsWith·p1.00:   60736,000 ns/op


# Run progress: 93,33% complete, ETA 00:03:21
# Fork: 4 of 5
# Warmup Iteration   1: 23,004 ±(99.9%) 0,345 ns/op
# Warmup Iteration   2: 25,532 ±(99.9%) 1,605 ns/op
# Warmup Iteration   3: 26,740 ±(99.9%) 1,864 ns/op
# Warmup Iteration   4: 23,807 ±(99.9%) 0,418 ns/op
# Warmup Iteration   5: 26,401 ±(99.9%) 1,675 ns/op
Iteration   1: 24,009 ±(99.9%) 0,688 ns/op
                 startsWith·p0.00:   ≈ 0 ns/op
                 startsWith·p0.50:   ≈ 0 ns/op
                 startsWith·p0.90:   100,000 ns/op
                 startsWith·p0.95:   100,000 ns/op
                 startsWith·p0.99:   100,000 ns/op
                 startsWith·p0.999:  101,000 ns/op
                 startsWith·p0.9999: 320,354 ns/op
                 startsWith·p1.00:   56256,000 ns/op

Iteration   2: 26,947 ±(99.9%) 1,897 ns/op
                 startsWith·p0.00:   ≈ 0 ns/op
                 startsWith·p0.50:   ≈ 0 ns/op
                 startsWith·p0.90:   100,000 ns/op
                 startsWith·p0.95:   100,000 ns/op
                 startsWith·p0.99:   100,000 ns/op
                 startsWith·p0.999:  101,000 ns/op
                 startsWith·p0.9999: 13314,826 ns/op
                 startsWith·p1.00:   89344,000 ns/op

Iteration   3: 26,109 ±(99.9%) 1,505 ns/op
                 startsWith·p0.00:   ≈ 0 ns/op
                 startsWith·p0.50:   ≈ 0 ns/op
                 startsWith·p0.90:   100,000 ns/op
                 startsWith·p0.95:   100,000 ns/op
                 startsWith·p0.99:   100,000 ns/op
                 startsWith·p0.999:  101,000 ns/op
                 startsWith·p0.9999: 12493,568 ns/op
                 startsWith·p1.00:   53248,000 ns/op

Iteration   4: 28,206 ±(99.9%) 2,189 ns/op
                 startsWith·p0.00:   ≈ 0 ns/op
                 startsWith·p0.50:   ≈ 0 ns/op
                 startsWith·p0.90:   100,000 ns/op
                 startsWith·p0.95:   100,000 ns/op
                 startsWith·p0.99:   100,000 ns/op
                 startsWith·p0.999:  101,000 ns/op
                 startsWith·p0.9999: 18301,850 ns/op
                 startsWith·p1.00:   98944,000 ns/op

Iteration   5: 24,209 ±(99.9%) 0,949 ns/op
                 startsWith·p0.00:   ≈ 0 ns/op
                 startsWith·p0.50:   ≈ 0 ns/op
                 startsWith·p0.90:   100,000 ns/op
                 startsWith·p0.95:   100,000 ns/op
                 startsWith·p0.99:   100,000 ns/op
                 startsWith·p0.999:  101,000 ns/op
                 startsWith·p0.9999: 300,000 ns/op
                 startsWith·p1.00:   50496,000 ns/op


# Run progress: 96,67% complete, ETA 00:01:40
# Fork: 5 of 5
# Warmup Iteration   1: 23,190 ±(99.9%) 0,603 ns/op
# Warmup Iteration   2: 24,180 ±(99.9%) 0,837 ns/op
# Warmup Iteration   3: 24,085 ±(99.9%) 0,776 ns/op
# Warmup Iteration   4: 23,383 ±(99.9%) 0,533 ns/op
# Warmup Iteration   5: 22,545 ±(99.9%) 0,252 ns/op
Iteration   1: 23,105 ±(99.9%) 0,596 ns/op
                 startsWith·p0.00:   ≈ 0 ns/op
                 startsWith·p0.50:   ≈ 0 ns/op
                 startsWith·p0.90:   100,000 ns/op
                 startsWith·p0.95:   100,000 ns/op
                 startsWith·p0.99:   100,000 ns/op
                 startsWith·p0.999:  101,000 ns/op
                 startsWith·p0.9999: 585,790 ns/op
                 startsWith·p1.00:   36160,000 ns/op

Iteration   2: 22,708 ±(99.9%) 0,310 ns/op
                 startsWith·p0.00:   ≈ 0 ns/op
                 startsWith·p0.50:   ≈ 0 ns/op
                 startsWith·p0.90:   100,000 ns/op
                 startsWith·p0.95:   100,000 ns/op
                 startsWith·p0.99:   100,000 ns/op
                 startsWith·p0.999:  101,000 ns/op
                 startsWith·p0.9999: 687,820 ns/op
                 startsWith·p1.00:   18272,000 ns/op

Iteration   3: 22,705 ±(99.9%) 0,342 ns/op
                 startsWith·p0.00:   ≈ 0 ns/op
                 startsWith·p0.50:   ≈ 0 ns/op
                 startsWith·p0.90:   100,000 ns/op
                 startsWith·p0.95:   100,000 ns/op
                 startsWith·p0.99:   100,000 ns/op
                 startsWith·p0.999:  101,000 ns/op
                 startsWith·p0.9999: 101,000 ns/op
                 startsWith·p1.00:   15792,000 ns/op

Iteration   4: 23,519 ±(99.9%) 0,261 ns/op
                 startsWith·p0.00:   ≈ 0 ns/op
                 startsWith·p0.50:   ≈ 0 ns/op
                 startsWith·p0.90:   100,000 ns/op
                 startsWith·p0.95:   100,000 ns/op
                 startsWith·p0.99:   100,000 ns/op
                 startsWith·p0.999:  101,000 ns/op
                 startsWith·p0.9999: 200,000 ns/op
                 startsWith·p1.00:   7696,000 ns/op

Iteration   5: 22,952 ±(99.9%) 0,762 ns/op
                 startsWith·p0.00:   ≈ 0 ns/op
                 startsWith·p0.50:   ≈ 0 ns/op
                 startsWith·p0.90:   100,000 ns/op
                 startsWith·p0.95:   100,000 ns/op
                 startsWith·p0.99:   100,000 ns/op
                 startsWith·p0.999:  101,000 ns/op
                 startsWith·p0.9999: 891,020 ns/op
                 startsWith·p1.00:   56256,000 ns/op



Result "org.example.Main.startsWith":
  N = 8779247
  mean =     24,729 ±(99.9%) 0,243 ns/op

  Histogram, ns/op:
    [     0,000,  10000,000) = 8778810 
    [ 10000,000,  20000,000) = 193 
    [ 20000,000,  30000,000) = 104 
    [ 30000,000,  40000,000) = 71 
    [ 40000,000,  50000,000) = 40 
    [ 50000,000,  60000,000) = 15 
    [ 60000,000,  70000,000) = 8 
    [ 70000,000,  80000,000) = 2 
    [ 80000,000,  90000,000) = 3 

  Percentiles, ns/op:
      p(0,0000) =        ≈ 0 ns/op
     p(50,0000) =        ≈ 0 ns/op
     p(90,0000) =    100,000 ns/op
     p(95,0000) =    100,000 ns/op
     p(99,0000) =    100,000 ns/op
     p(99,9000) =    101,000 ns/op
     p(99,9900) =   1698,150 ns/op
     p(99,9990) =  36570,563 ns/op
     p(99,9999) =  67981,281 ns/op
    p(100,0000) =  98944,000 ns/op


# JMH version: 1.35
# VM version: JDK 18.0.2, OpenJDK 64-Bit Server VM, 18.0.2+9-61
# VM invoker: C:\java\open\jdk-18.0.2\bin\java.exe
# VM options: -javaagent:C:\Program Files\JetBrains\IntelliJ IDEA 2022.3.2\lib\idea_rt.jar=57895:C:\Program Files\JetBrains\IntelliJ IDEA 2022.3.2\bin -Dfile.encoding=UTF-8 -Dsun.stdout.encoding=UTF-8 -Dsun.stderr.encoding=UTF-8
# Blackhole mode: compiler (auto-detected, use -Djmh.blackhole.autoDetect=false to disable)
# Warmup: <none>
# Measurement: 1 iterations, single-shot each
# Timeout: 10 min per iteration
# Threads: 1 thread
# Benchmark mode: Single shot invocation time
# Benchmark: org.example.Main.contains

# Run progress: 100,00% complete, ETA 00:00:00
# Fork: 1 of 5
Iteration   1: 4901,000 ns/op

# Run progress: 100,00% complete, ETA 00:00:00
# Fork: 2 of 5
Iteration   1: 5000,000 ns/op

# Run progress: 100,00% complete, ETA 00:00:00
# Fork: 3 of 5
Iteration   1: 4700,000 ns/op

# Run progress: 100,00% complete, ETA 00:00:00
# Fork: 4 of 5
Iteration   1: 4800,000 ns/op

# Run progress: 100,00% complete, ETA 00:00:00
# Fork: 5 of 5
Iteration   1: 5000,000 ns/op


Result "org.example.Main.contains":
  N = 5
  mean =   4880,200 ±(99.9%) 502,213 ns/op

  Histogram, ns/op:
    [4700,000, 4725,000) = 1 
    [4725,000, 4750,000) = 0 
    [4750,000, 4775,000) = 0 
    [4775,000, 4800,000) = 0 
    [4800,000, 4825,000) = 1 
    [4825,000, 4850,000) = 0 
    [4850,000, 4875,000) = 0 
    [4875,000, 4900,000) = 0 
    [4900,000, 4925,000) = 1 
    [4925,000, 4950,000) = 0 
    [4950,000, 4975,000) = 0 

  Percentiles, ns/op:
      p(0,0000) =   4700,000 ns/op
     p(50,0000) =   4901,000 ns/op
     p(90,0000) =   5000,000 ns/op
     p(95,0000) =   5000,000 ns/op
     p(99,0000) =   5000,000 ns/op
     p(99,9000) =   5000,000 ns/op
     p(99,9900) =   5000,000 ns/op
     p(99,9990) =   5000,000 ns/op
     p(99,9999) =   5000,000 ns/op
    p(100,0000) =   5000,000 ns/op


# JMH version: 1.35
# VM version: JDK 18.0.2, OpenJDK 64-Bit Server VM, 18.0.2+9-61
# VM invoker: C:\java\open\jdk-18.0.2\bin\java.exe
# VM options: -javaagent:C:\Program Files\JetBrains\IntelliJ IDEA 2022.3.2\lib\idea_rt.jar=57895:C:\Program Files\JetBrains\IntelliJ IDEA 2022.3.2\bin -Dfile.encoding=UTF-8 -Dsun.stdout.encoding=UTF-8 -Dsun.stderr.encoding=UTF-8
# Blackhole mode: compiler (auto-detected, use -Djmh.blackhole.autoDetect=false to disable)
# Warmup: <none>
# Measurement: 1 iterations, single-shot each
# Timeout: 10 min per iteration
# Threads: 1 thread
# Benchmark mode: Single shot invocation time
# Benchmark: org.example.Main.startsWith

# Run progress: 100,00% complete, ETA 00:00:00
# Fork: 1 of 5
Iteration   1: 4000,000 ns/op

# Run progress: 100,00% complete, ETA 00:00:00
# Fork: 2 of 5
Iteration   1: 4000,000 ns/op

# Run progress: 100,00% complete, ETA 00:00:00
# Fork: 3 of 5
Iteration   1: 3900,000 ns/op

# Run progress: 100,00% complete, ETA 00:00:00
# Fork: 4 of 5
Iteration   1: 4200,000 ns/op

# Run progress: 100,00% complete, ETA 00:00:00
# Fork: 5 of 5
Iteration   1: 4200,000 ns/op


Result "org.example.Main.startsWith":
  N = 5
  mean =   4060,000 ±(99.9%) 516,618 ns/op

  Histogram, ns/op:
    [3900,000, 3925,000) = 1 
    [3925,000, 3950,000) = 0 
    [3950,000, 3975,000) = 0 
    [3975,000, 4000,000) = 0 
    [4000,000, 4025,000) = 2 
    [4025,000, 4050,000) = 0 
    [4050,000, 4075,000) = 0 
    [4075,000, 4100,000) = 0 
    [4100,000, 4125,000) = 0 
    [4125,000, 4150,000) = 0 
    [4150,000, 4175,000) = 0 

  Percentiles, ns/op:
      p(0,0000) =   3900,000 ns/op
     p(50,0000) =   4000,000 ns/op
     p(90,0000) =   4200,000 ns/op
     p(95,0000) =   4200,000 ns/op
     p(99,0000) =   4200,000 ns/op
     p(99,9000) =   4200,000 ns/op
     p(99,9900) =   4200,000 ns/op
     p(99,9990) =   4200,000 ns/op
     p(99,9999) =   4200,000 ns/op
    p(100,0000) =   4200,000 ns/op


# Run complete. Total time: 00:50:29

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

NOTE: Current JVM experimentally supports Compiler Blackholes, and they are in use. Please exercise
extra caution when trusting the results, look into the generated code to check the benchmark still
works, and factor in a small probability of new VM bugs. Additionally, while comparisons between
different JVMs are already problematic, the performance difference caused by different Blackhole
modes can be very significant. Please make sure you use the consistent Blackhole mode for comparisons.

Benchmark                             Mode      Cnt      Score     Error   Units
Main.contains                        thrpt       25      0,412 ±   0,023  ops/ns
Main.startsWith                      thrpt       25      0,472 ±   0,006  ops/ns
Main.contains                         avgt       25      2,354 ±   0,064   ns/op
Main.startsWith                       avgt       25      2,164 ±   0,023   ns/op
Main.contains                       sample  8301485     25,169 ±   0,249   ns/op
Main.contains:contains·p0.00        sample                 ≈ 0             ns/op
Main.contains:contains·p0.50        sample                 ≈ 0             ns/op
Main.contains:contains·p0.90        sample             100,000             ns/op
Main.contains:contains·p0.95        sample             100,000             ns/op
Main.contains:contains·p0.99        sample             100,000             ns/op
Main.contains:contains·p0.999       sample             101,000             ns/op
Main.contains:contains·p0.9999      sample            1600,000             ns/op
Main.contains:contains·p1.00        sample           92672,000             ns/op
Main.startsWith                     sample  8779247     24,729 ±   0,243   ns/op
Main.startsWith:startsWith·p0.00    sample                 ≈ 0             ns/op
Main.startsWith:startsWith·p0.50    sample                 ≈ 0             ns/op
Main.startsWith:startsWith·p0.90    sample             100,000             ns/op
Main.startsWith:startsWith·p0.95    sample             100,000             ns/op
Main.startsWith:startsWith·p0.99    sample             100,000             ns/op
Main.startsWith:startsWith·p0.999   sample             101,000             ns/op
Main.startsWith:startsWith·p0.9999  sample            1698,150             ns/op
Main.startsWith:startsWith·p1.00    sample           98944,000             ns/op
Main.contains                           ss        5   4880,200 ± 502,213   ns/op
Main.startsWith                         ss        5   4060,000 ± 516,618   ns/op

Process finished with exit code 0

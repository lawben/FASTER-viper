set(BENCHMARK_HEADERS
  file.h
)

set(BENCHMARK_SOURCES
)

ADD_FASTER_BENCHMARK(faster-benchmark)

add_executable(process_ycsb process_ycsb.cc)

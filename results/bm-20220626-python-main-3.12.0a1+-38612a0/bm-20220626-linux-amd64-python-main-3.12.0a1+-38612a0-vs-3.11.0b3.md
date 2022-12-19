| Benchmark               | bm-20220601-linux-amd64-python-main-3.11.0b3-eb0004c | bm-20220626-linux-amd64-python-main-3.12.0a1+-38612a0 |
|-------------------------|:----------------------------------------------------:|:-----------------------------------------------------:|
| 2to3                    | 256 ms                                               | 249 ms: 1.03x faster                                  |
| chameleon               | 6.67 ms                                              | 6.45 ms: 1.03x faster                                 |
| chaos                   | 66.9 ms                                              | 63.8 ms: 1.05x faster                                 |
| crypto_pyaes            | 73.1 ms                                              | 73.7 ms: 1.01x slower                                 |
| deltablue               | 3.62 ms                                              | 3.24 ms: 1.12x faster                                 |
| django_template         | 32.9 ms                                              | 31.6 ms: 1.04x faster                                 |
| dulwich_log             | 63.1 ms                                              | 61.7 ms: 1.02x faster                                 |
| fannkuch                | 372 ms                                               | 376 ms: 1.01x slower                                  |
| float                   | 72.9 ms                                              | 71.1 ms: 1.02x faster                                 |
| go                      | 137 ms                                               | 128 ms: 1.06x faster                                  |
| hexiom                  | 6.32 ms                                              | 5.94 ms: 1.06x faster                                 |
| json_dumps              | 12.5 ms                                              | 12.0 ms: 1.04x faster                                 |
| json_loads              | 24.4 us                                              | 24.5 us: 1.00x slower                                 |
| logging_format          | 6.44 us                                              | 6.40 us: 1.01x faster                                 |
| logging_silent          | 101 ns                                               | 89.6 ns: 1.13x faster                                 |
| logging_simple          | 5.95 us                                              | 5.77 us: 1.03x faster                                 |
| mako                    | 9.82 ms                                              | 9.46 ms: 1.04x faster                                 |
| meteor_contest          | 104 ms                                               | 102 ms: 1.02x faster                                  |
| nbody                   | 90.6 ms                                              | 94.8 ms: 1.05x slower                                 |
| nqueens                 | 80.7 ms                                              | 82.2 ms: 1.02x slower                                 |
| pathlib                 | 17.9 ms                                              | 18.1 ms: 1.01x slower                                 |
| pickle                  | 9.55 us                                              | 10.2 us: 1.07x slower                                 |
| pickle_dict             | 25.6 us                                              | 30.1 us: 1.18x slower                                 |
| pickle_list             | 4.33 us                                              | 4.15 us: 1.04x faster                                 |
| pickle_pure_python      | 302 us                                               | 294 us: 1.03x faster                                  |
| pidigits                | 194 ms                                               | 194 ms: 1.00x faster                                  |
| pycparser               | 1.10 sec                                             | 1.05 sec: 1.05x faster                                |
| pyflate                 | 411 ms                                               | 400 ms: 1.03x faster                                  |
| python_startup          | 8.33 ms                                              | 8.26 ms: 1.01x faster                                 |
| python_startup_no_site  | 6.17 ms                                              | 6.10 ms: 1.01x faster                                 |
| raytrace                | 292 ms                                               | 279 ms: 1.05x faster                                  |
| regex_compile           | 135 ms                                               | 128 ms: 1.06x faster                                  |
| regex_dna               | 192 ms                                               | 208 ms: 1.09x slower                                  |
| regex_effbot            | 2.92 ms                                              | 3.61 ms: 1.24x slower                                 |
| regex_v8                | 21.2 ms                                              | 21.3 ms: 1.00x slower                                 |
| richards                | 46.5 ms                                              | 45.4 ms: 1.02x faster                                 |
| scimark_fft             | 317 ms                                               | 304 ms: 1.04x faster                                  |
| scimark_lu              | 107 ms                                               | 104 ms: 1.03x faster                                  |
| scimark_monte_carlo     | 66.0 ms                                              | 62.4 ms: 1.06x faster                                 |
| scimark_sor             | 115 ms                                               | 110 ms: 1.05x faster                                  |
| scimark_sparse_mat_mult | 4.54 ms                                              | 3.89 ms: 1.17x faster                                 |
| spectral_norm           | 97.6 ms                                              | 92.8 ms: 1.05x faster                                 |
| sqlite_synth            | 2.49 us                                              | 2.57 us: 1.03x slower                                 |
| sympy_expand            | 467 ms                                               | 451 ms: 1.04x faster                                  |
| sympy_integrate         | 20.5 ms                                              | 20.2 ms: 1.02x faster                                 |
| sympy_str               | 284 ms                                               | 277 ms: 1.03x faster                                  |
| thrift                  | 759 us                                               | 745 us: 1.02x faster                                  |
| tornado_http            | 93.8 ms                                              | 92.1 ms: 1.02x faster                                 |
| unpack_sequence         | 43.4 ns                                              | 42.8 ns: 1.02x faster                                 |
| unpickle_pure_python    | 228 us                                               | 198 us: 1.15x faster                                  |
| xml_etree_generate      | 76.3 ms                                              | 75.0 ms: 1.02x faster                                 |
| xml_etree_iterparse     | 105 ms                                               | 103 ms: 1.02x faster                                  |
| xml_etree_parse         | 156 ms                                               | 155 ms: 1.00x faster                                  |
| xml_etree_process       | 53.8 ms                                              | 52.0 ms: 1.03x faster                                 |
| Geometric mean          | (ref)                                                | 1.02x faster                                          |

Benchmark hidden because not significant (6): html5lib, json, sympy_sum, telco, unpickle, unpickle_list
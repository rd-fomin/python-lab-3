#### Запуск pytest  с замером покрытия кода
```
pytest --cov .
```
#### Результат pytest
```
=========================================================== test session starts ============================================================
platform win32 -- Python 3.9.0, pytest-4.3.1, py-1.9.0, pluggy-0.13.1
benchmark: 3.2.1 (defaults: timer=time.perf_counter disable_gc=False min_rounds=5 min_time=0.000005 max_time=1.0 calibration_precision=10 war
mup=False warmup_iterations=100000)
rootdir: C:\Users\rfomin\Downloads\python-lab-3, inifile:
plugins: benchmark-3.2.1, cov-2.6.1, grpc-0.7.0
collected 7 items                                                                                                                           

one_hot_encoder\test_one_hot_encoder.py ....                                                                                          [ 57%]
what_is_year_now\test_what_is_year_now.py ...                                                                                         [100%]

----------- coverage: platform win32, python 3.9.0-final-0 -----------
Name                                        Stmts   Miss  Cover
---------------------------------------------------------------
one_hot_encoder\one_hot_encoder.py             21      7    67%
one_hot_encoder\test_one_hot_encoder.py        22      1    95%
what_is_year_now\test_what_is_year_now.py      27      0   100%
what_is_year_now\what_is_year_now.py           19      0   100%
---------------------------------------------------------------
TOTAL                                          89      8    91%


========================================================= 7 passed in 0.26 seconds =========================================================
```

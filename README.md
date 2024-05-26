# ml-epiphany
Data-driven insights and discoveries. 

```
for package in `cat requirements.txt `; do ./python -m pip download $package  -d pip-packages-3.10/ --cache-dir pip-packages-cache-3.10/ && echo $package >> success || echo $package >> failed ; done
```

# BlackSwanAPI Client

### Building Instructions
```
git clone https://github.com/JayjeetAtGithub/blackswan-client
cd blackswan-client/
pip install .
```

### Example Usage:

```
blkswan.get_no_of_reps(
    machine_predicate = {
        "blockdevices": "nvme0n1"
    }, 
    benchmark_predicate = { 
        "testname": "SP",
        "dvfs": "yes",
        "socket": 0
     }, param = 'mops_total', test = 'npb_cpu_mt'))
```

Look into `usage/` for more example usage.
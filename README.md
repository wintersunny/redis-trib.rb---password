# redis-trib.rb---password

Adding support parameters  [ --password | host:port:password ] in the script redis-trib.rb

脚本redis-trib.rb中新增支持参数--password 或 host:port:password，建议使用参数--password

例子（for example）：
$ redis-trib.rb check --password foobared 127.0.0.1:6380
>>> Performing Cluster Check (using node 127.0.0.1:6380)
M: 61bcdc51681fc11d3e3151df691ac78d164c2d86 127.0.0.1:6380
   slots:0-5460 (5461 slots) master
   0 additional replica(s)
M: 3f76672dd54bef34d85a582fea4b4c3c2093c5ae 127.0.0.1:6379
   slots:10923-16383 (5461 slots) master
   0 additional replica(s)
M: df99c632f4336c3f34094c44dc49b3dcd5498fac 127.0.0.1:6381
   slots:5461-10922 (5462 slots) master
   0 additional replica(s)
[OK] All nodes agree about slots configuration.
>>> Check for open slots...
>>> Check slots coverage...
[OK] All 16384 slots covered.

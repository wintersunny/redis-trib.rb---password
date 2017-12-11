    # redis-trib.rb---password
    
    Adding support parameters  [ --password | host:port:password ] in the script redis-trib.rb
    for example：
    $ redis-trib.rb check --password foobared 127.0.0.1:6380
    
    脚本redis-trib.rb中新增支持参数--password 或 host:port:password，建议使用参数--password
    例子：
    $ redis-trib.rb check --password foobared 127.0.0.1:6380

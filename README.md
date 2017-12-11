    if you meet a problem like '[ERR] Sorry, can't connect to node ...', 
    when you try to create a redis cluster , 
    maybe the reason is that the script redis-trib.rb don't support the auth , 
    you could try this script with parameter [--password] .
        
    # redis-trib.rb---password
    
    Adding support parameters  [ --password | host:port:password ] in the script redis-trib.rb
    for example：
    $ redis-trib.rb check --password foobared 127.0.0.1:6380
    
    脚本redis-trib.rb中新增支持参数--password 或 host:port:password，建议使用参数--password
    例子：
    $ redis-trib.rb check --password foobared 127.0.0.1:6380

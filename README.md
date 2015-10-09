# python IP地址解析库 

>>> import ipaddr 

dir(ipaddr)

['AddressValueError', 'Bytes', 'CollapseAddrList', 'IPAddress', 'IPNetwork', 'IPV4LENGTH', 'IPV6LENGTH', 'IPv4Address', 'IPv4Network', 'IPv6Address', 'IPv6Network', 'NetmaskValueError', '_BaseIP', '_BaseNet', '_BaseV4', '_BaseV6', '_IPAddrBase', '__builtins__', '__doc__', '__file__', '__name__', '__package__', '__version__', '_collapse_address_list_recursive', '_count_righthand_zero_bits', '_find_address_range', '_get_prefix_length', 'collapse_address_list', 'get_mixed_type_key', 'struct', 'summarize_address_range', 'v4_int_to_packed', 'v6_int_to_packed']


a=ipaddr.IPv4Network("10.10.255.254/16")
b=a.masked()
str(b)
'10.10.0.0/16'

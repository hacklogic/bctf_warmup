# bctf_warmup
http://bctf.cn/#/question/550cd3d681cc227624560751
<code>c=0x1e04304936215de8e21965cfca9c245b1a8f38339875d36779c0f123c475bc24d5eef50e7d9ff5830e80c62e8083ec55f27456c80b0ab26546b9aeb8af30e82b650690a2ed7ea407dcd094ab9c9d3d25a93b2140dcebae1814610302896e67f3ae37d108cd029fae6362ea7ac1168974c1a747ec9173799e1107e7a56d783660418ebdf6898d7037cea25867093216c2c702ef3eef71f694a6063f5f0f1179c8a2afe9898ae8dec5bb393cdffa3a52a297cd96d1ea602309ecf47cd009829b44ed3100cf6194510c53c25ca7435f60ce5f4f614cdd2c63756093b848a70aade002d6bc8f316c9e5503f32d39a56193d1d92b697b48f5aa43417631846824b5e86</code>
http://dl.bctf.cn/warmup-c6aa398e4f3e72bc2ea2742ae528ed79.pub.xz


#solution

1. Download warmup-c6aa398e4f3e72bc2ea2742ae528ed79.pub.xz 
2. extract the file:
	xz -d warmup-c6aa398e4f3e72bc2ea2742ae528ed79.pub.xz
  cat warmup-c6aa398e4f3e72bc2ea2742ae528ed79.pub
it's public key:
-----BEGIN PUBLIC KEY-----
MIICIjANBgkqhkiG9w0BAQEFAAOCAg8AMIICCgKCAQEDZxmNa1YU6VgTrdjyKkcX
vHK+HqvZM9G4aUT9t1uO0jC+YtfRtp0iIJXBKMhvggEuyxFhkf2dAYptAvhNsnvF
GiEwfchvS/dxxpHBQ+Wr5Um1vS1usaIf1icOfhtI/gYR+7LhsLNSTm9N6LTko0Xa
RKE96CW3JgjbbHxKQLeCZubIe7/e9rSDgdScRQeli81Ht21ktFkIsVi9frxNrLCx
z9bCwZV09A6y79Dp4Q3HAFytObyvUrnqw4czaNaQMcXnJGhKRPBo79HT3Altm11k
EeWL3uQ+RrmaDQSUudsoGVr5Aa/xMNSm4gPa0I2lf6fkAmKlutsqMj7aKLRGlqsw
XQKCAQEA85Wdl44C658G3vPzNdj4r9dgmVHdrGC3FLbCKvD6kS8hCzQga9JKlgHH
jfSgJ18Qf9OrVS2VBX65NOcb3c1wRcJLGFh7jI/PWt1MXYPwx3yU3JxQy+Q44rZ7
r9MWM7aq8XgdkMOtbwPQN7MyGAGyNUbUg+Z+JgZ/eyI0fdvAwtWSzoFMv138zBQU
N/FOCzmQ+IBh5fC65fAeP6cNsOlgXnz9V16cge/uxSnDP9kDeiD9is1ROsljd2gx
PmP5g4rjURzdCporUW8hSMjUdaNgoGNZRJc57s0lGrtCsBRXPkOfL6RXNVeyVpn/
wR5jHOjul1qG5+JyvPX3apNFA0j+Pw==

3.openssl rsa -in warmup-c6aa398e4f3e72bc2ea2742ae528ed79.pub -pubin -text -modulus

<code>
Public-Key: (2050 bit)
Modulus:
    03:67:19:8d:6b:56:14:e9:58:13:ad:d8:f2:2a:47:
    17:bc:72:be:1e:ab:d9:33:d1:b8:69:44:fd:b7:5b:
    8e:d2:30:be:62:d7:d1:b6:9d:22:20:95:c1:28:c8:
    6f:82:01:2e:cb:11:61:91:fd:9d:01:8a:6d:02:f8:
    4d:b2:7b:c5:1a:21:30:7d:c8:6f:4b:f7:71:c6:91:
    c1:43:e5:ab:e5:49:b5:bd:2d:6e:b1:a2:1f:d6:27:
    0e:7e:1b:48:fe:06:11:fb:b2:e1:b0:b3:52:4e:6f:
    4d:e8:b4:e4:a3:45:da:44:a1:3d:e8:25:b7:26:08:
    db:6c:7c:4a:40:b7:82:66:e6:c8:7b:bf:de:f6:b4:
    83:81:d4:9c:45:07:a5:8b:cd:47:b7:6d:64:b4:59:
    08:b1:58:bd:7e:bc:4d:ac:b0:b1:cf:d6:c2:c1:95:
    74:f4:0e:b2:ef:d0:e9:e1:0d:c7:00:5c:ad:39:bc:
    af:52:b9:ea:c3:87:33:68:d6:90:31:c5:e7:24:68:
    4a:44:f0:68:ef:d1:d3:dc:09:6d:9b:5d:64:11:e5:
    8b:de:e4:3e:46:b9:9a:0d:04:94:b9:db:28:19:5a:
    f9:01:af:f1:30:d4:a6:e2:03:da:d0:8d:a5:7f:a7:
    e4:02:62:a5:ba:db:2a:32:3e:da:28:b4:46:96:ab:
    30:5d
Exponent:
    00:f3:95:9d:97:8e:02:eb:9f:06:de:f3:f3:35:d8:
    f8:af:d7:60:99:51:dd:ac:60:b7:14:b6:c2:2a:f0:
    fa:91:2f:21:0b:34:20:6b:d2:4a:96:01:c7:8d:f4:
    a0:27:5f:10:7f:d3:ab:55:2d:95:05:7e:b9:34:e7:
    1b:dd:cd:70:45:c2:4b:18:58:7b:8c:8f:cf:5a:dd:
    4c:5d:83:f0:c7:7c:94:dc:9c:50:cb:e4:38:e2:b6:
    7b:af:d3:16:33:b6:aa:f1:78:1d:90:c3:ad:6f:03:
    d0:37:b3:32:18:01:b2:35:46:d4:83:e6:7e:26:06:
    7f:7b:22:34:7d:db:c0:c2:d5:92:ce:81:4c:bf:5d:
    fc:cc:14:14:37:f1:4e:0b:39:90:f8:80:61:e5:f0:
    ba:e5:f0:1e:3f:a7:0d:b0:e9:60:5e:7c:fd:57:5e:
    9c:81:ef:ee:c5:29:c3:3f:d9:03:7a:20:fd:8a:cd:
    51:3a:c9:63:77:68:31:3e:63:f9:83:8a:e3:51:1c:
    dd:0a:9a:2b:51:6f:21:48:c8:d4:75:a3:60:a0:63:
    59:44:97:39:ee:cd:25:1a:bb:42:b0:14:57:3e:43:
    9f:2f:a4:57:35:57:b2:56:99:ff:c1:1e:63:1c:e8:
    ee:97:5a:86:e7:e2:72:bc:f5:f7:6a:93:45:03:48:
    fe:3f
 
Modulus=367198D6B5614E95813ADD8F22A4717BC72BE1EABD933D1B86944FDB75B8ED230BE62D7D                                                                                                                                           1B69D222095C128C86F82012ECB116191FD9D018A6D02F84DB27BC51A21307DC86F4BF771C691C14                                                                                                                                                             3E5ABE549B5BD2D6EB1A21FD6270E7E1B48FE0611FBB2E1B0B3524E6F4DE8B4E4A345DA44A13DE82                                                                                                                                                             5B72608DB6C7C4A40B78266E6C87BBFDEF6B48381D49C4507A58BCD47B76D64B45908B158BD7EBC4                                                                                                                                                             DACB0B1CFD6C2C19574F40EB2EFD0E9E10DC7005CAD39BCAF52B9EAC3873368D69031C5E724684A4                                                                                                                                                             4F068EFD1D3DC096D9B5D6411E58BDEE43E46B99A0D0494B9DB28195AF901AFF130D4A6E203DAD08                                                                                                                                                             DA57FA7E40262A5BADB2A323EDA28B44696AB305D
</code>


3. Download rsa wiener attack tool https://github.com/pablocelayes/rsa-wiener-attack
2. 

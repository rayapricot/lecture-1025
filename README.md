# テクノロジー（藤原）10/25授業

```
rayapricot:~/workspace $ [ ! -f ~/.ssh/id_rsa ] && ssh-keygen -t rsa
rayapricot:~/workspace $ cat ~/.ssh/id_rsa.pub
rayapricot:~/workspace $ [ ! -f ~/.ssh/id_rsa ] && ssh-keygen -t rsa
rayapricot:~/workspace $ cat ~/.ssh/id_rsa.pub
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAACAQCim/8BB+1ZpilRIJTtjkxtB55WovsYeYPmEuoOp/T6e7SW1fwumM+PngagtDJjm7Bv/16hbvEZt6a/I9lEM4D/8SpVTuTN6Ckkk5m2P+mmfTfEfkMte3nfbEw9LT3tdW+UaV6l0lQDTcdJf1ZeZ6AekyNgcUEjuEu9HS0ZEuAFigNH6mPhqHIWg+u1JZVnF5e3P408EeLwJc2vmLDbQd9XTEyz7kHaoIyj4oV1lmS0CsC1M44QaTC8DDUYRXxrb5LjRYKK/YpfRbqlgDrjch/UgJs9B77qukv9qEHnH2GkP0xIciRDjhysoTbu88hIcZlFDBSKjobCGgerBfiKumW7XCDkRCxmta3RsLBqf8dX0n/k+uTzvoH//9uYfsdtdZDEpnIDF+ZFWGYoItDWHxqS/4zkGrPrqktyfr3c5OK4VwR9OXKDJFegQZSefjaSgbStUChjqahO3Cu9uISI0SdQHJazbmJe1xRiPX3vqFgmPVg00Z6Oz1DD6FP5Y6HYOGnAKavreX4BoJQ7oX4ka6itQdQwNEBnSytRCG2cgb1M+XiFwXL5IDj4VZoAeAZm9o+oJastCEQXMEfF2d1+rRCWY9Vd+zc9fe3ceBMfXlrwFnUSBVzC1iPITdIct/EO7pE/THNnWGlOUBBKtx1DQPgABLwORvCzpaA+0Yzlhd2b5w== kd1220559@st.kobedenshi.ac.jp
rayapricot:~/workspace $ ssh -T git@github.com
Warning: Permanently added 'github.com,192.30.253.113' (RSA) to the list of known hosts.
Hi rayapricot! You've successfully authenticated, but GitHub does not provide shell access.
rayapricot:~/workspace $ git clone ssh-rsa AAAAB3Nz
rayapricot:~/workspace $ 
rayapricot:~/workspace $ git clone git@github.com:rayapricot/lecture-1025.git
Cloning into 'lecture-1025'...
Warning: Permanently added 'github.com,192.30.253.113' (RSA) to the list of known hosts.
remote: Counting objects: 6, done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 6 (delta 0), reused 6 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.
rayapricot:~/workspace $ git clone git@github.com:rayapricot/project2-server-app.git
Cloning into 'project2-server-app'...
Warning: Permanently added 'github.com,192.30.253.112' (RSA) to the list of known hosts.
remote: Counting objects: 7, done.
remote: Compressing objects: 100% (7/7), done.
remote: Total 7 (delta 0), reused 7 (delta 0), pack-reused 0
Receiving objects: 100% (7/7), done.
rayapricot:~/workspace $ git clone ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAACAQCim/8BB+1ZpilRIJTtjkxtB55WovsYeYPmEuoOp/T6e7SW1fwumM+PngagtDJjm7Bv/16hbvEZt6a/I9lEM4D/8SpVTuTN6Ckkk5m2P+mmfTfEfkMte3nfbEw9LT3tdW+UaV6l0lQDTcdJf1ZeZ6AekyNgcUEjuEu9HS0ZEuAFigNH6mPhqHIWg+u1JZVnF5e3P408EeLwJc2vmLDbQd9XTEyz7kHaoIyj4oV1lmS0CsC1M44QaTC8DDUYRXxrb5LjRYKK/YpfRbqlgDrjch/UgJs9B77qukv9qEHnH2GkP0xIciRDjhysoTbu88hIcZlFDBSKjobCGgerBfiKumW7XCDkRCxmta3RsLBqf8dX0n/k+uTzvoH//9uYfsdtdZDEpnIDF+ZFWGYoItDWHxqS/4zkGrPrqktyfr3c5OK4VwR9OXKDJFegQZSefjaSgbStUChjqahO3Cu9uISI0SdQHJazbmJe1xRiPX3vqFgmPVg00Z6Oz1DD6FP5Y6HYOGnAKavreX4BoJQ7oX4ka6itQdQwNEBnSytRCG2cgb1M+XiFwXL5IDj4VZoAeAZm9o+oJastCEQXMEfF2d1+rRCWY9Vd+zc9fe3ceBMfXlrwFnUSBVzC1iPITdIct/EO7pE/THNnWGlOUBBKtx1DQPgABLwORvCzpaA+0fatal: repository 'ssh-rsa' does not exist
rayapricot:~/workspace $ git clone git@github.com:rayapricot/project2-server-app.git
Cloning into 'project2-server-app'...
Warning: Permanently added 'github.com,192.30.253.113' (RSA) to the list of known hosts.
remote: Counting objects: 7, done.
remote: Compressing objects: 100% (7/7), done.
remote: Total 7 (delta 0), reused 7 (delta 0), pack-reused 0
Receiving objects: 100% (7/7), done.
rayapricot:~/workspace $ pry
[1] pry(main)> puts "こんにちは"
こんにちは
=> nil
[2] pry(main)> print "こんにちは"                  
こんにちは=> nil
[3] pry(main)> p "こんにちは"
"こんにちは"
=> "こんにちは"
[4] pry(main)> massage = "こんにちは"
=> "こんにちは"
[5] pry(main)> puts message
NameError: undefined local variable or method `message' for main:Object
Did you mean?  massage
from (pry):5:in `__pry__'
[6] pry(main)> message = "こんにちは"              
=> "こんにちは"
[7] pry(main)> puts message
こんにちは
=> nil
[8] pry(main)> num = 123
=> 123
[9] pry(main)> puts = 123
=> 123
[10] pry(main)> puts = num
=> 123
[11] pry(main)> puts massage
こんにちは
=> nil
[12] pry(main)> puts = 123
=> 123
[13] pry(main)> message = "こんにちは"
=> "こんにちは"
[14] pry(main)> puts message length
NameError: undefined local variable or method `length' for main:Object
from (pry):14:in `__pry__'
[15] pry(main)> puts message length
NameError: undefined local variable or method `length' for main:Object
from (pry):15:in `__pry__'
[16] pry(main)> length
NameError: undefined local variable or method `length' for main:Object
from (pry):16:in `__pry__'
[17] pry(main)> puts message length
NameError: undefined local variable or method `length' for main:Object
from (pry):17:in `__pry__'
[18] pry(main)> 1234
=> 1234
[19] pry(main)> 1234.class
=> Integer
[20] pry(main)> 3.14
=> 3.14
[21] pry(main)> 3.14.class
=> Float
[22] pry(main)> (3.14).class
=> Float
[23] pry(main)> a = 4
=> 4
[24] pry(main)> b = "9"
=> "9"
[25] pry(main)> a.class
=> Integer
[26] pry(main)> b.class
=> String
[27] pry(main)> a + b
TypeError: String can't be coerced into Integer
from (pry):27:in `+'
[28] pry(main)> b = 9
=> 9
[29] pry(main)> a + b
=> 13
[30] pry(main)> a
=> 4
[31] pry(main)> a.to_f
=> 4.0
[32] pry(main)> a.to_i
=> 4
[33] pry(main)> a.to_s
=> "4"
[34] pry(main)> a
=> 4
[35] pry(main)> animals = ["いぬ","ねこ","ぞう"]
=> ["いぬ", "ねこ", "ぞう"]
[36] pry(main)> animals[0]
=> "いぬ"
[37] pry(main)> animals[1]
=> "ねこ"
[38] pry(main)> animals[1] "こうもり"
SyntaxError: unexpected tSTRING_BEG, expecting end-of-input
animals[1] "こうもり"
            ^
[38] pry(main)> animals[1]
=> "ねこ"
[39] pry(main)> animals[1] = "こうもり"
=> "こうもり"
[40] pry(main)> animals[1]
=> "こうもり"
[41] pry(main)> animal
NameError: undefined local variable or method `animal' for main:Object
Did you mean?  animals
from (pry):41:in `__pry__'
[42] pry(main)> animals
=> ["いぬ", "こうもり", "ぞう"]
[43] pry(main)> d if true
NameError: undefined local variable or method `d' for main:Object
from (pry):43:in `__pry__'
[44] pry(main)> a = true
=> true
[45] pry(main)> b = 1
=> 1
[46] pry(main)> c = "a"
=> "a"
[47] pry(main)> d if true                          
NameError: undefined local variable or method `d' for main:Object
from (pry):47:in `__pry__'
[48] pry(main)> d = if true                        
[48] pry(main)*   "a"
[48] pry(main)*   
```
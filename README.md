Rubyのしくみ

YARV命令の動作を知りたい部分を
```
code = <<END
知りたい部分

END
```
のように囲んで、

`RubyVM::InstructionSequence.compile(code).disasm`　 
とすることで、表示が可能

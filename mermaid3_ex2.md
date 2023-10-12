```mermaid
flowchart LR
S{{学生}}
a(課題を提出する)
b(試験を受ける)
c(講義内で発言する)
T{{教員}}
d(課題を採点する)
e(試験を採点する)
f(発言を記録する)
G{{成績評価}}

S-.->a-.->T-.->d-.->G
S-.->b-.->T-.->e-.->G
S-.->c-.->T-.->f-.->G

subgraph 学期中
a
b
c

subgraph 期末
d
e
f

end
```

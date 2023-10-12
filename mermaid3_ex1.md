```mermaid
flowchart LR
S{{学生}}
T{{教員}}
a(課題)
b(試験)
c(講義内発言)
P{{成績評価}}

S-.->a-.->T-.->P
S-.->b-.->T
S-.->c-.->T

subgraph 採点
a
b
c
T
end

```

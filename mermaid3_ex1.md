```mermaid
flowchart LR
S{{学生}}
a(課題を提出する) -.-> d(課題を採点する)
b(試験を受ける) -.-> e(試験を採点する)
c(講義内で発言する) -.-> f(発言を記録する)
T{{教員}}

S --- a & b & c
d & e & f --- T

subgraph 学期中
a
b
c
end
```

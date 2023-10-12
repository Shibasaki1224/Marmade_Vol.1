```mermaid
flowchart LR
S{{学生}}
T{{教員}}
G{{成績評価}}

S-.->a[課題を提出]-.->T-.->d[課題を採点する]-.->G
S-.->b[試験を受ける]-.->T-.->e[試験を採点する]-.->G
S-.->c[講義内で発言する]-.->T-.->f[発言を記録する]-.->G

subgraph 学期中
a&b&c

subgraph 期末
d&e&f

end
```

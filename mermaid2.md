```mermaid
flowchart LR
a{{学生}}
b(本を借りる)
c(本を返す)
d(本を予約する)
a---b
a---c
a---d
e{{"図書管理\nデータベース"}}
b---e
c---e
d---e

subgraph 図書館窓口
b
c
d
end
```

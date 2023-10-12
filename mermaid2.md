```mermaid
flowchart LR
a{{学生}}
b(本を借りる)
c(本を返す)
d(本を予約する)
e("借りた本を\n延長する")
f(本を探す)
g{{"図書管理\nデータベース"}}

a---b---g
a---c---g
a---d---g
a---e---g
a---f---g

subgraph 図書館窓口
b
c
d
e
f
end
```

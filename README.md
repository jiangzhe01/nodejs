# Node 代码练习

## Node.js教程

## Node从入门到上线

## Node入门

### 流程图 练习

```flow
st=>start:开始
op=>operation:Your operation?
cond=>condition:Yes or No?
e=>end
st->op->e
cond(Yes)->e
cond(No)->op
&```

```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```

mermaid
graph TB
    c1-->a2
    subgraph one
    a1-->a2
    end
    subgraph two
    b1-->b2
    end
    subgraph three
    c1-->c2
    end


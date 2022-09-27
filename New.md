```flow
st=>start: Start
op=>operation: Your Operation
cond=>condition: Yes or No?
e=>end

st->op->cond->st
cond(yes)->e
cond(no)->op
​```

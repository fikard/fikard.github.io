graph LR
A[输入] --> B(模型处理)
B --> C{结果是否达标}
C -- Yes --> D[输出]
C -- No --> B

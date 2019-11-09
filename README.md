# Humans-360
```python
def setup():
    size(520, 500)
    
def draw():
    background(300, 100, 40)
    fill(0)
    homem(150, 250, 200, 100)
    fill (255)
    homem(360, 250, 200, 100)
    fill (255)
    homem(160, 250, 200, 0)
    fill (0)
    homem(370, 250, 200, 0)
    fill (20, 30, 100)
    homem(260, 150, 150, 0)

    
    
def homem(x, y, LADO, LADOO):
    L, l = LADO / 2, LADOO / 2
    pushMatrix() 
    translate(x, y)
    rotate(mouseX / 50.)
    beginShape()
    vertex(20, -70)
    vertex(14, -20)
    vertex(100, -15)
    vertex(23, 7)
    vertex(29, 100)
    vertex(0, 25)
    vertex(-29, 100)
    vertex(-23, 7)
    vertex(-100, -15)
    vertex(-14, -20)
    vertex(-14, -70)
    endShape(CLOSE) 
    popMatrix() 
```

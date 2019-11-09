# Humans-360

def setup():
    size(520, 500)
    
def draw():
    background(300, 100, 40)
    fill(0)
    estrela(150, 250, 200, 100)
    fill (255)
    estrela(360, 250, 200, 100)
    fill (255)
    estrela(160, 250, 200, 0)
    fill (0)
    estrela(370, 250, 200, 0)
    fill (20, 30, 100)
    estrela(260, 150, 150, 0)

    
    
def estrela(x, y, largura, largurinha):
    M, m = largura / 2, largurinha / 2
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

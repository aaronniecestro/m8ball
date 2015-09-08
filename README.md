# m8ball
def p1():
f="/Users/aaronniecestro/Documents/magic8ball.jpg"
p=makePicture(f)
s=makeStyle(sansSerif,bold,18)
addTextWithStyle(p,130,130,"You may rely",s,white)
addTextWithStyle(p,150,150,"on it",s,white)
repaint(p)

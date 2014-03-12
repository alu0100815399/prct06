#! encoding: UTF-8
def aproxpi (inicio,fin):

  if fin>0:
    
    suma=0.0
    pi=3.1415926535897931159979634685441852
    for i in range(inicio,fin+1):
  
      a= float (i-1.0)/fin
      b= float (i)/fin
      x_i= (i-0.5)/fin
      fx_i= ((4.0)/(1.0+x_i**2))
      
      suma+= fx_i

    aprox= suma/fin					
    
  return aprox

n=int(raw_input('Introduzca el número de subintervalos: '))
veces=int(raw_input('Introduzca el número de veces que va a ejecutar el programa: '))
l=[]
for i in range (1,veces+1):
  n*=i
  s=aproxpi (1,n)
  print "La aproximación del número pi es: %11.10f" %s
  l=l+[s]
print l
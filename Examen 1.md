#16 agosto 2022
#Examen 1
"1. Calcular el valor minimo del vector generado con vec = sample(0:100,10)"

vec= sample(0:100,10)
vmin= vec[1]
lvec= length(vec)
for (i in 1:lvec){
  if(vec[i]<vmin)
    vmin= vec[i]}
cat(sprintf("el valor minimo es  %1.f", vmin))

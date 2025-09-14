library(ggplot2)
?mpg
#View(mpg)
?aes
?geom_point




#ggplot(data=mpg) +
  #geom_point(mapping = aes(y=hwy,x=displ))


#ggplot(data=mpg) +
  #geom_point(mapping = aes(y=hwy,x=displ, color = class))

ggplot(data=mpg) +
  geom_point(mapping = aes(y=hwy,x=displ),color = "red")
ggplot(data=mpg) +
  geom_smooth(mapping = aes(y=hwy, x = displ, color = class))



ggplot(data=mpg) +
  geom_smooth(mapping = aes(y=hwy,x=displ, linetype = drv))



ggplot(data=mpg, mapping = aes(y=hwy,x=displ, color=drv)) +
  geom_point()+
  geom_smooth(mapping=aes(linetype = drv))

###############################################

setwd("C:/Users/rajabi.nasim/Documents/Probability_Statistics/Notebooks/0 - R Notebooks/2 - Data Visualization")
Salaries <- read.csv("Salaries.csv")

#show(Salaries)
#View(Salaries)

ggplot(data=Salaries, mapping =aes(x=yrs.service,y=salary))+
  geom_point()+
  geom_point(mapping=aes(color = salary >100000))

ggplot(data=Salaries, mapping =aes(x=yrs.service,y=salary))+
  geom_point(mapping=aes(color = rank))+
  geom_point(mapping=aes(shape=sex))

?diamonds
ggplot(diamonds)+
  geom_bar(aes(x=cut))

ggplot(diamonds)+
  stat_count(aes(x=cut))

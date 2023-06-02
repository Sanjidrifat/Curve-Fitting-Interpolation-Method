clear all;
close all;
clc;
dataX=0:6;
dataY=[0 0.8415 0.9093 0.1411 -0.7568 -0.9589 -0.2794]
n=length(dataX);
x=3.5;
sum=0;
for i=1:n
    prod=1;
    for j=1:n
        if i~=j
            prod=prod.*((x-dataX(j))/(dataX(i)-dataX(j)));
        end
    end
    sum=sum+prod.*dataY(i);
end
y=sum;
plot(dataX,dataY)
hold on
plot(x,y,'o')

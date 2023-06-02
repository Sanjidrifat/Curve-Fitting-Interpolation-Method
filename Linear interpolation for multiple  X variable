clear all;
close all;
clc;
dataX=0:6;
dataY=[0 0.8415 0.9093 0.1411 -0.7568 -0.9589 -0.2794];
x=[2.5 3 3.5];
 
for k = 1:length(x)
  for  i=1:length(dataX)-1
    if dataX(i)<=x(k) && dataX(i+1)>=x(k)
        x1=dataX(i);
        x2=dataX(i+1);
        y1=dataY(i);
        y2=dataY(i+1);
    end
  end
  y=(x(k)-x2)*y1/(x1-x2)+(x(k)-x1)*y2/(x2-x1);
end
 
 
plot(dataX,dataY)
hold on
plot(x,y,'o')

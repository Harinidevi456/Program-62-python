c = 0
p = 1.0
count = int(input(&quot;Enter the number of values: &quot;))
while(c&lt;count):
x = float(input(&quot;Enter a real number: &quot;))
c = c+1
p = p * x
gm = pow(p,1.0/count)
print(&quot;The geometric mean is: &quot;,gm)
output
Enter the number of values: 3
Enter a real number: 2
Enter a real number: 8
Enter a real number: 4
The geometric mean is: 4.0

# The Donut.go

You ever heard of a donut? Just a donut, why so uptight? It's like everyone's got a donut.c, but we're spicing things up in Go with my little spaghetti code. Don't worry, we're keeping it playful~~
```go
package main;import("fmt";"math";"time");func main(){A,B:= 0.0,0.0;z:=[1760]float64{};b:=[1760]byte{};i,j:=0.0,0.0;k:=0;fmt.Print("\x1b[2J");for{for k=0;k<1760;k++{b[k]=32;z[k]=0;};for j=0;j<6.28;j+=0.07{for i=0;i< 6.28;i+=0.02{c:=math.Sin(i);d:=math.Cos(j);e:=math.Sin(A);f:=math.Sin(j);g:=math.Cos(A);h:=d+2;D:=1/(c*h*e+f*g+5);l:=math.Cos(i);m:=math.Cos(B);n:=math.Sin(B);t:=c*h*g-f*e;x:=int(40+30*D*(l*h*m-t*n));y:=int(12+15*D*(l*h*n+t*m));o:=int(x+80*y);N:=int(8 *((f*e-c*d*g)*m-c*d*e-f*g-l*d*n));if 22>y&&y>0&&x>0&&80>x&&D>z[o]{z[o]=D;if N > 0 {b[o]=".,-~:;=!*#$@"[N]}else{b[o]='.'}}}};fmt.Print("\x1b[H");for k=0;k<1761;k++{if 0==k%80{fmt.Print("\n")}else{fmt.Printf("%c",b[k])};A+=0.00004;B+=0.00002};time.Sleep(16*time.Millisecond)}}
```

# Let's Get Rolling!

```bash
go run donut.go
```

Roll away and enjoy the code magic! 🍩✨
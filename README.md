module fulladder(a,b,c,s,ca);
input a,b,c;
output ca,s;
wire n,p,k;
xor (s,a,,b,c);
and(n,a,b);
and (p,b,c);
and(k,a,c);
or (ca,n,p,k);
endmodule

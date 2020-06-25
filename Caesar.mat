
%% Written by Azizul Hakim
%Email:ajijulgreen@gmail.com
%Here caesar(ch,n) takes ch a character vector,n is the key to encode the
%messange.
%Example:coded=caesar('Hello recently i learn to code in matlab!',-258)
%
%
%here 258 is left shift key and encoded message is:c!((+;.!~!*0(5;%;(!|.*;0+;~+ !;%*;)|0(|}<
%Each character is shifted to left by 258 and if the ASCII value is less
%than 32 or greater than 126 than it will wrap up
%% Main section
function coded=caesar(ch,n)
ln=length(ch);
k=0;
for i=1:ln
    k=k+1;
    d=ch(i)+n;
    if d<32
        d=127+95*fix(abs(32-d)/95)-(32-d);
        
        
    end
    if d>126
       d=d-95*fix((d-127)/95+1);%for greater than 126
       
    end
    z(k)=char(d);
end   
coded=z;
    

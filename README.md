# matlab
Programs that are related to various problems .
prompt={'Enter Value of a :','Enter Value of b:','Enter Value of c'};
title='Shri_Dharacharya_Formula';
answer=inputdlg(prompt,title);
a=answer{1};
b=answer{2};
c= answer{3};
prompt={'do you want to find roots'};
title='action to perform';
answer=inputdlg(prompt,title);
action=answer{1};
B=str2num(b);
B=[B];
C=str2num(c);
C=[C];
A=str2num(a);
A=[A];
disp(A);
disp(B);
disp(C);
D=((B.^2)-(4*C*A));
x1=((-B)+ (sqrt(D)))/(2*A);
x2=((-B)- (sqrt(D)))/(2*A);
disp('DISCREMINENT IS ');
disp(D);
disp('your roots are ');
disp('x1=');
disp(x1);
disp('x2=');
disp(x2);


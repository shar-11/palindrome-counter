# palindrome-counter
    Public static intcountpalindrome(string s){
    Int count=0;
    If(s==null||s.length()==0){
    Return count;
    }
    Boolean[][]dp=new boolean[s.length]
    [S.length()];
    For(int I=0;I<length.s;I++)
    {
    Dp[I][ I]==0;
    Count ++;
    }
   For(inti=1;I<=length.s;I++)
   {
    If(s.charat(i-1)==s.charat(I))
    {
    . Dp[i-1][ I]=true;
      Count++;
     }
    For(intj=1;j<s.length();j++)
     For(I=0;i<j;I++)
     {
     If(dp(I+)(i-1)&&s.charat(I)==s.charat(j))
     Dp[I][j]=true;
     Count++;
     }
.  ...}

    }
  Return count;
}

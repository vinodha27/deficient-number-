# deficient-number

int n=45;
        int c=1;
        for(int i=1;i<n;i++)
        {
            if(n%i==0)
            {
                c=c+i;
            }
        }
            if(c<=n)
            {
                System.out.println(" deficient number");
            }
            else 
            {
                System.out.println("not deficient number");
            }

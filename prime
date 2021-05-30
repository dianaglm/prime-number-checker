int prime(int x)
{
	if(x==1 || (x%2==0  && x!=2))
		return 0;
	else 
		for(int i=3; i*i<=x; i+=2)
			if(x%i==0)
				return 0;
	return 1;
}

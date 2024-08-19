def factors(n):
    # Complete code for this function
    fact =[]

    for i in range (1,n+1):
      if n % i == 0:
        fact.append(i)
    return fact

def common_factors(a, b):
    # Complete code for this function
    fact_a = factors(a)
    fact_b = factors(b)
    #print(fact_a)
    #print(fact_b)
    common_fact =[]
    for i in fact_a:
      if i in fact_b:
        common_fact.append(i)
    return common_fact

def factors_upto(n):
    # Complete code for this function
    fact_dict = {}
    lfact=[]
    for i in range (1,n+1):
      fact_dict[i] = factors(i)
    return fact_dict

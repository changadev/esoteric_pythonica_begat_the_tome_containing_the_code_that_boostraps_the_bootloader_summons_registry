#lambda functions are throwaway or anonnymous functions
a = [(1,2),(2,5),(3,1),(4,15)] #some example tuples to disect with function or lambda
def second(x):
    return x[1]
''''returns the second element of tuple/list x provided to the func''''
'''the above function reaches into tuples for the second element to then iterate through and sort'''
a.sort(key=second)
#better, lambda way as follows:
a.sort(key=lambda x:x[1])
'''this is so much better with an anonymous lambda function!'''

#code I am stuck with right now:
def computepay(h, r):
    return print(f'{(lambda x: (h-40.0)*r*1.5 + (40*r))}') 
#I cannot figure out why this instances an object instead of doing a f-string print statement

#I've spent so long bashing (heh) my brain against interactive shell that I can no longer even extract the functionality I want from the lambda function itself
def computepay(h, r):
    return lambda x: (h-40.0)*r*1.5 + (40*r)

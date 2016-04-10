table = { 'A':10 , 'B':11 , 'C':12 , 'D':13 , 'E':14 , 'F':15}
def pow(arg,n):
    i=0
    s=1
    while i<n:
        s=s*arg
        i=i+1
    return s


def hex_to_dec(arg):

    sum=0
    chars = list(arg)
    size = len(chars)
    #print str(chars) + ' size ' + str(size)
    for v in chars:
        if v>='A' and v<='F' or v>='a' and v<='f':
            v=v.upper()
            sum = sum +table[v]*pow(16,size-1)
            size =size -1
            #print str(v)+' '+ str(size) + 'litera   '
        else:
            sum = sum + int(v)*pow(16,size-1)
            size =size -1
            #print str(size) + 'digit'
    return sum

print hex_to_dec('49276d206b696c6c696e6720796f757220627261696e206c696b65206120706f69736f6e6f7573206d757368726f6f6d')

import base64
encoded = base64.b64encode('data to be encoded')
print encoded

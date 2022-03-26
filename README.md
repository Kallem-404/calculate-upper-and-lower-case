# calculate-upper-and-lower-case
def string_test(s):          #defining function
    d={"UPPER_CASE":0, "LOWER_CASE":0}
    for char in s:
        if char.isupper():   # counting the upper case character in the string
           d["UPPER_CASE"]+=1
        elif char.islower():   # counting the lower case character in the string
           d["LOWER_CASE"]+=1
        else:
           pass

    print ("Original String : ", s)
    print ("No. of Upper case characters : ", d["UPPER_CASE"])
    print ("No. of Lower case Characters : ", d["LOWER_CASE"])

string_test('The quick Brown Fox')            #taken as input string

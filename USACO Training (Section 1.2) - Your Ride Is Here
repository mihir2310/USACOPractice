"""
USER: mihir.s1
TASK: ride
LANG: PYTHON3
"""
def getNumber(letters):
    numbers = []
    for letter in letters:
        number = ord(letter)-64
        numbers.append(number)
    ans = 1
    for i in numbers:
        ans = (i*ans)
    return ans%47

fin = open ('ride.in', 'r')
fout = open ('ride.out', 'w')

cometName = fin.readline()
groupName = fin.readline()

cometNumber = getNumber(cometName)
groupNumber = getNumber(groupName)

if(cometNumber == groupNumber):
	fout.write ("GO\n")
else:
	fout.write ("STAY\n")
fout.close()

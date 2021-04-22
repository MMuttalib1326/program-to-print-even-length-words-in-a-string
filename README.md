# program-to-print-even-length-words-in-a-string
Python  programming

def printWords(s):
	s = s.split(' ')
	for word in s:
		if len(word)%2==0:
			print(word)
s = "i am mohd muttalib"
printWords(s)

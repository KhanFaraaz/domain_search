#!/usr/bin/pyhton3
import sys
domain=sys.argv[1]
agr=sys.argv[2]
with open(agr) as file:
	lines = [line.rstrip() for line in file]
val=0
for i in lines:
	print(lines[val]+"."+domain)
	if val <= len(lines):
		val=val+1
	else:
		break
val=0
for i in lines:
	print(lines[val]+"0"+"."+domain)
	if val <= len(lines):
		val=val+1
	else:
		break
val2=0

toallenth= len(lines)
for b in lines:
	if val2 < toallenth:
		val3=0
		for j in b:
			if val3 < toallenth:
				if lines[val2]!=lines[val3]:
					print(lines[val2]+str(val2)+"."+lines[val3]+str(val3)+"."+domain)
					val3=val3+1
			else:
				break
		val2=val2+1
	else:
		break



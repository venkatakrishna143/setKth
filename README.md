# setKth

def setKthBit(n,k):
	return ((1 << k) | n)
n = 10
k = 2
print("Kth bit set number = ",setKthBit(n, k))

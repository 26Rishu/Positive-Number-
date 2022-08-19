# Positive Number 
 Developed by Rishu 
# Remove Negative Elements in List
# Using list comprehension
 
# initializing list

test_list = [12, -7, 5, 64, -14] 
test_listt = [12, 14, -95, 3] 
 
# printing original list

print("The original list is : " + str(test_list))
print("The original list is : " + str(test_listt))
 
# Remove Negative Elements in List
# Using list comprehension

res = [ele for ele in test_list if ele > 0]
ress = [ele for ele in test_listt if ele > 0]
# printing result 

print("List after filtering : " + str(res))
print("List after filtering : " + str(ress))

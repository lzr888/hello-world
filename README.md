# hello-world
#冒泡法
num_list=[1,3,2,4,6,5,9,7,8]
for i in range(len(num_list)):
    for j in range(len(num_list)-i-1):
        if num_list[j]>num_list[j+1]:
            tmp=num_list[j]
            num_list[j]=num_list[j+1]
            num_list[j+1]=tmp
print(num_list)

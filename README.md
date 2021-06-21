# List-Creation-and-appending-that-data-into-another-list-to-get-the-table-of-14-from-the-list-contain
num=2
table_1=[12,24,36,48,60,72,84,96,108,120]
table_2=[]
print('Table of 12 :')

for i in range(len(table_1)):
    print('12 x ',i+1,'=',table_1[i])

for x in range(len(table_1)):
     table_2.append(table_1[x]+num)
     num=num+2
for i in range(len(table_2)):
    print('14 x ',i+1,'=',table_2[i])


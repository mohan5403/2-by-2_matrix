# 2-by-2_matrix
lst = [int(x) for x in input('Enter two values which is seperated by , :').split(',')] 
row_num = lst[0]
col_num = lst[1]
matrix_number = [[col for col in range(col_num)] for row in range(row_num)]
for col in range(row_num) :
    for row in range(col_num) :
        matrix_number [col][row]= row * col
print(matrix_number)

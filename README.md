# line-distribution-file

file = open("C:\\Users\\ADMIN\\Desktop\\vtube applications\\myfile.txt")

line_num = 1

for line in file:
    if "follow" in line:
        print(f" line {line_num} : {line}")
    line_num += 1

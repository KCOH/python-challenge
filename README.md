# python-challenge
#Importing module and dependency
import ~~
#and set for csv.file
csvpath=os.path.join('~')
#Open and Read CSV file
with open(csvpath, newline='') as csvfile:
#csv reader specifies Delimiter & Variable That Holds Contents
csvreader=csv.reader(csvfile, delimiter=',')
#read the header row first
csv_header=next(csvfile)
#Specify file to write to~
output_file=os.path.join('~')
#open file using 'write'mode. specify the variable to hold the contents
with open(output_file, '~') as txtfile:
#write TXT file
txtfile.write(f"~~~~\n")

# Python Challenge 
## Notes for debugs
# ## Lists
### 1. PyBank: 

When I tried to read csv file, I encountered difficulties in locating the file path. Then I asked Xpert Learning Assistant, and found the solution of using the r when getting stuck with file path. And it works! However, I still need to study how to make the csv file and ipynb file under the same repo, therefore the file path will be simpler. 

![This is an alt text.](/images/Screenshot_readCSVfile.png)


Line 37 of Main.py, Print the Analysis, I noticed that the required format had the dotted line ---------------- which need to be printed. I didn't know how. Then I asked ChatGPT, and it gave me two solutions:
1. Type: Separator = "-" *30 (or any integer I want)
2. Type: Print ("-------------------")
Therefore in PyBank, I used the 1st solution, and in PyPoll Homework, I used the 2nd Solution. 
![This is an alt text.](/images/shots2.png)

Line 25, the home work requirement expected me to print the result to a txt. file as well. I don't know how, so I asked ChatGPT, and got the hint, 
with open ('Fin_Analysis.txt','w') as file:
    file.write(formatted_results)


### 2. PyPoll:

1. When I tried to run Print to text file, there is a bug:
![This is an alt text.](/images/Shot4.png)
I figured it out by myself, then I tried to define the 'result' variable as in Line 22, result = [], then I debugged it. 




Section A:

class Solution:
    #it might be more efficient to start off with a: def __init__(self) function.
       def groupAnagrams(self, strs):
           #the result variable declaration along with the for loop and if statement should be indented within the groupAnagram function
      result = {}
      for i in strs:
         x = "".join(sorted())
         if x in result:
            result[x].append(i)
         else:
            result[x] = [i]
      return list(result.values())
ob1 = Solution()
#this is well done because intantiating the class is a very important and crucial step. This code is written effectively.
print(ob1.groupAnagrams(["eat", "tea", "tan", "ate", "nat", "bat"]))
#this code is written in Python2. I am more familiar with Python3 (as I did in my computer science course)

Section B:
https://github.com/A-P28112005/Python_project.git My own project

Section C:
https://dev.to/ap28112005/bible-quiz-55k7 (solutions and explanation of my project)

Section D:
https://www.loom.com/share/f834158278cf433eb1aa237bd08da502

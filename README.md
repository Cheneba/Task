# HTTP Methods, Command Line, and PHP Basics


## 📖 Task 1: Understanding HTTP Methods

**Summary**:
Write a summary (at least 5 sentences) explaining the difference between GET, POST, PUT, and DELETE in simple terms.
- GET:
- POST:
- PUT:
- DELETE:

### 📝 MCQs (Multiple Choice Questions):
1. Which HTTP method is used to retrieve data from a server?
   - b) GET

2. The PUT method is used for:
   - c) Updating an existing resource

3. What is the difference between POST and PUT?
   - c) PUT is for updating, POST is for creating

## 💻 Task 2: Command-Line Navigation (Linux/Git Bash)
Challenge Task:
1. Navigate to your Desktop:
   ```bash
   cd ~/Desktop
2. Create a new folder named task_folder:
   ```bash
   mkdir task_folder  
3. Create three files named file1.txt, file2.txt, and file3.txt:
   ```bash
   touch file1.txt file2.txt file3.txt
4. Delete file2.txt:rm file2.txt
   ```bash
   rm file2.txt
5. Move file1.txt back to your Desktop:
   ```bash
   mv file1.txt ../file1.txt
6. Check your Desktop to see the moved file
   ```bash
   cd ..
   ls

## 🖥️ Task 3: PHP Basics – Write Simple Code
📝 Coding Challenge:
a. Write a PHP script that:
- Stores a number in a variable.
- Checks if the number is even or odd using a conditional (if-else).
- Displays "The number is even" or "The number is odd" based on the condition.
   ```bash
   // Checks if $number is even or odd
   $number = 5;
   if ($number % 2 === 0) {
       echo "The number: $number is even";
   } else {
       echo "The number: $number is odd";
   }
b. Write another PHP script that:
- Creates an array of 5 colors.
- Uses a loop to print each color on a new line.
   ```bash
   // Displays colors from an array
   $arr = array('red', 'blue', 'green', 'cyan', 'yellow');
   foreach ($arr as $color) {
       echo "$color<br>";
   }

c. Modify your script to display only colors that contain the letter 'e'.
   ```bash
   // Displays colors from an array which contain the character 'e'
   $arr = array('red', 'blue', 'green', 'cyan', 'yellow');
   foreach ($arr as $color) {
       if (check_e($color)) {
           echo "$color<br>";
       }
   }
   
   // Checks the string $color for the presence of 'e'
   function check_e($c): bool
   {
       for ($i = 0; $i < strlen($c); $i++) {
           if ($c[$i] === 'e') {
               return true;
           }
       }
       return false;
   }

*********************************************************************************
## END

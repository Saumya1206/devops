TASK-1

# Create the file with your first name
touch saumya.txt

# Add few lines without a text editor
echo "My name is saumya ofc" >> saumya.txt
echo " I love web development" >> saumya.txt

# Add few more lines without a text editor
echo "I mean devops is fine too" >> saumya.txt
echo "devops does have a bright scope too" >> saumya.txt
echo "still I like fullstack more" >> saumya.txt
echo "This is the sixth line" >> saumya.txt

# Rename the file with your last name
mv saumya.txt pathak.txt

# Print the first 5 lines
echo "First 5 lines:"
head -n 5 pathak.txt

# Print the last 5 lines
echo "Last 5 lines:"
tail -n 5 pathak.txt

# Print lines 2 to 6 without using sed
echo "Lines 2 to 6:"
head -n 6 pathak.txt | tail -n 5


TASK -2
# Step 1: Create a file with the first name in a text editor 
 vim saumya.txt &
# Step 2: Create a file with the last name in a text editor 
vim pathak.txt &
# Step 3: List out processes running in the system
ps aux
# Step 4: Identify and kill the process belonging to the first name 
ps aux | grep 'vim firstname.txt'
kill <PID>

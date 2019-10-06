$Greeting = 'Hi my name is Emanuel'
$Pattern = 'Hi my name is (\w+)'

$Greeting -match $Pattern
$Matches

# Replace 'Emanuel' with your own name using Regex
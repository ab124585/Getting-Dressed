**Getting Dressed**

You have to get dressed in the morning before going to work. Unfortunately, you only accept a
space separated list of numbers to indicate article of clothing to don.
1 = hat
2 = pants
3 = shirt
4 = shoes
5 = socks


Rules:
• You must put your socks on before your shoes.
• You must put your pants on before your shoes.
• You must put your shirt on before your hat.
• A hat is optional, but all other articles of clothing are required.
• You must leave the house when receiving the number 6.
• You must leave the house after getting dressed.
• Any violation should output "fail" and stop immediately.


Examples:
• Input: 5 1
Output: socks, fail
• Input: 5 2 3 4 6
Output: socks, pants, shirt, shoes, leave


Please include all implementation and supporting Java, JavaScript, or Python code either in a zip
file, GitHub repository, or Bitbucket repository. Please treat this as production code to be
maintained by your peers and follow object-oriented best practices and design patterns
where appropriate. The exact input and output mechanisms are not important.
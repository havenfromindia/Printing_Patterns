# Printing_Patterns
Printing Patterns using loop ('#')

for i in range(4):
    for j in range(4):
        print('# ', end='')
    print()

# # # #
# # # #
# # # #
# # # #

print()

for j in range(4):
    for i in range(j+1):
        print('# ', end='')
    print()
#
# #
# # #
# # # #
print()

for j in range(4):
    for i in range(4-j):
        print('# ', end='')
    print()
# # # #
# # #
# #
#

# ***********************---------WHILE LOOP----------**************************

j = 1
while j <= 4:
    i = 1
    print()
    while i <= 4:
        print('# ', end='')
        i = i + 1
    j = j + 1
# # # #
# # # #
# # # #
# # # #

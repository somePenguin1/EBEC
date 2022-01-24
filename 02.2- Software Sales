"""
Author: Aadi Jain, jain448@purdue.edu
Assignment: m.n - Software Sales
Date: 9/19/2021

Description:
    Program that calculates cost of number of packages and applies discounts.

Contributors:
    Name, login@purdue.edu [repeat for each]

My contributor(s) helped me:
    [ ] understand the assignment expectations without
        telling me how they will approach it.
    [ ] understand different ways to think about a solution
        without helping me plan my solution.
    [ ] think through the meaning of a specific error or
        bug present in my code without looking at my code.
    Note that if you helped somebody else with their code, you
    have to list that person as a contributor.

Academic Integrity Statement:
    I have not used source code obtained from any unauthorized
    source, either modified or unmodified; nor have I provided
    another student access to my code.  The project I am
    submitting is my own original work.
"""

def main():

    PACKAGE=79  #constant
    numPac= int(input('How many packages will be purchased: ')) #input for packages
    cost=numPac*PACKAGE

    # main if statement
    if (numPac<0):
        print('  Invalid Input!')
    elif (numPac<5):
        print('  No discount applied.')
        print('  The total price for purchasing ' + str(numPac) + ' packages is $' + str(cost) +'.00.' )
    elif (numPac <25):
        discount=0.10
        cost*=(1.0-discount)
    elif (numPac<50):
        discount=0.20
        cost*=(1.0-discount)
    elif (numPac<100):
        discount=0.30
        cost*=(1.0-discount)
    else:
        discount=0.45
        cost*=(1.0-discount)

    if (numPac>=5):   #if statement to check
        print('  ' + str(int(discount*100)) + '% discount applied.')
        cost=round(cost,2)
        cost="{:,}".format(cost)
        print('  The total price for purchasing ' + str(numPac) + ' packages is $' + str(cost) +'0.' )

if __name__ == '__main__': # call main fucntion
    main()

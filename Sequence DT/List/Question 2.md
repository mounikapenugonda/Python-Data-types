## Write a Python program to multiply all the items in a list.
       Sol:
        # function
        def mult(items):
            m = 1
            for x in items:
                m = m* x
            print(m)
        # ex - 1
        mult(listt)   
            Output : 3628800
        # ex - 2
        mult([-1,2,3,4])
            Output : -24

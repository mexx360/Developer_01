def even_or_odd(integers = [0,1,2,3,4,5,6,7,8,9]):
  array_size=10
  array_index=0
  even_numbers = [ ]
  odd_numbers = [ ]
    if integers(array_index) % 2 == 0:
        even_numbers=+1
    else:
        odd_numbers=+1
    
    return integers(array_index) % 2 == 0


print even_numbers, odd_numbers
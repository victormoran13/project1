# project1
#print data
data_set = [
    ['56','52','39','69','65','66'],
    ['54','55','55','56','55','56'],
    ['Over','Under','Under','Over','Over','Over']]
for row in data_set:
    print("{: >20}{: >20}{: >20}{: >20}{: >20}{: >20}".format(*row))

#display sets of data 
actual_score = set(['56', '52', '39', '69', '65', '66'])
vegas_line = set(['54', '55', '55', '56', '55', '56'])
over_under = set(['Over', 'Under', 'Under', 'Over', 'Over', 'Over'])
results = actual_score | vegas_line | over_under           # union
actual_score.add('100')                                  # add element

print (actual_score)

#class 
class Myclass2:
   pass 

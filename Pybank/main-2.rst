.. code:: ipython3

    budget_data = [ "month", "year" , "profitloss" ]
    print(budget_data)

.. code:: ipython3

    nested_budget_data = [ [ "jan", 2010 , 867884 ],
                          
                           [ "feb", 2010 , 984655 ],
                          
                           [ "mar", 2010 , 322013 ],
                          
                           [ "apr", 2010 , -69417 ],
                          
                           [ "may", 2010 , 310503 ],
                          
                           [ "jun", 2010 , 522857 ],
                          
                           [ "jul", 2010 , 1033096 ],
                          
                           [ "aug", 2010 , 604885 ],
                          
                           [ "sep", 2010 , -216386 ],
                          
                           [ "oct", 2010 , 477532 ],
                          
                           [ "nov", 2010 , 893810 ],
                          
                           [ "dec", 2010 , -80353 ],
                          
                           [ "jan", 2011 , 779806 ],
                          
                           [ "feb", 2011 , -335203 ],
                          
                           [ "mar", 2011 , 697845 ],
                          
                           [ "apr", 2011 , 793163 ],
                          
                           [ "may", 2011 , 485070 ],
                          
                           [ "jun", 2011 , 584122 ],
                          
                           [ "jul", 2011, 62729 ],
                          
                           [ "aug", 2011, 668179 ],
                          
                           [ "sep", 2011, 899906 ],
                          
                           [ "oct", 2011, 834719 ],
                          
                           [ "nov", 2011, 132003 ],
                          
                           [ "dec", 2011, 309978 ],
                           [ "jan", 2012, -755566 ],
                          
                           [ "feb", 2012, 1170593 ],
                          
                           [ "mar", 2012, 252780 ],
                          
                           [ "apr", 2012, 1151518 ],
                          
                           [ "may", 2012, 817256 ],
                          
                           [ "jun", 2012, 570757 ],
                          
                           [ "jul", 2012, 506702 ],
                          
                           [ "aug", 2012, -1022534 ],
                          
                           [ "sep", 2012, 475062 ],
                          
                           [ "oct", 2012, 779976 ],
                          
                           [ "nov", 2012, 144175 ],
                    
                           [ "dec", 2012, 542494 ],
                           [ "jan", 2013, 359333 ],
                           [ "feb", 2013, 321469 ],
                           [ "mar", 2013, 67780 ],
                           [ "apr", 2013, 471435 ],
                           [ "may", 2013, 565603 ],
                           [ "jun", 2013, 872480 ],
                           [ "jul", 2013, 789480 ],
                           [ "aug", 2013, 999942 ],
                           [ "sept", 2013, -1196225 ],
                           [ "oct", 2013, 268997 ],
                           [ "nov", 2013, -687986 ],
                           [ "dec", 2013, 1150461 ],
                           [ "jan", 2014, 682458 ],
                           [ "feb", 2014, 617856 ],
                           [ "mar", 2014, 824098 ],
                           [ "apr", 2014, 581943 ],
                           [ "may", 2014, 132864 ],
                           [ "jun", 2014, 448062 ],
                           [ "jul", 2014, 689161 ],
                           [ "aug", 2014, 800701 ],
                           [ "sep", 2014, 1166643 ],
                           [ "oct", 2014, 947333 ],
                           [ "nov", 2014, 578668 ],
                           [ "dec", 2014, 988505 ],
                           [ "jan", 2015, 1139715 ],
                           [ "feb", 2015, 1029471 ],
                           [ "mar", 2015, 687533 ],
                           [ "apr", 2015, -524626 ],
                           [ "may", 2015, 158620 ],
                           [ "jun", 2015, 87795 ],
                           [ "jul", 2015, 423389 ],
                           [ "aug", 2015, 840723 ],
                           [ "sep", 2015, 568529 ],
                           [ "oct", 2015, 332067 ],
                           [ "nov", 2015, 989499 ],
                           [ "dec", 2015, 778237 ],
                           [ "jan", 2016, 650000 ],
                           [ "feb", 2016, -1100387 ],
                           [ "mar", 2016, -174946 ],
                           [ "apr", 2016, 757143 ],
                           [ "may", 2016, 445709 ],
                           [ "jun", 2016, 712961 ],
                           [ "jul", 2016, -1163797 ],
                           [ "aug", 2016, 569899 ],
                           [ "sep", 2016, 768450 ],
                           [ "oct", 2016, 102685 ],
                           [ "nov", 2016, 795914 ],
                           [ "dec", 2016, 60988 ],
                           [ "jan", 2017, 138230 ],
                           [ "feb", 2017, 671099 ] ]
                          
                           
                          
    first_entry = nested_budget_data[0]
    first_entry_month = nested_budget_data[0][0]
    first_entry_year = nested_budget_data[0][1]
    first_entry_pl = nested_budget_data[0][2]
    
    print("The first entry in nested_budget_data is:", first_entry)
    print(f"{first_entry_month} is {first_entry_year} year, serving as profit loss year{first_entry_pl}.")
    print(nested_budget_data)
    x = nested_budget_data
    
    # Total Months: this is how i calculated total months, using len
    len(x)
    print("Total_months:", len(x))
    
    #This is how i calculated total profit/loss
    Total1= x[0][2]+x[1][2]+ x[2][2]+ x[3][2]+ x[4][2]+x[5][2]+x[6][2]+x[7][2]+x[8][2]+x[9][2]+x[10][2]+x[11][2]+x[12][2]+x[13][2]+x[14][2]+x[15][2]+x[16][2]+x[17][2]+x[18][2]+x[19][2]+x[20][2]+x[21][2]+x[22][2]+x[23][2]+x[24][2]+x[25][2]+x[26][2]+x[27][2]+x[28][2]+x[29][2]+x[30][2]
    Total2= x[31][2]+x[32][2]+x[33][2]+x[34][2]+x[35][2]+x[36][2]+x[37][2]+x[38][2]+x[39][2]+x[40][2]
    Total3= x[41][2]+x[42][2]+x[43][2]+x[44][2]+x[45][2]+x[46][2]+ x[47][2]
    Total4= x[48][2]+x[49][2]+x[50][2]+x[51][2]
    Total5= x[52][2]+x[53][2]+x[54][2]+x[55][2]
    Total6= x[56][2]+ x[57][2]+x[58][2]+x[59][2]+x[60][2]+x[61][2]+x[62][2]+x[63][2]+x[64][2]+x[65][2]
    Total7= x[66][2]+x[67][2]+x[68][2]+x[69][2]+x[70][2]+x[71][2]+x[72][2]+x[73][2]+x[74][2]+x[75][2]
    Total8= x[76][2]+x[77][2]+x[78][2]+x[79][2]+x[80][2]+x[81][2]+x[82][2]+x[83][2]+x[84][2]+x[85][2]
    
    
    
    
    
    total = Total1 + Total2 +Total3+Total4 +Total5+Total6+Total7+Total8
    print("Total", total)
    
    
    



.. code:: ipython3

    nested_budget_data = [ [ "jan", 2010 , 867884 ],
                          
                           [ "feb", 2010 , 984655 ],
                          
                           [ "mar", 2010 , 322013 ],
                          
                           [ "apr", 2010 , -69417 ],
                          
                           [ "may", 2010 , 310503 ],
                          
                           [ "jun", 2010 , 522857 ],
                          
                           [ "jul", 2010 , 1033096 ],
                          
                           [ "aug", 2010 , 604885 ],
                          
                           [ "sep", 2010 , -216386 ],
                          
                           [ "oct", 2010 , 477532 ],
                          
                           [ "nov", 2010 , 893810 ],
                          
                           [ "dec", 2010 , -80353 ],
                          
                           [ "jan", 2011 , 779806 ],
                          
                           [ "feb", 2011 , -335203 ],
                          
                           [ "mar", 2011 , 697845 ],
                          
                           [ "apr", 2011 , 793163 ],
                          
                           [ "may", 2011 , 485070 ],
                          
                           [ "jun", 2011 , 584122 ],
                          
                           [ "jul", 2011, 62729 ],
                          
                           [ "aug", 2011, 668179 ],
                          
                           [ "sep", 2011, 899906 ],
                          
                           [ "oct", 2011, 834719 ],
                          
                           [ "nov", 2011, 132003 ],
                          
                           [ "dec", 2011, 309978 ],
                           [ "jan", 2012, -755566 ],
                          
                           [ "feb", 2012, 1170593 ],
                          
                           [ "mar", 2012, 252780 ],
                          
                           [ "apr", 2012, 1151518 ],
                          
                           [ "may", 2012, 817256 ],
                          
                           [ "jun", 2012, 570757 ],
                          
                           [ "jul", 2012, 506702 ],
                          
                           [ "aug", 2012, -1022534 ],
                          
                           [ "sep", 2012, 475062 ],
                          
                           [ "oct", 2012, 779976 ],
                          
                           [ "nov", 2012, 144175 ],
                    
                           [ "dec", 2012, 542494 ],
                           [ "jan", 2013, 359333 ],
                           [ "feb", 2013, 321469 ],
                           [ "mar", 2013, 67780 ],
                           [ "apr", 2013, 471435 ],
                           [ "may", 2013, 565603 ],
                           [ "jun", 2013, 872480 ],
                           [ "jul", 2013, 789480 ],
                           [ "aug", 2013, 999942 ],
                           [ "sept", 2013, -1196225 ],
                           [ "oct", 2013, 268997 ],
                           [ "nov", 2013, -687986 ],
                           [ "dec", 2013, 1150461 ],
                           [ "jan", 2014, 682458 ],
                           [ "feb", 2014, 617856 ],
                           [ "mar", 2014, 824098 ],
                           [ "apr", 2014, 581943 ],
                           [ "may", 2014, 132864 ],
                           [ "jun", 2014, 448062 ],
                           [ "jul", 2014, 689161 ],
                           [ "aug", 2014, 800701 ],
                           [ "sep", 2014, 1166643 ],
                           [ "oct", 2014, 947333 ],
                           [ "nov", 2014, 578668 ],
                           [ "dec", 2014, 988505 ],
                           [ "jan", 2015, 1139715 ],
                           [ "feb", 2015, 1029471 ],
                           [ "mar", 2015, 687533 ],
                           [ "apr", 2015, -524626 ],
                           [ "may", 2015, 158620 ],
                           [ "jun", 2015, 87795 ],
                           [ "jul", 2015, 423389 ],
                           [ "aug", 2015, 840723 ],
                           [ "sep", 2015, 568529 ],
                           [ "oct", 2015, 332067 ],
                           [ "nov", 2015, 989499 ],
                           [ "dec", 2015, 778237 ],
                           [ "jan", 2016, 650000 ],
                           [ "feb", 2016, -1100387 ],
                           [ "mar", 2016, -174946 ],
                           [ "apr", 2016, 757143 ],
                           [ "may", 2016, 445709 ],
                           [ "jun", 2016, 712961 ],
                           [ "jul", 2016, -1163797 ],
                           [ "aug", 2016, 569899 ],
                           [ "sep", 2016, 768450 ],
                           [ "oct", 2016, 102685 ],
                           [ "nov", 2016, 795914 ],
                           [ "dec", 2016, 60988 ],
                           [ "jan", 2017, 138230 ],
                           [ "feb", 2017, 671099 ] ]
                          
                           
                          
    first_entry = nested_budget_data[0]
    first_entry_month = nested_budget_data[0][0]
    first_entry_year = nested_budget_data[0][1]
    first_entry_pl = nested_budget_data[0][2]
    
    print("The first entry in nested_budget_data is:", first_entry)
    print(f"{first_entry_month} is {first_entry_year} year, serving as profit loss year{first_entry_pl}.")
    print(nested_budget_data)
    x = nested_budget_data
    
    # Total Months
    len(x)
    print("Total_months:", len(x))
    
    # This is how i calculated the change in profits for every month throughout the period
    
    tot = y = [x[1][2]-x[0][2], x[2][2]- x[1][2], x[3][2]-x[2][2],
        x[4][2]-x[3][2], x[5][2]-x[4][2], x[6][2]-x[5][2],
        x[7][2]-x[6][2], x[8][2]-x[7][2], x[9][2]-x[8][2],
        x[10][2]-x[9][2], x[11][2]-x[10][2], x[12][2]-x[11][2],
        x[13][2]-x[12][2], x[14][2]-x[13][2], x[15][2]-x[14][2],
        x[16][2]-x[15][2], x[17][2]-x[16][2], x[18][2]-x[17][2],
        x[19][2]-x[18][2], x[20][2]-x[19][2], x[21][2]-x[20][2],
        x[22][2]-x[21][2], x[23][2]-x[22][2], x[24][2]-x[23][2],
        x[25][2]-x[24][2], x[26][2]-x[25][2], x[27][2]-x[26][2],
        x[28][2]-x[27][2], x[29][2]-x[28][2], x[30][2]-x[29][2],
        x[31][2]-x[30][2], x[32][2]-x[31][2], x[33][2]-x[32][2],
        x[34][2]-x[33][2], x[35][2]-x[34][2], x[36][2]-x[35][2],
        x[37][2]-x[36][2], x[38][2]-x[37][2], x[39][2]-x[38][2],
        x[40][2]-x[39][2], x[41][2]-x[40][2], x[42][2]-x[41][2],
        x[43][2]-x[42][2], x[44][2]-x[43][2], x[45][2]-x[44][2],
        x[46][2]-x[45][2], x[47][2]-x[46][2], x[48][2]-x[47][2],
        x[49][2]-x[48][2], x[50][2]-x[49][2], x[51][2]-x[50][2],
        x[52][2]-x[51][2], x[53][2]-x[52][2], x[54][2]-x[53][2],
        x[55][2]-x[54][2], x[56][2]-x[55][2], x[57][2]-x[56][2],
        x[58][2]-x[57][2], x[59][2]-x[58][2], x[60][2]-x[59][2],
        x[61][2]-x[60][2], x[62][2]-x[61][2], x[63][2]-x[62][2],
        x[64][2]-x[63][2], x[65][2]-x[64][2], x[66][2]-x[65][2],
        x[67][2]-x[66][2], x[68][2]-x[67][2], x[69][2]-x[68][2],
        x[70][2]-x[69][2], x[71][2]-x[70][2], x[72][2]-x[71][2],
        x[73][2]-x[72][2], x[74][2]-x[73][2], x[75][2]-x[74][2],
        x[76][2]-x[75][2], x[77][2]-x[76][2], x[78][2]-x[77][2],
        x[79][2]-x[78][2], x[80][2]-x[79][2], x[81][2]-x[80][2],
        x[82][2]-x[81][2], x[83][2]-x[82][2], x[84][2]-x[83][2],
        x[85][2]-x[84][2]]
    
               
        
    
    print("_change_in_profit = ", tot)
    
    
    
         
    
        
         
                                                 
    
    
                                                       
                                                       
    
    
    



.. parsed-literal::

    The first entry in nested_budget_data is: ['jan', 2010, 867884]
    jan is 2010 year, serving as profit loss year867884.
    [['jan', 2010, 867884], ['feb', 2010, 984655], ['mar', 2010, 322013], ['apr', 2010, -69417], ['may', 2010, 310503], ['jun', 2010, 522857], ['jul', 2010, 1033096], ['aug', 2010, 604885], ['sep', 2010, -216386], ['oct', 2010, 477532], ['nov', 2010, 893810], ['dec', 2010, -80353], ['jan', 2011, 779806], ['feb', 2011, -335203], ['mar', 2011, 697845], ['apr', 2011, 793163], ['may', 2011, 485070], ['jun', 2011, 584122], ['jul', 2011, 62729], ['aug', 2011, 668179], ['sep', 2011, 899906], ['oct', 2011, 834719], ['nov', 2011, 132003], ['dec', 2011, 309978], ['jan', 2012, -755566], ['feb', 2012, 1170593], ['mar', 2012, 252780], ['apr', 2012, 1151518], ['may', 2012, 817256], ['jun', 2012, 570757], ['jul', 2012, 506702], ['aug', 2012, -1022534], ['sep', 2012, 475062], ['oct', 2012, 779976], ['nov', 2012, 144175], ['dec', 2012, 542494], ['jan', 2013, 359333], ['feb', 2013, 321469], ['mar', 2013, 67780], ['apr', 2013, 471435], ['may', 2013, 565603], ['jun', 2013, 872480], ['jul', 2013, 789480], ['aug', 2013, 999942], ['sept', 2013, -1196225], ['oct', 2013, 268997], ['nov', 2013, -687986], ['dec', 2013, 1150461], ['jan', 2014, 682458], ['feb', 2014, 617856], ['mar', 2014, 824098], ['apr', 2014, 581943], ['may', 2014, 132864], ['jun', 2014, 448062], ['jul', 2014, 689161], ['aug', 2014, 800701], ['sep', 2014, 1166643], ['oct', 2014, 947333], ['nov', 2014, 578668], ['dec', 2014, 988505], ['jan', 2015, 1139715], ['feb', 2015, 1029471], ['mar', 2015, 687533], ['apr', 2015, -524626], ['may', 2015, 158620], ['jun', 2015, 87795], ['jul', 2015, 423389], ['aug', 2015, 840723], ['sep', 2015, 568529], ['oct', 2015, 332067], ['nov', 2015, 989499], ['dec', 2015, 778237], ['jan', 2016, 650000], ['feb', 2016, -1100387], ['mar', 2016, -174946], ['apr', 2016, 757143], ['may', 2016, 445709], ['jun', 2016, 712961], ['jul', 2016, -1163797], ['aug', 2016, 569899], ['sep', 2016, 768450], ['oct', 2016, 102685], ['nov', 2016, 795914], ['dec', 2016, 60988], ['jan', 2017, 138230], ['feb', 2017, 671099]]
    Total_months: 86
    _change_in_profit =  [116771, -662642, -391430, 379920, 212354, 510239, -428211, -821271, 693918, 416278, -974163, 860159, -1115009, 1033048, 95318, -308093, 99052, -521393, 605450, 231727, -65187, -702716, 177975, -1065544, 1926159, -917813, 898738, -334262, -246499, -64055, -1529236, 1497596, 304914, -635801, 398319, -183161, -37864, -253689, 403655, 94168, 306877, -83000, 210462, -2196167, 1465222, -956983, 1838447, -468003, -64602, 206242, -242155, -449079, 315198, 241099, 111540, 365942, -219310, -368665, 409837, 151210, -110244, -341938, -1212159, 683246, -70825, 335594, 417334, -272194, -236462, 657432, -211262, -128237, -1750387, 925441, 932089, -311434, 267252, -1876758, 1733696, 198551, -665765, 693229, -734926, 77242, 532869]


.. code:: ipython3

    #Calculating the total change to determine the average
    sum(tot)
    print("Sum_of_tot", sum(tot))
    



.. parsed-literal::

    Sum_of_tot -196785


.. code:: ipython3

    p= sum(tot)
    print(p)
    
    
    
    



.. parsed-literal::

    -196785


.. code:: ipython3

    #calculating the average change
    average_change = p/85
    
    average_change





.. parsed-literal::

    -2315.1176470588234



.. code:: ipython3

    print("Financial Analysis Summary")
    
    print("Total_months", len(x))
    print("Total", total)
    print("average change", average_change)
    
    print("Max increase in profits ocured February 2012 : ", max(tot))
    print("Max decrease in profits occured September 2013 : ", min(tot))


.. parsed-literal::

    Financial Analysis Summary
    Total_months 86
    Total 38382570
    average change -2315.1176470588234
    Max increase in profits ocured February 2012 :  1926159
    Max decrease in profits occured September 2013 :  -2196167



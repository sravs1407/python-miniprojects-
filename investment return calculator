pa=int(input("enter principle amount:"))
minvest=int(input("enter monthly contribution:"))
yinvest=minvest*12
rate=int(input("enter rate of investment:"))
inc=int(input("enter rate of increment(per annum) of monthly payment:"))
inf=int(input("enter percentage of inflation"))
age=int(input("enter start age"))
endage=int(input("enter end age"))
time=endage-age
tot=pa
for i in range(time):
  tot=(tot+yinvest)*(1+rate*0.01)
  yinvest=yinvest*(1+inc*0.01)
  tot=tot-(inf*0.01)
  print("$ {} ) monthly contribution for the next year is : {} \n\t|| total amount :  {}".format(1+i,yinvest/12,tot))
print("The Total Amount after the age '{}' is {}".format(endage,tot))

'''output:
enter principle amount:5000
enter monthly contribution:500
enter rate of investment:15
enter rate of increment(per annum) of monthly payment:5
enter percentage of inflation5
enter start age20
enter end age65
$ 1 ) monthly contribution for the next year is : 525.0 
	|| total amount :  12649.949999999999
$ 2 ) monthly contribution for the next year is : 551.25 
	|| total amount :  21792.392499999994
$ 3 ) monthly contribution for the next year is : 578.8125 
	|| total amount :  32668.451374999993
$ 4 ) monthly contribution for the next year is : 607.7531250000001 
	|| total amount :  45556.28158124998
$ 5 ) monthly contribution for the next year is : 638.14078125 
	|| total amount :  60776.66694343747
$ 6 ) monthly contribution for the next year is : 670.0478203125001 
	|| total amount :  78699.45976620307
$ 7 ) monthly contribution for the next year is : 703.5502113281251 
	|| total amount :  99750.98865144602
$ 8 ) monthly contribution for the next year is : 738.7277218945314 
	|| total amount :  124422.57986549105
$ 9 ) monthly contribution for the next year is : 775.664107989258 
	|| total amount :  153280.35940745924
$ 10 ) monthly contribution for the next year is : 814.447313388721 
	|| total amount :  186976.5280088299
$ 11 ) monthly contribution for the next year is : 855.1696790581572 
	|| total amount :  226262.3301349187
$ 12 ) monthly contribution for the next year is : 897.928163011065 
	|| total amount :  272002.9712261591
$ 13 ) monthly contribution for the next year is : 942.8245711616182 
	|| total amount :  325194.7755596356
$ 14 ) monthly contribution for the next year is : 989.9657997196991 
	|| total amount :  386984.92097561125
$ 15 ) monthly contribution for the next year is : 1039.464089705684 
	|| total amount :  458694.1371580848
$ 16 ) monthly contribution for the next year is : 1091.4372941909685 
	|| total amount :  541842.8121697359
$ 17 ) monthly contribution for the next year is : 1146.009158900517 
	|| total amount :  638181.0186550316
$ 18 ) monthly contribution for the next year is : 1203.309616845543 
	|| total amount :  749723.0478461134
$ 19 ) monthly contribution for the next year is : 1263.4750976878202 
	|| total amount :  878787.127735499
$ 20 ) monthly contribution for the next year is : 1326.6488525722111 
	|| total amount :  1028041.1032439156
$ 21 ) monthly contribution for the next year is : 1392.9812952008217 
	|| total amount :  1200554.9728959994
$ 22 ) monthly contribution for the next year is : 1462.630359960863 
	|| total amount :  1399861.3107041705
$ 23 ) monthly contribution for the next year is : 1535.7618779589063 
	|| total amount :  1630024.7562772557
$ 24 ) monthly contribution for the next year is : 1612.5499718568517 
	|| total amount :  1895721.933634677
$ 25 ) monthly contribution for the next year is : 1693.1774704496945 
	|| total amount :  2202333.363291503
$ 26 ) monthly contribution for the next year is : 1777.836343972179 
	|| total amount :  2556049.166877434
$ 27 ) monthly contribution for the next year is : 1866.7281611707883 
	|| total amount :  2963990.633455865
$ 28 ) monthly contribution for the next year is : 1960.0645692293276 
	|| total amount :  3434350.027098402
$ 29 ) monthly contribution for the next year is : 2058.067797690794 
	|| total amount :  3976551.372218527
$ 30 ) monthly contribution for the next year is : 2160.971187575334 
	|| total amount :  4601435.363659439
$ 31 ) monthly contribution for the next year is : 2269.019746954101 
	|| total amount :  5321472.0205968935
$ 32 ) monthly contribution for the next year is : 2382.470734301806 
	|| total amount :  6151005.246194393
$ 33 ) monthly contribution for the next year is : 2501.594271016896 
	|| total amount :  7106534.079256916
$ 34 ) monthly contribution for the next year is : 2626.673984567741 
	|| total amount :  8207036.142085487
$ 35 ) monthly contribution for the next year is : 2758.0076837961283 
	|| total amount :  9474339.614385342
$ 36 ) monthly contribution for the next year is : 2895.908067985935 
	|| total amount :  10933551.012579529
$ 37 ) monthly contribution for the next year is : 3040.7034713852318 
	|| total amount :  12613547.145804662
$ 38 ) monthly contribution for the next year is : 3192.7386449544933 
	|| total amount :  14547540.875580477
$ 39 ) monthly contribution for the next year is : 3352.3755772022178 
	|| total amount :  16773731.750217916
$ 40 ) monthly contribution for the next year is : 3519.9943560623287 
	|| total amount :  19336054.24571599
$ 41 ) monthly contribution for the next year is : 3695.9940738654454 
	|| total amount :  22285038.254687045
$ 42 ) monthly contribution for the next year is : 3880.793777558718 
	|| total amount :  25678798.66110944
$ 43 ) monthly contribution for the next year is : 4074.833466436654 
	|| total amount :  29584173.36440616
$ 44 ) monthly contribution for the next year is : 4278.575139758487 
	|| total amount :  34078032.020903915
$ 45 ) monthly contribution for the next year is : 4492.503896746412 
	|| total amount :  39248781.11096817
The Total Amount after the age '65' is 39248781.11096817'''

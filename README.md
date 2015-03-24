# dofile-nutrition
*******************************************************
************ Creé en: 06/12/2014**********************
************Dernier modification En: 13/02/2015*******
************ Crer par: Aboubaker**********************
******* Donneé: MIS DIKHIL+OBOCK+DJIBOUTI VILLE*******
************* Pays: DJIBOUTI   ***********************
*******************************************************

****Importation de la base de donnée***
use "D:\addss\travailler cloture 2015\job finalise\Base_de_Traitement.dta", clear

********************Détermination du nombre de sessions*****************

gen nb_session=.

gen i=1


*Je n'ai pas pu trouver une boucle donc j'ai utilisé l'incrémentation de Excel"

il faut introduire une boucle 


replace nb_session=sum(i) if Enfant_Id==6408
replace nb_session=sum(i) if Enfant_Id==6827
replace nb_session=sum(i) if Enfant_Id==6838
replace nb_session=sum(i) if Enfant_Id==6841
replace nb_session=sum(i) if Enfant_Id==7055
replace nb_session=sum(i) if Enfant_Id==7179
replace nb_session=sum(i) if Enfant_Id==7227
replace nb_session=sum(i) if Enfant_Id==7259
replace nb_session=sum(i) if Enfant_Id==7281
replace nb_session=sum(i) if Enfant_Id==7308
replace nb_session=sum(i) if Enfant_Id==7327
replace nb_session=sum(i) if Enfant_Id==7343
replace nb_session=sum(i) if Enfant_Id==7433
replace nb_session=sum(i) if Enfant_Id==7526
replace nb_session=sum(i) if Enfant_Id==7536
replace nb_session=sum(i) if Enfant_Id==7552
replace nb_session=sum(i) if Enfant_Id==7571
replace nb_session=sum(i) if Enfant_Id==7612
replace nb_session=sum(i) if Enfant_Id==7624
replace nb_session=sum(i) if Enfant_Id==7657
replace nb_session=sum(i) if Enfant_Id==7699
replace nb_session=sum(i) if Enfant_Id==7754
replace nb_session=sum(i) if Enfant_Id==7770
replace nb_session=sum(i) if Enfant_Id==7796
replace nb_session=sum(i) if Enfant_Id==7825
replace nb_session=sum(i) if Enfant_Id==7838
replace nb_session=sum(i) if Enfant_Id==7848
replace nb_session=sum(i) if Enfant_Id==8068
replace nb_session=sum(i) if Enfant_Id==8151
replace nb_session=sum(i) if Enfant_Id==8156
replace nb_session=sum(i) if Enfant_Id==8168
replace nb_session=sum(i) if Enfant_Id==8174
replace nb_session=sum(i) if Enfant_Id==8175
replace nb_session=sum(i) if Enfant_Id==8177
replace nb_session=sum(i) if Enfant_Id==8453
replace nb_session=sum(i) if Enfant_Id==8481
replace nb_session=sum(i) if Enfant_Id==8503
replace nb_session=sum(i) if Enfant_Id==8593
replace nb_session=sum(i) if Enfant_Id==8608
replace nb_session=sum(i) if Enfant_Id==8629
replace nb_session=sum(i) if Enfant_Id==8646
replace nb_session=sum(i) if Enfant_Id==8651
replace nb_session=sum(i) if Enfant_Id==8682
replace nb_session=sum(i) if Enfant_Id==9956
replace nb_session=sum(i) if Enfant_Id==10100
replace nb_session=sum(i) if Enfant_Id==10125
replace nb_session=sum(i) if Enfant_Id==10133
replace nb_session=sum(i) if Enfant_Id==10137
replace nb_session=sum(i) if Enfant_Id==10142
replace nb_session=sum(i) if Enfant_Id==10154
replace nb_session=sum(i) if Enfant_Id==10160
replace nb_session=sum(i) if Enfant_Id==10183
replace nb_session=sum(i) if Enfant_Id==11409
replace nb_session=sum(i) if Enfant_Id==15680
replace nb_session=sum(i) if Enfant_Id==15681
replace nb_session=sum(i) if Enfant_Id==15685
replace nb_session=sum(i) if Enfant_Id==15727
replace nb_session=sum(i) if Enfant_Id==15735
replace nb_session=sum(i) if Enfant_Id==15740
replace nb_session=sum(i) if Enfant_Id==15759
replace nb_session=sum(i) if Enfant_Id==15763
replace nb_session=sum(i) if Enfant_Id==15766
replace nb_session=sum(i) if Enfant_Id==15769
replace nb_session=sum(i) if Enfant_Id==15779
replace nb_session=sum(i) if Enfant_Id==15781
replace nb_session=sum(i) if Enfant_Id==15783
replace nb_session=sum(i) if Enfant_Id==15784
replace nb_session=sum(i) if Enfant_Id==15786
replace nb_session=sum(i) if Enfant_Id==15788
replace nb_session=sum(i) if Enfant_Id==15790
replace nb_session=sum(i) if Enfant_Id==15792
replace nb_session=sum(i) if Enfant_Id==15794
replace nb_session=sum(i) if Enfant_Id==15797
replace nb_session=sum(i) if Enfant_Id==15798
replace nb_session=sum(i) if Enfant_Id==15800
replace nb_session=sum(i) if Enfant_Id==15802
replace nb_session=sum(i) if Enfant_Id==15805
replace nb_session=sum(i) if Enfant_Id==15808
replace nb_session=sum(i) if Enfant_Id==15810
replace nb_session=sum(i) if Enfant_Id==15814
replace nb_session=sum(i) if Enfant_Id==15818
replace nb_session=sum(i) if Enfant_Id==15830
replace nb_session=sum(i) if Enfant_Id==15831
replace nb_session=sum(i) if Enfant_Id==15835
replace nb_session=sum(i) if Enfant_Id==15839
replace nb_session=sum(i) if Enfant_Id==15844
replace nb_session=sum(i) if Enfant_Id==15849
replace nb_session=sum(i) if Enfant_Id==15850
replace nb_session=sum(i) if Enfant_Id==15854
replace nb_session=sum(i) if Enfant_Id==15866
replace nb_session=sum(i) if Enfant_Id==15867
replace nb_session=sum(i) if Enfant_Id==15872
replace nb_session=sum(i) if Enfant_Id==15874
replace nb_session=sum(i) if Enfant_Id==15879
replace nb_session=sum(i) if Enfant_Id==15881
replace nb_session=sum(i) if Enfant_Id==15884
replace nb_session=sum(i) if Enfant_Id==15890
replace nb_session=sum(i) if Enfant_Id==15893
replace nb_session=sum(i) if Enfant_Id==15897
replace nb_session=sum(i) if Enfant_Id==15905
replace nb_session=sum(i) if Enfant_Id==15908
replace nb_session=sum(i) if Enfant_Id==15911
replace nb_session=sum(i) if Enfant_Id==15926
replace nb_session=sum(i) if Enfant_Id==15936
replace nb_session=sum(i) if Enfant_Id==15937
replace nb_session=sum(i) if Enfant_Id==15945
replace nb_session=sum(i) if Enfant_Id==15948
replace nb_session=sum(i) if Enfant_Id==15952
replace nb_session=sum(i) if Enfant_Id==15955
replace nb_session=sum(i) if Enfant_Id==15963
replace nb_session=sum(i) if Enfant_Id==15974
replace nb_session=sum(i) if Enfant_Id==15977
replace nb_session=sum(i) if Enfant_Id==15988
replace nb_session=sum(i) if Enfant_Id==15993
replace nb_session=sum(i) if Enfant_Id==15997
replace nb_session=sum(i) if Enfant_Id==15999
replace nb_session=sum(i) if Enfant_Id==16002
replace nb_session=sum(i) if Enfant_Id==16005
replace nb_session=sum(i) if Enfant_Id==16017
replace nb_session=sum(i) if Enfant_Id==16025
replace nb_session=sum(i) if Enfant_Id==16027
replace nb_session=sum(i) if Enfant_Id==16028
replace nb_session=sum(i) if Enfant_Id==16030
replace nb_session=sum(i) if Enfant_Id==16033
replace nb_session=sum(i) if Enfant_Id==16035
replace nb_session=sum(i) if Enfant_Id==16038
replace nb_session=sum(i) if Enfant_Id==16039
replace nb_session=sum(i) if Enfant_Id==16042
replace nb_session=sum(i) if Enfant_Id==16045
replace nb_session=sum(i) if Enfant_Id==16052
replace nb_session=sum(i) if Enfant_Id==16055
replace nb_session=sum(i) if Enfant_Id==16058
replace nb_session=sum(i) if Enfant_Id==16061
replace nb_session=sum(i) if Enfant_Id==16064
replace nb_session=sum(i) if Enfant_Id==16067
replace nb_session=sum(i) if Enfant_Id==16069
replace nb_session=sum(i) if Enfant_Id==16072
replace nb_session=sum(i) if Enfant_Id==16081
replace nb_session=sum(i) if Enfant_Id==16086
replace nb_session=sum(i) if Enfant_Id==16089
replace nb_session=sum(i) if Enfant_Id==16091
replace nb_session=sum(i) if Enfant_Id==16094
replace nb_session=sum(i) if Enfant_Id==16100
replace nb_session=sum(i) if Enfant_Id==16101
replace nb_session=sum(i) if Enfant_Id==16106
replace nb_session=sum(i) if Enfant_Id==16110
replace nb_session=sum(i) if Enfant_Id==16111
replace nb_session=sum(i) if Enfant_Id==16114
replace nb_session=sum(i) if Enfant_Id==16117
replace nb_session=sum(i) if Enfant_Id==16120
replace nb_session=sum(i) if Enfant_Id==16131
replace nb_session=sum(i) if Enfant_Id==16138
replace nb_session=sum(i) if Enfant_Id==16143
replace nb_session=sum(i) if Enfant_Id==16148
replace nb_session=sum(i) if Enfant_Id==16152
replace nb_session=sum(i) if Enfant_Id==16157
replace nb_session=sum(i) if Enfant_Id==16160
replace nb_session=sum(i) if Enfant_Id==16167
replace nb_session=sum(i) if Enfant_Id==16168
replace nb_session=sum(i) if Enfant_Id==16170
replace nb_session=sum(i) if Enfant_Id==16173
replace nb_session=sum(i) if Enfant_Id==16176
replace nb_session=sum(i) if Enfant_Id==16179
replace nb_session=sum(i) if Enfant_Id==16182
replace nb_session=sum(i) if Enfant_Id==16185
replace nb_session=sum(i) if Enfant_Id==16188
replace nb_session=sum(i) if Enfant_Id==16192
replace nb_session=sum(i) if Enfant_Id==16196
replace nb_session=sum(i) if Enfant_Id==16197
replace nb_session=sum(i) if Enfant_Id==16200
replace nb_session=sum(i) if Enfant_Id==16203
replace nb_session=sum(i) if Enfant_Id==16204
replace nb_session=sum(i) if Enfant_Id==16206
replace nb_session=sum(i) if Enfant_Id==16208
replace nb_session=sum(i) if Enfant_Id==16211
replace nb_session=sum(i) if Enfant_Id==16214
replace nb_session=sum(i) if Enfant_Id==16217
replace nb_session=sum(i) if Enfant_Id==16218
replace nb_session=sum(i) if Enfant_Id==16219
replace nb_session=sum(i) if Enfant_Id==16223
replace nb_session=sum(i) if Enfant_Id==16226
replace nb_session=sum(i) if Enfant_Id==16229
replace nb_session=sum(i) if Enfant_Id==16231
replace nb_session=sum(i) if Enfant_Id==16234
replace nb_session=sum(i) if Enfant_Id==16236
replace nb_session=sum(i) if Enfant_Id==16239
replace nb_session=sum(i) if Enfant_Id==16244
replace nb_session=sum(i) if Enfant_Id==16245
replace nb_session=sum(i) if Enfant_Id==16246
replace nb_session=sum(i) if Enfant_Id==16249
replace nb_session=sum(i) if Enfant_Id==16259
replace nb_session=sum(i) if Enfant_Id==16260
replace nb_session=sum(i) if Enfant_Id==16263
replace nb_session=sum(i) if Enfant_Id==16268
replace nb_session=sum(i) if Enfant_Id==16269
replace nb_session=sum(i) if Enfant_Id==16272
replace nb_session=sum(i) if Enfant_Id==16278
replace nb_session=sum(i) if Enfant_Id==16297
replace nb_session=sum(i) if Enfant_Id==16301
replace nb_session=sum(i) if Enfant_Id==16310
replace nb_session=sum(i) if Enfant_Id==16313
replace nb_session=sum(i) if Enfant_Id==16316
replace nb_session=sum(i) if Enfant_Id==16318
replace nb_session=sum(i) if Enfant_Id==16321
replace nb_session=sum(i) if Enfant_Id==16324
replace nb_session=sum(i) if Enfant_Id==16327
replace nb_session=sum(i) if Enfant_Id==16330
replace nb_session=sum(i) if Enfant_Id==16333
replace nb_session=sum(i) if Enfant_Id==16336
replace nb_session=sum(i) if Enfant_Id==16337
replace nb_session=sum(i) if Enfant_Id==16339
replace nb_session=sum(i) if Enfant_Id==16343
replace nb_session=sum(i) if Enfant_Id==16345
replace nb_session=sum(i) if Enfant_Id==16351
replace nb_session=sum(i) if Enfant_Id==16353
replace nb_session=sum(i) if Enfant_Id==16354
replace nb_session=sum(i) if Enfant_Id==16356
replace nb_session=sum(i) if Enfant_Id==16359
replace nb_session=sum(i) if Enfant_Id==16363
replace nb_session=sum(i) if Enfant_Id==16365
replace nb_session=sum(i) if Enfant_Id==16368
replace nb_session=sum(i) if Enfant_Id==16372
replace nb_session=sum(i) if Enfant_Id==16374
replace nb_session=sum(i) if Enfant_Id==16379
replace nb_session=sum(i) if Enfant_Id==16380
replace nb_session=sum(i) if Enfant_Id==16382
replace nb_session=sum(i) if Enfant_Id==16383
replace nb_session=sum(i) if Enfant_Id==16384
replace nb_session=sum(i) if Enfant_Id==16385
replace nb_session=sum(i) if Enfant_Id==16388
replace nb_session=sum(i) if Enfant_Id==16391
replace nb_session=sum(i) if Enfant_Id==16394
replace nb_session=sum(i) if Enfant_Id==16397
replace nb_session=sum(i) if Enfant_Id==16400
replace nb_session=sum(i) if Enfant_Id==16402
replace nb_session=sum(i) if Enfant_Id==16441
replace nb_session=sum(i) if Enfant_Id==16467
replace nb_session=sum(i) if Enfant_Id==16473
replace nb_session=sum(i) if Enfant_Id==16474
replace nb_session=sum(i) if Enfant_Id==16478
replace nb_session=sum(i) if Enfant_Id==16482
replace nb_session=sum(i) if Enfant_Id==16485
replace nb_session=sum(i) if Enfant_Id==16490
replace nb_session=sum(i) if Enfant_Id==16494
replace nb_session=sum(i) if Enfant_Id==16496
replace nb_session=sum(i) if Enfant_Id==16500
replace nb_session=sum(i) if Enfant_Id==16507
replace nb_session=sum(i) if Enfant_Id==16508
replace nb_session=sum(i) if Enfant_Id==16512
replace nb_session=sum(i) if Enfant_Id==16514
replace nb_session=sum(i) if Enfant_Id==16515
replace nb_session=sum(i) if Enfant_Id==16520
replace nb_session=sum(i) if Enfant_Id==16522
replace nb_session=sum(i) if Enfant_Id==16526
replace nb_session=sum(i) if Enfant_Id==16527
replace nb_session=sum(i) if Enfant_Id==16529
replace nb_session=sum(i) if Enfant_Id==16533
replace nb_session=sum(i) if Enfant_Id==16536
replace nb_session=sum(i) if Enfant_Id==16541
replace nb_session=sum(i) if Enfant_Id==16542
replace nb_session=sum(i) if Enfant_Id==16543
replace nb_session=sum(i) if Enfant_Id==16546
replace nb_session=sum(i) if Enfant_Id==16551
replace nb_session=sum(i) if Enfant_Id==16552
replace nb_session=sum(i) if Enfant_Id==16556
replace nb_session=sum(i) if Enfant_Id==16558
replace nb_session=sum(i) if Enfant_Id==16561
replace nb_session=sum(i) if Enfant_Id==16563
replace nb_session=sum(i) if Enfant_Id==16571
replace nb_session=sum(i) if Enfant_Id==16578
replace nb_session=sum(i) if Enfant_Id==16581
replace nb_session=sum(i) if Enfant_Id==16586
replace nb_session=sum(i) if Enfant_Id==16589
replace nb_session=sum(i) if Enfant_Id==16590
replace nb_session=sum(i) if Enfant_Id==16593
replace nb_session=sum(i) if Enfant_Id==16597
replace nb_session=sum(i) if Enfant_Id==16599
replace nb_session=sum(i) if Enfant_Id==16601
replace nb_session=sum(i) if Enfant_Id==16604
replace nb_session=sum(i) if Enfant_Id==16606
replace nb_session=sum(i) if Enfant_Id==16610
replace nb_session=sum(i) if Enfant_Id==16611
replace nb_session=sum(i) if Enfant_Id==16614
replace nb_session=sum(i) if Enfant_Id==16617
replace nb_session=sum(i) if Enfant_Id==16621
replace nb_session=sum(i) if Enfant_Id==16623
replace nb_session=sum(i) if Enfant_Id==16626
replace nb_session=sum(i) if Enfant_Id==16632
replace nb_session=sum(i) if Enfant_Id==16633
replace nb_session=sum(i) if Enfant_Id==16635
replace nb_session=sum(i) if Enfant_Id==16639
replace nb_session=sum(i) if Enfant_Id==16641
replace nb_session=sum(i) if Enfant_Id==16645
replace nb_session=sum(i) if Enfant_Id==16650
replace nb_session=sum(i) if Enfant_Id==16651
replace nb_session=sum(i) if Enfant_Id==16654
replace nb_session=sum(i) if Enfant_Id==16657
replace nb_session=sum(i) if Enfant_Id==16659
replace nb_session=sum(i) if Enfant_Id==16661
replace nb_session=sum(i) if Enfant_Id==16664
replace nb_session=sum(i) if Enfant_Id==16667
replace nb_session=sum(i) if Enfant_Id==16669
replace nb_session=sum(i) if Enfant_Id==16671
replace nb_session=sum(i) if Enfant_Id==16674
replace nb_session=sum(i) if Enfant_Id==16683
replace nb_session=sum(i) if Enfant_Id==16686
replace nb_session=sum(i) if Enfant_Id==16689
replace nb_session=sum(i) if Enfant_Id==16694
replace nb_session=sum(i) if Enfant_Id==16696
replace nb_session=sum(i) if Enfant_Id==16697
replace nb_session=sum(i) if Enfant_Id==16710
replace nb_session=sum(i) if Enfant_Id==16711
replace nb_session=sum(i) if Enfant_Id==16715
replace nb_session=sum(i) if Enfant_Id==16720
replace nb_session=sum(i) if Enfant_Id==16727
replace nb_session=sum(i) if Enfant_Id==16731
replace nb_session=sum(i) if Enfant_Id==16734
replace nb_session=sum(i) if Enfant_Id==16736
replace nb_session=sum(i) if Enfant_Id==16740
replace nb_session=sum(i) if Enfant_Id==16747
replace nb_session=sum(i) if Enfant_Id==16748
replace nb_session=sum(i) if Enfant_Id==16751
replace nb_session=sum(i) if Enfant_Id==16760
replace nb_session=sum(i) if Enfant_Id==16763
replace nb_session=sum(i) if Enfant_Id==16766
replace nb_session=sum(i) if Enfant_Id==16780
replace nb_session=sum(i) if Enfant_Id==16782
replace nb_session=sum(i) if Enfant_Id==16783
replace nb_session=sum(i) if Enfant_Id==16786
replace nb_session=sum(i) if Enfant_Id==16788
replace nb_session=sum(i) if Enfant_Id==16791
replace nb_session=sum(i) if Enfant_Id==16793
replace nb_session=sum(i) if Enfant_Id==16794
replace nb_session=sum(i) if Enfant_Id==16796
replace nb_session=sum(i) if Enfant_Id==16798
replace nb_session=sum(i) if Enfant_Id==16799
replace nb_session=sum(i) if Enfant_Id==16803
replace nb_session=sum(i) if Enfant_Id==16804
replace nb_session=sum(i) if Enfant_Id==16805
replace nb_session=sum(i) if Enfant_Id==16808
replace nb_session=sum(i) if Enfant_Id==16810
replace nb_session=sum(i) if Enfant_Id==16811
replace nb_session=sum(i) if Enfant_Id==16813
replace nb_session=sum(i) if Enfant_Id==16818
replace nb_session=sum(i) if Enfant_Id==16820
replace nb_session=sum(i) if Enfant_Id==16822
replace nb_session=sum(i) if Enfant_Id==16824
replace nb_session=sum(i) if Enfant_Id==16828
replace nb_session=sum(i) if Enfant_Id==16842
replace nb_session=sum(i) if Enfant_Id==16846
replace nb_session=sum(i) if Enfant_Id==16849
replace nb_session=sum(i) if Enfant_Id==16852
replace nb_session=sum(i) if Enfant_Id==16855
replace nb_session=sum(i) if Enfant_Id==16858
replace nb_session=sum(i) if Enfant_Id==16861
replace nb_session=sum(i) if Enfant_Id==16864
replace nb_session=sum(i) if Enfant_Id==16867
replace nb_session=sum(i) if Enfant_Id==16869
replace nb_session=sum(i) if Enfant_Id==16872
replace nb_session=sum(i) if Enfant_Id==16876
replace nb_session=sum(i) if Enfant_Id==16877
replace nb_session=sum(i) if Enfant_Id==16882
replace nb_session=sum(i) if Enfant_Id==16885
replace nb_session=sum(i) if Enfant_Id==16889
replace nb_session=sum(i) if Enfant_Id==16901
replace nb_session=sum(i) if Enfant_Id==16907
replace nb_session=sum(i) if Enfant_Id==16910
replace nb_session=sum(i) if Enfant_Id==16912
replace nb_session=sum(i) if Enfant_Id==16916
replace nb_session=sum(i) if Enfant_Id==16959
replace nb_session=sum(i) if Enfant_Id==16962
replace nb_session=sum(i) if Enfant_Id==16965
replace nb_session=sum(i) if Enfant_Id==16968
replace nb_session=sum(i) if Enfant_Id==16971
replace nb_session=sum(i) if Enfant_Id==16974
replace nb_session=sum(i) if Enfant_Id==16977
replace nb_session=sum(i) if Enfant_Id==16981
replace nb_session=sum(i) if Enfant_Id==16984
replace nb_session=sum(i) if Enfant_Id==16987
replace nb_session=sum(i) if Enfant_Id==17077
replace nb_session=sum(i) if Enfant_Id==17094
replace nb_session=sum(i) if Enfant_Id==17113
replace nb_session=sum(i) if Enfant_Id==17121
replace nb_session=sum(i) if Enfant_Id==17131
replace nb_session=sum(i) if Enfant_Id==17135
replace nb_session=sum(i) if Enfant_Id==17138
replace nb_session=sum(i) if Enfant_Id==17141
replace nb_session=sum(i) if Enfant_Id==17144
replace nb_session=sum(i) if Enfant_Id==17148
replace nb_session=sum(i) if Enfant_Id==17150
replace nb_session=sum(i) if Enfant_Id==17154
replace nb_session=sum(i) if Enfant_Id==17155
replace nb_session=sum(i) if Enfant_Id==17157
replace nb_session=sum(i) if Enfant_Id==17160
replace nb_session=sum(i) if Enfant_Id==17165
replace nb_session=sum(i) if Enfant_Id==17166
replace nb_session=sum(i) if Enfant_Id==17167
replace nb_session=sum(i) if Enfant_Id==17171
replace nb_session=sum(i) if Enfant_Id==17174
replace nb_session=sum(i) if Enfant_Id==17178
replace nb_session=sum(i) if Enfant_Id==17181
replace nb_session=sum(i) if Enfant_Id==17184
replace nb_session=sum(i) if Enfant_Id==17188
replace nb_session=sum(i) if Enfant_Id==17191
replace nb_session=sum(i) if Enfant_Id==17194
replace nb_session=sum(i) if Enfant_Id==17202
replace nb_session=sum(i) if Enfant_Id==17210
replace nb_session=sum(i) if Enfant_Id==17211
replace nb_session=sum(i) if Enfant_Id==17212
replace nb_session=sum(i) if Enfant_Id==17270
replace nb_session=sum(i) if Enfant_Id==17275
replace nb_session=sum(i) if Enfant_Id==17282
replace nb_session=sum(i) if Enfant_Id==17290
replace nb_session=sum(i) if Enfant_Id==17303
replace nb_session=sum(i) if Enfant_Id==17349
replace nb_session=sum(i) if Enfant_Id==17554
replace nb_session=sum(i) if Enfant_Id==17555
replace nb_session=sum(i) if Enfant_Id==17556
replace nb_session=sum(i) if Enfant_Id==17559
replace nb_session=sum(i) if Enfant_Id==17562
replace nb_session=sum(i) if Enfant_Id==17633
replace nb_session=sum(i) if Enfant_Id==17696
replace nb_session=sum(i) if Enfant_Id==17702
replace nb_session=sum(i) if Enfant_Id==17703
replace nb_session=sum(i) if Enfant_Id==17706
replace nb_session=sum(i) if Enfant_Id==17709
replace nb_session=sum(i) if Enfant_Id==17712
replace nb_session=sum(i) if Enfant_Id==17718
replace nb_session=sum(i) if Enfant_Id==17721
replace nb_session=sum(i) if Enfant_Id==17724
replace nb_session=sum(i) if Enfant_Id==17729
replace nb_session=sum(i) if Enfant_Id==17731
replace nb_session=sum(i) if Enfant_Id==17733
replace nb_session=sum(i) if Enfant_Id==17742
replace nb_session=sum(i) if Enfant_Id==17748
replace nb_session=sum(i) if Enfant_Id==17782
replace nb_session=sum(i) if Enfant_Id==17790
replace nb_session=sum(i) if Enfant_Id==17795
replace nb_session=sum(i) if Enfant_Id==17798
replace nb_session=sum(i) if Enfant_Id==17802
replace nb_session=sum(i) if Enfant_Id==17805
replace nb_session=sum(i) if Enfant_Id==17809
replace nb_session=sum(i) if Enfant_Id==17812
replace nb_session=sum(i) if Enfant_Id==17817
replace nb_session=sum(i) if Enfant_Id==17821
replace nb_session=sum(i) if Enfant_Id==17832
replace nb_session=sum(i) if Enfant_Id==17837
replace nb_session=sum(i) if Enfant_Id==17840
replace nb_session=sum(i) if Enfant_Id==17933
replace nb_session=sum(i) if Enfant_Id==17961
replace nb_session=sum(i) if Enfant_Id==17992
replace nb_session=sum(i) if Enfant_Id==18033
replace nb_session=sum(i) if Enfant_Id==18096
replace nb_session=sum(i) if Enfant_Id==18102
replace nb_session=sum(i) if Enfant_Id==18108
replace nb_session=sum(i) if Enfant_Id==18109
replace nb_session=sum(i) if Enfant_Id==18118
replace nb_session=sum(i) if Enfant_Id==18125
replace nb_session=sum(i) if Enfant_Id==18132
replace nb_session=sum(i) if Enfant_Id==18133
replace nb_session=sum(i) if Enfant_Id==18142
replace nb_session=sum(i) if Enfant_Id==18145
replace nb_session=sum(i) if Enfant_Id==18154
replace nb_session=sum(i) if Enfant_Id==18155
replace nb_session=sum(i) if Enfant_Id==18159
replace nb_session=sum(i) if Enfant_Id==18161
replace nb_session=sum(i) if Enfant_Id==18167
replace nb_session=sum(i) if Enfant_Id==18169
replace nb_session=sum(i) if Enfant_Id==18173
replace nb_session=sum(i) if Enfant_Id==18178
replace nb_session=sum(i) if Enfant_Id==18181
replace nb_session=sum(i) if Enfant_Id==18183
replace nb_session=sum(i) if Enfant_Id==18186
replace nb_session=sum(i) if Enfant_Id==18190
replace nb_session=sum(i) if Enfant_Id==18193
replace nb_session=sum(i) if Enfant_Id==18196
replace nb_session=sum(i) if Enfant_Id==18201
replace nb_session=sum(i) if Enfant_Id==18202
replace nb_session=sum(i) if Enfant_Id==18300
replace nb_session=sum(i) if Enfant_Id==18506
replace nb_session=sum(i) if Enfant_Id==18509
replace nb_session=sum(i) if Enfant_Id==18512
replace nb_session=sum(i) if Enfant_Id==18515
replace nb_session=sum(i) if Enfant_Id==18540
replace nb_session=sum(i) if Enfant_Id==18545
replace nb_session=sum(i) if Enfant_Id==18547
replace nb_session=sum(i) if Enfant_Id==18550
replace nb_session=sum(i) if Enfant_Id==18555
replace nb_session=sum(i) if Enfant_Id==18557
replace nb_session=sum(i) if Enfant_Id==18560
replace nb_session=sum(i) if Enfant_Id==18563
replace nb_session=sum(i) if Enfant_Id==18565
replace nb_session=sum(i) if Enfant_Id==18570
replace nb_session=sum(i) if Enfant_Id==18572
replace nb_session=sum(i) if Enfant_Id==18575
replace nb_session=sum(i) if Enfant_Id==18578
replace nb_session=sum(i) if Enfant_Id==18583
replace nb_session=sum(i) if Enfant_Id==18584
replace nb_session=sum(i) if Enfant_Id==18587
replace nb_session=sum(i) if Enfant_Id==18591
replace nb_session=sum(i) if Enfant_Id==18594
replace nb_session=sum(i) if Enfant_Id==18596
replace nb_session=sum(i) if Enfant_Id==18597
replace nb_session=sum(i) if Enfant_Id==18600
replace nb_session=sum(i) if Enfant_Id==18603
replace nb_session=sum(i) if Enfant_Id==18609
replace nb_session=sum(i) if Enfant_Id==18613
replace nb_session=sum(i) if Enfant_Id==18614
replace nb_session=sum(i) if Enfant_Id==18616
replace nb_session=sum(i) if Enfant_Id==18619
replace nb_session=sum(i) if Enfant_Id==18622
replace nb_session=sum(i) if Enfant_Id==18625
replace nb_session=sum(i) if Enfant_Id==18626
replace nb_session=sum(i) if Enfant_Id==18630
replace nb_session=sum(i) if Enfant_Id==18632
replace nb_session=sum(i) if Enfant_Id==18638
replace nb_session=sum(i) if Enfant_Id==18640
replace nb_session=sum(i) if Enfant_Id==18643
replace nb_session=sum(i) if Enfant_Id==18647
replace nb_session=sum(i) if Enfant_Id==18654
replace nb_session=sum(i) if Enfant_Id==18656
replace nb_session=sum(i) if Enfant_Id==18658
replace nb_session=sum(i) if Enfant_Id==18662
replace nb_session=sum(i) if Enfant_Id==18664
replace nb_session=sum(i) if Enfant_Id==18668
replace nb_session=sum(i) if Enfant_Id==18673
replace nb_session=sum(i) if Enfant_Id==18680
replace nb_session=sum(i) if Enfant_Id==18685
replace nb_session=sum(i) if Enfant_Id==18687
replace nb_session=sum(i) if Enfant_Id==18689
replace nb_session=sum(i) if Enfant_Id==18692
replace nb_session=sum(i) if Enfant_Id==18696
replace nb_session=sum(i) if Enfant_Id==18699
replace nb_session=sum(i) if Enfant_Id==18707
replace nb_session=sum(i) if Enfant_Id==18711
replace nb_session=sum(i) if Enfant_Id==18714
replace nb_session=sum(i) if Enfant_Id==18725
replace nb_session=sum(i) if Enfant_Id==18727
replace nb_session=sum(i) if Enfant_Id==18733
replace nb_session=sum(i) if Enfant_Id==18738
replace nb_session=sum(i) if Enfant_Id==18742
replace nb_session=sum(i) if Enfant_Id==18818
replace nb_session=sum(i) if Enfant_Id==18878
replace nb_session=sum(i) if Enfant_Id==18881
replace nb_session=sum(i) if Enfant_Id==18884
replace nb_session=sum(i) if Enfant_Id==18887
replace nb_session=sum(i) if Enfant_Id==18890
replace nb_session=sum(i) if Enfant_Id==18893
replace nb_session=sum(i) if Enfant_Id==18896
replace nb_session=sum(i) if Enfant_Id==19285
replace nb_session=sum(i) if Enfant_Id==19293
replace nb_session=sum(i) if Enfant_Id==19304
replace nb_session=sum(i) if Enfant_Id==19310
replace nb_session=sum(i) if Enfant_Id==19372
replace nb_session=sum(i) if Enfant_Id==19377
replace nb_session=sum(i) if Enfant_Id==19404
replace nb_session=sum(i) if Enfant_Id==19407
replace nb_session=sum(i) if Enfant_Id==19412
replace nb_session=sum(i) if Enfant_Id==19415
replace nb_session=sum(i) if Enfant_Id==19418
replace nb_session=sum(i) if Enfant_Id==19422
replace nb_session=sum(i) if Enfant_Id==19427
replace nb_session=sum(i) if Enfant_Id==19431
replace nb_session=sum(i) if Enfant_Id==19434
replace nb_session=sum(i) if Enfant_Id==19441
replace nb_session=sum(i) if Enfant_Id==19627
replace nb_session=sum(i) if Enfant_Id==19813
replace nb_session=sum(i) if Enfant_Id==20031
replace nb_session=sum(i) if Enfant_Id==20041
replace nb_session=sum(i) if Enfant_Id==20044
replace nb_session=sum(i) if Enfant_Id==20047
replace nb_session=sum(i) if Enfant_Id==20050
replace nb_session=sum(i) if Enfant_Id==20088
replace nb_session=sum(i) if Enfant_Id==20106
replace nb_session=sum(i) if Enfant_Id==20137
replace nb_session=sum(i) if Enfant_Id==20141
replace nb_session=sum(i) if Enfant_Id==20150
replace nb_session=sum(i) if Enfant_Id==20220
replace nb_session=sum(i) if Enfant_Id==20234
replace nb_session=sum(i) if Enfant_Id==20236
replace nb_session=sum(i) if Enfant_Id==20243
replace nb_session=sum(i) if Enfant_Id==20244
replace nb_session=sum(i) if Enfant_Id==20257
replace nb_session=sum(i) if Enfant_Id==20268
replace nb_session=sum(i) if Enfant_Id==20427
replace nb_session=sum(i) if Enfant_Id==20465
replace nb_session=sum(i) if Enfant_Id==20539
replace nb_session=sum(i) if Enfant_Id==20659
replace nb_session=sum(i) if Enfant_Id==20671
replace nb_session=sum(i) if Enfant_Id==20700
replace nb_session=sum(i) if Enfant_Id==20712
replace nb_session=sum(i) if Enfant_Id==23601
replace nb_session=sum(i) if Enfant_Id==23602
replace nb_session=sum(i) if Enfant_Id==23664
replace nb_session=sum(i) if Enfant_Id==23668
replace nb_session=sum(i) if Enfant_Id==23678
replace nb_session=sum(i) if Enfant_Id==23686
replace nb_session=sum(i) if Enfant_Id==23733
replace nb_session=sum(i) if Enfant_Id==23735
replace nb_session=sum(i) if Enfant_Id==23737
replace nb_session=sum(i) if Enfant_Id==23739
replace nb_session=sum(i) if Enfant_Id==23741
replace nb_session=sum(i) if Enfant_Id==23743
replace nb_session=sum(i) if Enfant_Id==23745
replace nb_session=sum(i) if Enfant_Id==23747
replace nb_session=sum(i) if Enfant_Id==23749
replace nb_session=sum(i) if Enfant_Id==23751
replace nb_session=sum(i) if Enfant_Id==23753
replace nb_session=sum(i) if Enfant_Id==23755
replace nb_session=sum(i) if Enfant_Id==23761
replace nb_session=sum(i) if Enfant_Id==23763
replace nb_session=sum(i) if Enfant_Id==23765
replace nb_session=sum(i) if Enfant_Id==23767
replace nb_session=sum(i) if Enfant_Id==23769
replace nb_session=sum(i) if Enfant_Id==23771
replace nb_session=sum(i) if Enfant_Id==23791
replace nb_session=sum(i) if Enfant_Id==23793
replace nb_session=sum(i) if Enfant_Id==23795
replace nb_session=sum(i) if Enfant_Id==23797
replace nb_session=sum(i) if Enfant_Id==23799
replace nb_session=sum(i) if Enfant_Id==23801
replace nb_session=sum(i) if Enfant_Id==23803
replace nb_session=sum(i) if Enfant_Id==23805
replace nb_session=sum(i) if Enfant_Id==23807
replace nb_session=sum(i) if Enfant_Id==23809
replace nb_session=sum(i) if Enfant_Id==23815
replace nb_session=sum(i) if Enfant_Id==23818
replace nb_session=sum(i) if Enfant_Id==23825
replace nb_session=sum(i) if Enfant_Id==23829
replace nb_session=sum(i) if Enfant_Id==23833
replace nb_session=sum(i) if Enfant_Id==23839
replace nb_session=sum(i) if Enfant_Id==23843
replace nb_session=sum(i) if Enfant_Id==23893
replace nb_session=sum(i) if Enfant_Id==23895
replace nb_session=sum(i) if Enfant_Id==23901
replace nb_session=sum(i) if Enfant_Id==23902
replace nb_session=sum(i) if Enfant_Id==23908
replace nb_session=sum(i) if Enfant_Id==23912
replace nb_session=sum(i) if Enfant_Id==23913
replace nb_session=sum(i) if Enfant_Id==23918
replace nb_session=sum(i) if Enfant_Id==23921
replace nb_session=sum(i) if Enfant_Id==23925
replace nb_session=sum(i) if Enfant_Id==23932
replace nb_session=sum(i) if Enfant_Id==23933
replace nb_session=sum(i) if Enfant_Id==23938
replace nb_session=sum(i) if Enfant_Id==23963
replace nb_session=sum(i) if Enfant_Id==23965
replace nb_session=sum(i) if Enfant_Id==23969
replace nb_session=sum(i) if Enfant_Id==23974
replace nb_session=sum(i) if Enfant_Id==23978
replace nb_session=sum(i) if Enfant_Id==23980
replace nb_session=sum(i) if Enfant_Id==23982
replace nb_session=sum(i) if Enfant_Id==23984
replace nb_session=sum(i) if Enfant_Id==23985
replace nb_session=sum(i) if Enfant_Id==23987
replace nb_session=sum(i) if Enfant_Id==23990
replace nb_session=sum(i) if Enfant_Id==24076
replace nb_session=sum(i) if Enfant_Id==24081
replace nb_session=sum(i) if Enfant_Id==24083
replace nb_session=sum(i) if Enfant_Id==24087
replace nb_session=sum(i) if Enfant_Id==24091
replace nb_session=sum(i) if Enfant_Id==24093
replace nb_session=sum(i) if Enfant_Id==24099
replace nb_session=sum(i) if Enfant_Id==24101
replace nb_session=sum(i) if Enfant_Id==24107
replace nb_session=sum(i) if Enfant_Id==24113
replace nb_session=sum(i) if Enfant_Id==24117
replace nb_session=sum(i) if Enfant_Id==24119
replace nb_session=sum(i) if Enfant_Id==24122
replace nb_session=sum(i) if Enfant_Id==24207
replace nb_session=sum(i) if Enfant_Id==24210
replace nb_session=sum(i) if Enfant_Id==24221
replace nb_session=sum(i) if Enfant_Id==24225
replace nb_session=sum(i) if Enfant_Id==24235
replace nb_session=sum(i) if Enfant_Id==24237
replace nb_session=sum(i) if Enfant_Id==24239
replace nb_session=sum(i) if Enfant_Id==24241
replace nb_session=sum(i) if Enfant_Id==24301
replace nb_session=sum(i) if Enfant_Id==24303
replace nb_session=sum(i) if Enfant_Id==24305
replace nb_session=sum(i) if Enfant_Id==24313
replace nb_session=sum(i) if Enfant_Id==24315
replace nb_session=sum(i) if Enfant_Id==24317
replace nb_session=sum(i) if Enfant_Id==24319
replace nb_session=sum(i) if Enfant_Id==24321
replace nb_session=sum(i) if Enfant_Id==24325
replace nb_session=sum(i) if Enfant_Id==24327
replace nb_session=sum(i) if Enfant_Id==24857
replace nb_session=sum(i) if Enfant_Id==24918
replace nb_session=sum(i) if Enfant_Id==24937
replace nb_session=sum(i) if Enfant_Id==25009
replace nb_session=sum(i) if Enfant_Id==25277
replace nb_session=sum(i) if Enfant_Id==25832
replace nb_session=sum(i) if Enfant_Id==25834
replace nb_session=sum(i) if Enfant_Id==25838
replace nb_session=sum(i) if Enfant_Id==25843
replace nb_session=sum(i) if Enfant_Id==25845
replace nb_session=sum(i) if Enfant_Id==25847
replace nb_session=sum(i) if Enfant_Id==25849
replace nb_session=sum(i) if Enfant_Id==25851
replace nb_session=sum(i) if Enfant_Id==25853
replace nb_session=sum(i) if Enfant_Id==25858
replace nb_session=sum(i) if Enfant_Id==25859
replace nb_session=sum(i) if Enfant_Id==25861
replace nb_session=sum(i) if Enfant_Id==25864
replace nb_session=sum(i) if Enfant_Id==25865
replace nb_session=sum(i) if Enfant_Id==25867
replace nb_session=sum(i) if Enfant_Id==25869
replace nb_session=sum(i) if Enfant_Id==25872
replace nb_session=sum(i) if Enfant_Id==25873
replace nb_session=sum(i) if Enfant_Id==25875
replace nb_session=sum(i) if Enfant_Id==25879
replace nb_session=sum(i) if Enfant_Id==25883
replace nb_session=sum(i) if Enfant_Id==25888
replace nb_session=sum(i) if Enfant_Id==25889
replace nb_session=sum(i) if Enfant_Id==25892
replace nb_session=sum(i) if Enfant_Id==25893
replace nb_session=sum(i) if Enfant_Id==25897
replace nb_session=sum(i) if Enfant_Id==25900
replace nb_session=sum(i) if Enfant_Id==25903
replace nb_session=sum(i) if Enfant_Id==25905
replace nb_session=sum(i) if Enfant_Id==25906
replace nb_session=sum(i) if Enfant_Id==25908
replace nb_session=sum(i) if Enfant_Id==25911
replace nb_session=sum(i) if Enfant_Id==25912
replace nb_session=sum(i) if Enfant_Id==25916
replace nb_session=sum(i) if Enfant_Id==25919
replace nb_session=sum(i) if Enfant_Id==25921
replace nb_session=sum(i) if Enfant_Id==25923
replace nb_session=sum(i) if Enfant_Id==25926
replace nb_session=sum(i) if Enfant_Id==25928
replace nb_session=sum(i) if Enfant_Id==25932
replace nb_session=sum(i) if Enfant_Id==25934
replace nb_session=sum(i) if Enfant_Id==25936
replace nb_session=sum(i) if Enfant_Id==25938
replace nb_session=sum(i) if Enfant_Id==25941
replace nb_session=sum(i) if Enfant_Id==25943
replace nb_session=sum(i) if Enfant_Id==25946
replace nb_session=sum(i) if Enfant_Id==25948
replace nb_session=sum(i) if Enfant_Id==26006
replace nb_session=sum(i) if Enfant_Id==26008
replace nb_session=sum(i) if Enfant_Id==26010
replace nb_session=sum(i) if Enfant_Id==26012
replace nb_session=sum(i) if Enfant_Id==26014
replace nb_session=sum(i) if Enfant_Id==26150
replace nb_session=sum(i) if Enfant_Id==26151
replace nb_session=sum(i) if Enfant_Id==26188
replace nb_session=sum(i) if Enfant_Id==28046
replace nb_session=sum(i) if Enfant_Id==28064
replace nb_session=sum(i) if Enfant_Id==28065
replace nb_session=sum(i) if Enfant_Id==28066
replace nb_session=sum(i) if Enfant_Id==28069
replace nb_session=sum(i) if Enfant_Id==28070
replace nb_session=sum(i) if Enfant_Id==28071
replace nb_session=sum(i) if Enfant_Id==28073
replace nb_session=sum(i) if Enfant_Id==28074
replace nb_session=sum(i) if Enfant_Id==28075
replace nb_session=sum(i) if Enfant_Id==28076
replace nb_session=sum(i) if Enfant_Id==28078
replace nb_session=sum(i) if Enfant_Id==28079
replace nb_session=sum(i) if Enfant_Id==28081
replace nb_session=sum(i) if Enfant_Id==28084
replace nb_session=sum(i) if Enfant_Id==28085
replace nb_session=sum(i) if Enfant_Id==28086
replace nb_session=sum(i) if Enfant_Id==28088
replace nb_session=sum(i) if Enfant_Id==28092
replace nb_session=sum(i) if Enfant_Id==28095
replace nb_session=sum(i) if Enfant_Id==28097
replace nb_session=sum(i) if Enfant_Id==28100
replace nb_session=sum(i) if Enfant_Id==28103
replace nb_session=sum(i) if Enfant_Id==28105
replace nb_session=sum(i) if Enfant_Id==28106
replace nb_session=sum(i) if Enfant_Id==28112
replace nb_session=sum(i) if Enfant_Id==28114
replace nb_session=sum(i) if Enfant_Id==28115
replace nb_session=sum(i) if Enfant_Id==28116
replace nb_session=sum(i) if Enfant_Id==28118
replace nb_session=sum(i) if Enfant_Id==28119
replace nb_session=sum(i) if Enfant_Id==28120
replace nb_session=sum(i) if Enfant_Id==28121
replace nb_session=sum(i) if Enfant_Id==28122
replace nb_session=sum(i) if Enfant_Id==28123
replace nb_session=sum(i) if Enfant_Id==28127
replace nb_session=sum(i) if Enfant_Id==28128
replace nb_session=sum(i) if Enfant_Id==28129
replace nb_session=sum(i) if Enfant_Id==28131
replace nb_session=sum(i) if Enfant_Id==28134
replace nb_session=sum(i) if Enfant_Id==28135
replace nb_session=sum(i) if Enfant_Id==28138
replace nb_session=sum(i) if Enfant_Id==28143
replace nb_session=sum(i) if Enfant_Id==28144
replace nb_session=sum(i) if Enfant_Id==28145
replace nb_session=sum(i) if Enfant_Id==28146
replace nb_session=sum(i) if Enfant_Id==28147
replace nb_session=sum(i) if Enfant_Id==28148
replace nb_session=sum(i) if Enfant_Id==28151
replace nb_session=sum(i) if Enfant_Id==28153
replace nb_session=sum(i) if Enfant_Id==28194
replace nb_session=sum(i) if Enfant_Id==28197
replace nb_session=sum(i) if Enfant_Id==28198
replace nb_session=sum(i) if Enfant_Id==28199
replace nb_session=sum(i) if Enfant_Id==28200
replace nb_session=sum(i) if Enfant_Id==28201
replace nb_session=sum(i) if Enfant_Id==28202
replace nb_session=sum(i) if Enfant_Id==28205
replace nb_session=sum(i) if Enfant_Id==28206
replace nb_session=sum(i) if Enfant_Id==28207
replace nb_session=sum(i) if Enfant_Id==28208
replace nb_session=sum(i) if Enfant_Id==28209
replace nb_session=sum(i) if Enfant_Id==28210
replace nb_session=sum(i) if Enfant_Id==28212
replace nb_session=sum(i) if Enfant_Id==28218
replace nb_session=sum(i) if Enfant_Id==28305
replace nb_session=sum(i) if Enfant_Id==28308
replace nb_session=sum(i) if Enfant_Id==28320
replace nb_session=sum(i) if Enfant_Id==28699
replace nb_session=sum(i) if Enfant_Id==28701
replace nb_session=sum(i) if Enfant_Id==45031
replace nb_session=sum(i) if Enfant_Id==45039
replace nb_session=sum(i) if Enfant_Id==45056
replace nb_session=sum(i) if Enfant_Id==45061
replace nb_session=sum(i) if Enfant_Id==45571
replace nb_session=sum(i) if Enfant_Id==45976

drop i

******************************************************************************************

*************************DJIBOUTI *******************************

keep if region =="DJIBOUTI"
table quartier sexe
table quartier foyer
table quartier foyer anne_visite

****** SECTEUR HAYABLEY****
keep if quartier == "HAYABLEY"
table quartier site
table foyer anne_visite
table foyer anne_visite
table foyer anne_visite site
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "FILLE"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "Garçon"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
*Nombre de session moyenne saisie par enfant suivant les sites
tabstat nb_session, statistics( mean ) by(site) columns(variables)
*Nombre de session moyenne saisie par enfant suivant les foyers
tabstat nb_session, statistics( mean ) by( foyer) columns(variables)

*** vaccins &  maux****
table rougeole anne_visite foyer if rougeole==1
table BCGPo0HeB anne_visite foyer if BCGPo0HeB==1
table Pent1Po1Pneu1 anne_visite foyer if Pent1Po1Pneu1==1
table Pent2Po2Pneu2 anne_visite foyer if Pent2Po2Pneu2==1
table Pent3Po3Pneu3 anne_visite foyer if Pent3Po3Pneu3==1
table dtcp_15 anne_visite foyer if dtcp_15==1
table dtcp_59 anne_visite foyer if dtcp_59==1
table toux anne_visite foyer if toux==1
table Fievré anne_visite foyer if Fievré==1
table diarrhee anne_visite foyer if diarrhee==1
table Anémie anne_visite foyer if Anémie==1
table Paleur anne_visite foyer if Paleur==1
 
****** SECTEUR  ARHIBA******
keep if quartier == "ARHIBA"
table foyer anne_visite site
table quartier site
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "FILLE"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "Garçon"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
*Nombre de session moyenne saisie par enfant suivant les sites
tabstat nb_session, statistics( mean ) by(site) columns(variables)
*Nombre de session moyenne saisie par enfant suivant les foyers
tabstat nb_session, statistics( mean ) by( foyer) columns(variables)

*** vaccins & maux ****
table rougeole anne_visite foyer if rougeole==1
table BCGPo0HeB anne_visite foyer if BCGPo0HeB==1
table Pent1Po1Pneu1 anne_visite foyer if Pent1Po1Pneu1==1
table Pent2Po2Pneu2 anne_visite foyer if Pent2Po2Pneu2==1
table Pent3Po3Pneu3 anne_visite foyer if Pent3Po3Pneu3==1
table dtcp_15 anne_visite foyer if dtcp_15==1
table dtcp_59 anne_visite foyer if dtcp_59==1
table toux anne_visite foyer if toux==1
table Fievré anne_visite foyer if Fievré==1
table diarrhee anne_visite foyer if diarrhee==1
table Anémie anne_visite foyer if Anémie==1
table Paleur anne_visite foyer if Paleur==1

 
****** SECTEUR MOUSTIQUAIRE ******
keep if quartier == "MOUSTIQUAIRE"
table foyer anne_visite
table quartier site
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "FILLE"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "Garçon"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
*Nombre de session moyenne saisie par enfant suivant les sites
tabstat nb_session, statistics( mean ) by(site) columns(variables)
*Nombre de session moyenne saisie par enfant suivant les foyers
tabstat nb_session, statistics( mean ) by( foyer) columns(variables)

*** vaccins & maux ****
table rougeole anne_visite foyer if rougeole==1
table BCGPo0HeB anne_visite foyer if BCGPo0HeB==1
table Pent1Po1Pneu1 anne_visite foyer if Pent1Po1Pneu1==1
table Pent2Po2Pneu2 anne_visite foyer if Pent2Po2Pneu2==1
table Pent3Po3Pneu3 anne_visite foyer if Pent3Po3Pneu3==1
table dtcp_15 anne_visite foyer if dtcp_15==1
table dtcp_59 anne_visite foyer if dtcp_59==1
table toux anne_visite foyer if toux==1
table Fievré anne_visite foyer if Fievré==1
table diarrhee anne_visite foyer if diarrhee==1
table Anémie anne_visite foyer if Anémie==1
table Paleur anne_visite foyer if Paleur==1
 
****** SECTEUR Q5 ******
keep if quartier == "Q5"
table foyer anne_visite
table quartier site
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "FILLE"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "Garçon"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
*Nombre de session moyenne saisie par enfant suivant les sites
tabstat nb_session, statistics( mean ) by(site) columns(variables)
*Nombre de session moyenne saisie par enfant suivant les foyers
tabstat nb_session, statistics( mean ) by( foyer) columns(variables)
*** vaccins & maux ****
table rougeole anne_visite foyer if rougeole==1
table BCGPo0HeB anne_visite foyer if BCGPo0HeB==1
table Pent1Po1Pneu1 anne_visite foyer if Pent1Po1Pneu1==1
table Pent2Po2Pneu2 anne_visite foyer if Pent2Po2Pneu2==1
table Pent3Po3Pneu3 anne_visite foyer if Pent3Po3Pneu3==1
table dtcp_15 anne_visite foyer if dtcp_15==1
table dtcp_59 anne_visite foyer if dtcp_59==1
table toux anne_visite foyer if toux==1
table Fievré anne_visite foyer if Fievré==1
table diarrhee anne_visite foyer if diarrhee==1
table Anémie anne_visite foyer if Anémie==1
table Paleur anne_visite foyer if Paleur==1


******************** REGION DE  DIKHIL *********************
  
keep if region =="DIKHIL"
table quartier sexe
table quartier foyer
table quartier foyer anne_visite

****** SECTEUR CHEIK MANDAYTE****

keep if quartier == "CHEIK MaNdayte"
table foyer anne_visite
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "FILLE"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "Garçon"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm

*Nombre de session moyenne saisie par enfant suivant les foyers
tabstat nb_session, statistics( mean ) by( foyer) columns(variables)

*** vaccins & maux ****
table rougeole anne_visite foyer if rougeole==1
table BCGPo0HeB anne_visite foyer if BCGPo0HeB==1
table Pent1Po1Pneu1 anne_visite foyer if Pent1Po1Pneu1==1
table Pent2Po2Pneu2 anne_visite foyer if Pent2Po2Pneu2==1
table Pent3Po3Pneu3 anne_visite foyer if Pent3Po3Pneu3==1
table dtcp_15 anne_visite foyer if dtcp_15==1
table dtcp_59 anne_visite foyer if dtcp_59==1
table toux anne_visite foyer if toux==1
table Fievré anne_visite foyer if Fievré==1
table diarrhee anne_visite foyer if diarrhee==1
table Anémie anne_visite foyer if Anémie==1
table Paleur anne_visite foyer if Paleur==1
 
 
 ***** SECTEUR CAR ( cheik issa) *****
 
keep if quartier == " CAR(cheik issa) "
table foyer anne_visite
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "FILLE"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "Garçon"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm

*Nombre de session moyenne saisie par enfant suivant les foyers
tabstat nb_session, statistics( mean ) by( foyer) columns(variables)


*** vaccins & maux ****
table rougeole anne_visite foyer if rougeole==1
table BCGPo0HeB anne_visite foyer if BCGPo0HeB==1
table Pent1Po1Pneu1 anne_visite foyer if Pent1Po1Pneu1==1
table Pent2Po2Pneu2 anne_visite foyer if Pent2Po2Pneu2==1
table Pent3Po3Pneu3 anne_visite foyer if Pent3Po3Pneu3==1
table dtcp_15 anne_visite foyer if dtcp_15==1
table dtcp_59 anne_visite foyer if dtcp_59==1
table toux anne_visite foyer if toux==1
table Fievré anne_visite foyer if Fievré==1
table diarrhee anne_visite foyer if diarrhee==1
table Anémie anne_visite foyer if Anémie==1
table Paleur anne_visite foyer if Paleur==1

*****  SECTEUR EDD*****
 
keep if quartier == "EDD"
table foyer anne_visite
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "FILLE"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "Garçon"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm

*Nombre de session moyenne saisie par enfant suivant les foyers
tabstat nb_session, statistics( mean ) by( foyer) columns(variables)

*** vaccins & maux ****
table rougeole anne_visite foyer if rougeole==1
table BCGPo0HeB anne_visite foyer if BCGPo0HeB==1
table Pent1Po1Pneu1 anne_visite foyer if Pent1Po1Pneu1==1
table Pent2Po2Pneu2 anne_visite foyer if Pent2Po2Pneu2==1
table Pent3Po3Pneu3 anne_visite foyer if Pent3Po3Pneu3==1
table dtcp_15 anne_visite foyer if dtcp_15==1
table dtcp_59 anne_visite foyer if dtcp_59==1
table toux anne_visite foyer if toux==1
table Fievré anne_visite foyer if Fievré==1
table diarrhee anne_visite foyer if diarrhee==1
table Anémie anne_visite foyer if Anémie==1
table Paleur anne_visite foyer if Paleur==1
 

 *****  SECTEUR HAROU *****
keep if quartier == "HAROU"
table quartier site
table quartier foyer
table foyer anne_visite site
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "FILLE"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "Garçon"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm

*Nombre de session moyenne saisie par enfant suivant les sites
tabstat nb_session, statistics( mean ) by(site) columns(variables)
*Nombre de session moyenne saisie par enfant suivant les foyers
tabstat nb_session, statistics( mean ) by( foyer) columns(variables)

*** vaccins & maux ****
table rougeole anne_visite foyer if rougeole==1
table BCGPo0HeB anne_visite foyer if BCGPo0HeB==1
table Pent1Po1Pneu1 anne_visite foyer if Pent1Po1Pneu1==1
table Pent2Po2Pneu2 anne_visite foyer if Pent2Po2Pneu2==1
table Pent3Po3Pneu3 anne_visite foyer if Pent3Po3Pneu3==1
table dtcp_15 anne_visite foyer if dtcp_15==1
table dtcp_59 anne_visite foyer if dtcp_59==1
table toux anne_visite foyer if toux==1
table Fievré anne_visite foyer if Fievré==1
table diarrhee anne_visite foyer if diarrhee==1
table Anémie anne_visite foyer if Anémie==1
table Paleur anne_visite foyer if Paleur==1

***** secteur ILJANO******
 
keep if quartier == "ILJANO"
table foyer anne_visite
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "FILLE"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "Garçon"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm


*Nombre de session moyenne saisie par enfant suivant les foyers
tabstat nb_session, statistics( mean ) by( foyer) columns(variables)

*** vaccins & maux ****
table rougeole anne_visite foyer if rougeole==1
table BCGPo0HeB anne_visite foyer if BCGPo0HeB==1
table Pent1Po1Pneu1 anne_visite foyer if Pent1Po1Pneu1==1
table Pent2Po2Pneu2 anne_visite foyer if Pent2Po2Pneu2==1
table Pent3Po3Pneu3 anne_visite foyer if Pent3Po3Pneu3==1
table dtcp_15 anne_visite foyer if dtcp_15==1
table dtcp_59 anne_visite foyer if dtcp_59==1
table toux anne_visite foyer if toux==1
table Fievré anne_visite foyer if Fievré==1
table diarrhee anne_visite foyer if diarrhee==1
table Anémie anne_visite foyer if Anémie==1
table Paleur anne_visite foyer if Paleur==1

********* SECTEUR OKARE ******

keep if quartier == "OKARE"
table foyer anne_visite
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "FILLE"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "Garçon"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm


*Nombre de session moyenne saisie par enfant suivant les foyers
tabstat nb_session, statistics( mean ) by( foyer) columns(variables)

*** vaccins & maux ****

table rougeole anne_visite foyer if rougeole==1
table BCGPo0HeB anne_visite foyer if BCGPo0HeB==1
table Pent1Po1Pneu1 anne_visite foyer if Pent1Po1Pneu1==1
table Pent2Po2Pneu2 anne_visite foyer if Pent2Po2Pneu2==1
table Pent3Po3Pneu3 anne_visite foyer if Pent3Po3Pneu3==1
table dtcp_15 anne_visite foyer if dtcp_15==1
table dtcp_59 anne_visite foyer if dtcp_59==1
table toux anne_visite foyer if toux==1
table Fievré anne_visite foyer if Fievré==1
table diarrhee anne_visite foyer if diarrhee==1
table Anémie anne_visite foyer if Anémie==1
table Paleur anne_visite foyer if Paleur==1
  
 ************** SECTEUR QUARTIER3**********
 
keep if quartier == "QUARTIER3"
table foyer anne_visite
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "FILLE"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "Garçon"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm


*Nombre de session moyenne saisie par enfant suivant les foyers
tabstat nb_session, statistics( mean ) by( foyer) columns(variables)

*** vaccins & maux ****
table rougeole anne_visite foyer if rougeole==1
table BCGPo0HeB anne_visite foyer if BCGPo0HeB==1
table Pent1Po1Pneu1 anne_visite foyer if Pent1Po1Pneu1==1
table Pent2Po2Pneu2 anne_visite foyer if Pent2Po2Pneu2==1
table Pent3Po3Pneu3 anne_visite foyer if Pent3Po3Pneu3==1
table dtcp_15 anne_visite foyer if dtcp_15==1
table dtcp_59 anne_visite foyer if dtcp_59==1
table toux anne_visite foyer if toux==1
table Fievré anne_visite foyer if Fievré==1
table diarrhee anne_visite foyer if diarrhee==1
table Anémie anne_visite foyer if Anémie==1
table Paleur anne_visite foyer if Paleur==1

 ************ SECTEUR TP ******
 
keep if quartier == "TP"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "FILLE"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "Garçon"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm


*Nombre de session moyenne saisie par enfant suivant les foyers
tabstat nb_session, statistics( mean ) by( foyer) columns(variables)

*** vaccins & maux ****
table rougeole anne_visite foyer if rougeole==1
table BCGPo0HeB anne_visite foyer if BCGPo0HeB==1
table Pent1Po1Pneu1 anne_visite foyer if Pent1Po1Pneu1==1
table Pent2Po2Pneu2 anne_visite foyer if Pent2Po2Pneu2==1
table Pent3Po3Pneu3 anne_visite foyer if Pent3Po3Pneu3==1
table dtcp_15 anne_visite foyer if dtcp_15==1
table dtcp_59 anne_visite foyer if dtcp_59==1
table toux anne_visite foyer if toux==1
table Fievré anne_visite foyer if Fievré==1
table diarrhee anne_visite foyer if diarrhee==1
table Anémie anne_visite foyer if Anémie==1
table Paleur anne_visite foyer if Paleur==1

***** SECTEUR TP GAMI *****

keep if quartier == "TP GAMI"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "FILLE"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "Garçon"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm


*Nombre de session moyenne saisie par enfant suivant les foyers
tabstat nb_session, statistics( mean ) by( foyer) columns(variables)

*** vaccins & maux ****
table rougeole anne_visite foyer if rougeole==1
table BCGPo0HeB anne_visite foyer if BCGPo0HeB==1
table Pent1Po1Pneu1 anne_visite foyer if Pent1Po1Pneu1==1
table Pent2Po2Pneu2 anne_visite foyer if Pent2Po2Pneu2==1
table Pent3Po3Pneu3 anne_visite foyer if Pent3Po3Pneu3==1
table dtcp_15 anne_visite foyer if dtcp_15==1
table dtcp_59 anne_visite foyer if dtcp_59==1
table toux anne_visite foyer if toux==1
table Fievré anne_visite foyer if Fievré==1
table diarrhee anne_visite foyer if diarrhee==1
table Anémie anne_visite foyer if Anémie==1
table Paleur anne_visite foyer if Paleur==1

************** REGION D'OBOCK *******
keep if region == "OBOCK"
table quartier sexe
table quartier foyer
table quartier foyer anne_visite 
keep if sexe == "FILLE"
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "Garçon"
codebook Poids_KG Taille_CM IMCkmm


*Nombre de session moyenne saisie par enfant suivant les foyers
tabstat nb_session, statistics( mean ) by( foyer) columns(variables)

***** SECTEUR BAD *****

keep if quartier == "BAD"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "FILLE"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "Garçon"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm


*Nombre de session moyenne saisie par enfant suivant les foyers
tabstat nb_session, statistics( mean ) by( foyer) columns(variables)

*** vaccins & maux ****
table rougeole anne_visite foyer if rougeole==1
table BCGPo0HeB anne_visite foyer if BCGPo0HeB==1
table Pent1Po1Pneu1 anne_visite foyer if Pent1Po1Pneu1==1
table Pent2Po2Pneu2 anne_visite foyer if Pent2Po2Pneu2==1
table Pent3Po3Pneu3 anne_visite foyer if Pent3Po3Pneu3==1
table dtcp_15 anne_visite foyer if dtcp_15==1
table dtcp_59 anne_visite foyer if dtcp_59==1
table toux anne_visite foyer if toux==1
table Fievré anne_visite foyer if Fievré==1
table diarrhee anne_visite foyer if diarrhee==1
table Anémie anne_visite foyer if Anémie==1
table Paleur anne_visite foyer if Paleur==1


***** SECTEUR FAN *****

keep if quartier == "FAN"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "FILLE"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "Garçon"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm

*Nombre de session moyenne saisie par enfant suivant les foyers
tabstat nb_session, statistics( mean ) by( foyer) columns(variables)

*** vaccins & maux ****
table rougeole anne_visite foyer if rougeole==1
table BCGPo0HeB anne_visite foyer if BCGPo0HeB==1
table Pent1Po1Pneu1 anne_visite foyer if Pent1Po1Pneu1==1
table Pent2Po2Pneu2 anne_visite foyer if Pent2Po2Pneu2==1
table Pent3Po3Pneu3 anne_visite foyer if Pent3Po3Pneu3==1
table dtcp_15 anne_visite foyer if dtcp_15==1
table dtcp_59 anne_visite foyer if dtcp_59==1
table toux anne_visite foyer if toux==1
table Fievré anne_visite foyer if Fievré==1
table diarrhee anne_visite foyer if diarrhee==1
table Anémie anne_visite foyer if Anémie==1
table Paleur anne_visite foyer if Paleur==1


***** SECTEUR JAR *****

keep if quartier == "JAR"
table foyer anne_visite
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "FILLE"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "Garçon"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm


*Nombre de session moyenne saisie par enfant suivant les foyers
tabstat nb_session, statistics( mean ) by( foyer) columns(variables)

*** vaccins & maux ****
table rougeole anne_visite foyer if rougeole==1
table BCGPo0HeB anne_visite foyer if BCGPo0HeB==1
table Pent1Po1Pneu1 anne_visite foyer if Pent1Po1Pneu1==1
table Pent2Po2Pneu2 anne_visite foyer if Pent2Po2Pneu2==1
table Pent3Po3Pneu3 anne_visite foyer if Pent3Po3Pneu3==1
table dtcp_15 anne_visite foyer if dtcp_15==1
table dtcp_59 anne_visite foyer if dtcp_59==1
table toux anne_visite foyer if toux==1
table Fievré anne_visite foyer if Fievré==1
table diarrhee anne_visite foyer if diarrhee==1
table Anémie anne_visite foyer if Anémie==1
table Paleur anne_visite foyer if Paleur==1


***** SECTEUR KB *****

keep if quartier == "KB"
table foyer anne_visite
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "FILLE"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "Garçon"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm


*Nombre de session moyenne saisie par enfant suivant les foyers
tabstat nb_session, statistics( mean ) by( foyer) columns(variables)

*** vaccins & maux ****
table rougeole anne_visite foyer if rougeole==1
table BCGPo0HeB anne_visite foyer if BCGPo0HeB==1
table Pent1Po1Pneu1 anne_visite foyer if Pent1Po1Pneu1==1
table Pent2Po2Pneu2 anne_visite foyer if Pent2Po2Pneu2==1
table Pent3Po3Pneu3 anne_visite foyer if Pent3Po3Pneu3==1
table dtcp_15 anne_visite foyer if dtcp_15==1
table dtcp_59 anne_visite foyer if dtcp_59==1
table toux anne_visite foyer if toux==1
table Fievré anne_visite foyer if Fievré==1
table diarrhee anne_visite foyer if diarrhee==1
table Anémie anne_visite foyer if Anémie==1
table Paleur anne_visite foyer if Paleur==1

***** SECTEUR MAG*****

keep if quartier == "MAG"
table foyer anne_visite
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "FILLE"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "Garçon"
table   anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm


*Nombre de session moyenne saisie par enfant suivant les foyers
tabstat nb_session, statistics( mean ) by( foyer) columns(variables)

*** vaccins & maux ****
table rougeole anne_visite foyer if rougeole==1
table BCGPo0HeB anne_visite foyer if BCGPo0HeB==1
table Pent1Po1Pneu1 anne_visite foyer if Pent1Po1Pneu1==1
table Pent2Po2Pneu2 anne_visite foyer if Pent2Po2Pneu2==1
table Pent3Po3Pneu3 anne_visite foyer if Pent3Po3Pneu3==1
table dtcp_15 anne_visite foyer if dtcp_15==1
table dtcp_59 anne_visite foyer if dtcp_59==1
table toux anne_visite foyer if toux==1
table Fievré anne_visite foyer if Fievré==1
table diarrhee anne_visite foyer if diarrhee==1
table Anémie anne_visite foyer if Anémie==1
table Paleur anne_visite foyer if Paleur==1

***** SECTEUR MAR*****

keep if quartier == "MAR"
table foyer anne_visite
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "FILLE"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "Garçon"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm


*Nombre de session moyenne saisie par enfant suivant les foyers
tabstat nb_session, statistics( mean ) by( foyer) columns(variables)

*** vaccins & maux ****
table rougeole anne_visite foyer if rougeole==1
table BCGPo0HeB anne_visite foyer if BCGPo0HeB==1
table Pent1Po1Pneu1 anne_visite foyer if Pent1Po1Pneu1==1
table Pent2Po2Pneu2 anne_visite foyer if Pent2Po2Pneu2==1
table Pent3Po3Pneu3 anne_visite foyer if Pent3Po3Pneu3==1
table dtcp_15 anne_visite foyer if dtcp_15==1
table dtcp_59 anne_visite foyer if dtcp_59==1
table toux anne_visite foyer if toux==1
table Fievré anne_visite foyer if Fievré==1
table diarrhee anne_visite foyer if diarrhee==1
table Anémie anne_visite foyer if Anémie==1
table Paleur anne_visite foyer if Paleur==1

***** SECTEUR PLA*****

keep if quartier == "PLA"
table foyer anne_visite
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "FILLE"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "Garçon"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm

*Nombre de session moyenne saisie par enfant suivant les foyers
tabstat nb_session, statistics( mean ) by( foyer) columns(variables)

*** vaccins & maux ****
table rougeole anne_visite foyer if rougeole==1
table BCGPo0HeB anne_visite foyer if BCGPo0HeB==1
table Pent1Po1Pneu1 anne_visite foyer if Pent1Po1Pneu1==1
table Pent2Po2Pneu2 anne_visite foyer if Pent2Po2Pneu2==1
table Pent3Po3Pneu3 anne_visite foyer if Pent3Po3Pneu3==1
table dtcp_15 anne_visite foyer if dtcp_15==1
table dtcp_59 anne_visite foyer if dtcp_59==1
table toux anne_visite foyer if toux==1
table Fievré anne_visite foyer if Fievré==1
table diarrhee anne_visite foyer if diarrhee==1
table Anémie anne_visite foyer if Anémie==1
table Paleur anne_visite foyer if Paleur==1


***** SECTEUR PNU*****

keep if quartier == "PNU"
table foyer anne_visite
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "FILLE"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "Garçon"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm


*Nombre de session moyenne saisie par enfant suivant les foyers
tabstat nb_session, statistics( mean ) by( foyer) columns(variables)

*** vaccins & maux ****
table rougeole anne_visite foyer if rougeole==1
table BCGPo0HeB anne_visite foyer if BCGPo0HeB==1
table Pent1Po1Pneu1 anne_visite foyer if Pent1Po1Pneu1==1
table Pent2Po2Pneu2 anne_visite foyer if Pent2Po2Pneu2==1
table Pent3Po3Pneu3 anne_visite foyer if Pent3Po3Pneu3==1
table dtcp_15 anne_visite foyer if dtcp_15==1
table dtcp_59 anne_visite foyer if dtcp_59==1
table toux anne_visite foyer if toux==1
table Fievré anne_visite foyer if Fievré==1
table diarrhee anne_visite foyer if diarrhee==1
table Anémie anne_visite foyer if Anémie==1
table Paleur anne_visite foyer if Paleur==1


***** SECTEUR RE*****

keep if quartier == "RE"
table foyer anne_visite
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "FILLE"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "Garçon"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm


*Nombre de session moyenne saisie par enfant suivant les foyers
tabstat nb_session, statistics( mean ) by( foyer) columns(variables)

*** vaccins & maux ****
table rougeole anne_visite foyer if rougeole==1
table BCGPo0HeB anne_visite foyer if BCGPo0HeB==1
table Pent1Po1Pneu1 anne_visite foyer if Pent1Po1Pneu1==1
table Pent2Po2Pneu2 anne_visite foyer if Pent2Po2Pneu2==1
table Pent3Po3Pneu3 anne_visite foyer if Pent3Po3Pneu3==1
table dtcp_15 anne_visite foyer if dtcp_15==1
table dtcp_59 anne_visite foyer if dtcp_59==1
table toux anne_visite foyer if toux==1
table Fievré anne_visite foyer if Fievré==1
table diarrhee anne_visite foyer if diarrhee==1
table Anémie anne_visite foyer if Anémie==1
table Paleur anne_visite foyer if Paleur==1

***** SECTEUR RES*****

keep if quartier == "RES"
table foyer anne_visite
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "FILLE"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm
keep if sexe == "Garçon"
table anne_visite, c(mean   Poids_KG mean  Taille_CM mean   IMCkmm)
codebook Poids_KG Taille_CM IMCkmm


*Nombre de session moyenne saisie par enfant suivant les foyers
tabstat nb_session, statistics( mean ) by( foyer) columns(variables)

*** vaccins & maux ****
table rougeole anne_visite foyer if rougeole==1
table BCGPo0HeB anne_visite foyer if BCGPo0HeB==1
table Pent1Po1Pneu1 anne_visite foyer if Pent1Po1Pneu1==1
table Pent2Po2Pneu2 anne_visite foyer if Pent2Po2Pneu2==1
table Pent3Po3Pneu3 anne_visite foyer if Pent3Po3Pneu3==1
table dtcp_15 anne_visite foyer if dtcp_15==1
table dtcp_59 anne_visite foyer if dtcp_59==1
table toux anne_visite foyer if toux==1
table Fievré anne_visite foyer if Fievré==1
table diarrhee anne_visite foyer if diarrhee==1
table Anémie anne_visite foyer if Anémie==1
table Paleur anne_visite foyer if Paleur==1

# Binary Search Tree

- [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] Dizisinin Binary Search Tree Aşamaları

- Root = 7 olarak belirledim.


- Aşama 1

5 sayısı 7 den küçük olduğu için 7 nin soluna ekledik


                                            7
                                          /
                                        5


- Aşama 2

1 sayısı 5 ve 7 den küçük olduğu için 5 in soluna ekledik


                                            7
                                          /  
                                        5
                                      /  
                                    1  

- Aşama 3 

8 sayısı  7 den büyük olduğu için sağına ekledik

                                            7
                                          /   \       
                                        5       8
                                      /
                                    1      

- Aşama 4 

3 sayısı 5 ve 7 den küçük olduğu için 5 in soluna ve 1 in sağına ekledik

                                            7
                                          /   \       
                                        5       8
                                      /
                                    1  
                                      \ 
                                        3

- Aşama 5 

6 sayısı 7 den küçük ve 5 ten büyük olduğu için 7 nin soluna 5 in sağına ekledik

                                            7
                                          /   \       
                                        5       8
                                      /   \
                                    1       6
                                      \
                                        3     

- Aşama 6

0 sayısı 7 , 5 ve 1 den küçük olduğu için 1 in soluna ekledik

                                            7
                                          /   \       
                                        5       8
                                      /   \
                                    1       6
                                  /   \
                                0       3

- Aşama 7

 9 sayısı 7 ve 8 den büyük olduğu için 8 in sağına ekledik

                                            7
                                          /   \       
                                        5       8
                                      /   \       \
                                    1       6       9
                                  /   \
                                0       3

- Aşama 8 

4 sayısı 7 ve 5 ten küçük olduğu için 5 in soluna 1 den ve 3 ten büyük olduğu için 3 ün sağına ekledik

                                            7
                                          /   \       
                                        5       8
                                      /   \       \
                                    1       6       9
                                  /   \
                                0       3
                                          \
                                            4

- Aşama 9

2 sayısı 7 den 5 ten ve 3 ten küçük olduğu için 3 ün soluna ekledik

                                            7
                                          /   \       
                                        5       8
                                      /   \       \
                                    1       6       9
                                  /   \
                                0       3
                                      /   \
                                    2       4

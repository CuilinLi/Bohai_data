# Bohai_data
Data (China_Bohai_CFs_data1....23.dat) are cross-correlation functions (CFs) from the ambient seismic noise of two stations.   
The data file is too big, so we devided it to 23 files.                                                                        
                                                                                                                               
The CF data is like                                                                                                                                                                                                                                         
      39.8      116.6                                                                                                          
      36.4      119.2                                                                                                          
      0.00     0.1169     0.1169                                                                                               
      0.20     0.1247     0.1176                                                                                               
      0.40     0.1389     0.1211                                                                                               
      0.60     0.1502     0.1191                                                                                               
      0.80     0.1482     0.1057                                                                                               
      1.00     0.1306     0.0802                                                                                               
       ...       ...        ...                                                                                                
  with the format                                                                                                              
     Lat(Station_A)  Lon(Station_A)                                                                                            
     Lat(Station_B)  Lon(Station_B)                                                                                            
       Time(t=0)        GAB(t)       GBA(t)                                                                                    
       Time(t=dt)       GAB(t)       GBA(t)                                                                                    
       Time(t=2dt)      GAB(t)       GBA(t)                                                                                    
          ...            ...          ...                                                                                      
GAB(t) is the CF from source A to station B while GBA(t) is from source B to station A.                                        

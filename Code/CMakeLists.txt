
ADD_EXECUTABLE( t1sim t1sim.cxx )
TARGET_LINK_LIBRARIES ( t1sim 
vul 
ITKAlgorithms 
ITKBasicFilters 
ITKCommon
ITKIO)

# *=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=* 
# ** Copyright UCAR (c) 1990 - 2016                                         
# ** University Corporation for Atmospheric Research (UCAR)                 
# ** National Center for Atmospheric Research (NCAR)                        
# ** Boulder, Colorado, USA                                                 
# ** BSD licence applies - redistribution and use in source and binary      
# ** forms, with or without modification, are permitted provided that       
# ** the following conditions are met:                                      
# ** 1) If the software is modified to produce derivative works,            
# ** such modified software should be clearly marked, so as not             
# ** to confuse it with the version available from UCAR.                    
# ** 2) Redistributions of source code must retain the above copyright      
# ** notice, this list of conditions and the following disclaimer.          
# ** 3) Redistributions in binary form must reproduce the above copyright   
# ** notice, this list of conditions and the following disclaimer in the    
# ** documentation and/or other materials provided with the distribution.   
# ** 4) Neither the name of UCAR nor the names of its contributors,         
# ** if any, may be used to endorse or promote products derived from        
# ** this software without specific prior written permission.               
# ** DISCLAIMER: THIS SOFTWARE IS PROVIDED "AS IS" AND WITHOUT ANY EXPRESS  
# ** OR IMPLIED WARRANTIES, INCLUDING, WITHOUT LIMITATION, THE IMPLIED      
# ** WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE.    
# *=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=* 
###########################################################################
#
# Makefile for PrintTitanServer
#
# Mike Dixon, RAP, NCAR, Boulder, CO, 80307, USA
#
# Feb 2001
#
###########################################################################

include $(RAP_MAKE_INC_DIR)/rap_make_macros

TARGET_FILE = PrintTitanServerXML

LOC_INCLUDES =  -I$(RAP_INC_DIR)/../libs/apiTitan/src/include
LOC_CFLAGS =
LOC_LDFLAGS =
#LOC_LIBS = -ltitan -ldsserver -lrapformats -ldidss -ltoolsa -ldataport -lm -lpthread
LOC_LIBS = \
	-lapiTitan -lz -lpthread -lm

HDRS = \
	Args.hh \
	PrintTitanServerXML.hh

CPPC_SRCS = \
	Args.cc \
	PrintTitanServerXML.cc \
	Main.cc

#
# standard C++ targets
#

include $(RAP_MAKE_INC_DIR)/rap_make_c++_targets

#
# local targets
#

# DO NOT DELETE THIS LINE -- make depend depends on it.



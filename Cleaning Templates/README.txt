CODE SNIPPET TEMPLATE: 

def descriptive_name(df, cols, x, y): 
    '''
    AIM    -> What the function does (50 char or less)
     
    INPUT  -> List, Dictionary, etc, params
    
    OUTPUT -> What function gives back (50 char or less)  
    ------
    '''
#code snippet here


EXAMPLE:

def change_dtypes(col_int, col_float, df): 
    '''
    AIM    -> Changing dtypes to save memory
     
    INPUT  -> List of column names (int, float), df
    
    OUTPUT -> updated df with smaller memory  
    ------
    '''
    df[col_int] = df[col_int].astype('int32')
    df[col_float] = df[col_float].astype('float32')


**********************************************************
NOTES:

[] Structure by types? (dealing with nulls, filling rows, etc)
[] Structure by scenario? (Classification/Regression)
[] Link to notebooks from assignments or templates you understand that answer problem
[] Link to resources when troubleshooting. 
[] Update regularly

Source:https://towardsdatascience.com/my-compilation-of-simple-yet-practical-data-cleaning-codes-d692ec20dca8
https://www.admondlee.com/

https://www.dezyre.com/article/data-cleaning-in-python/406


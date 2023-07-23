# Jp_nout_3
Кирилл, не могу понять, где у меня ошибка в задаче 1.2. - там, где надо было поставить ноль в delta_renovated.
Я ее сделал в конце концов через сортировку и конкатенацию, но понимаю, что это не лучший вариант. 
Пытался сделать через функцию:
def delt(x):
    if x < 0:
       delt == 0
    else:
        delt == x 
    return delt
df['delta_renovated'] = df['delta_renovated'].apply(delt)
df['delta_renovated']
но получается ответ: 
0        <function delta at 0x0000021717E50B80>
1        <function delta at 0x0000021717E50B80>
2        <function delta at 0x0000021717E50B80>
3        <function delta at 0x0000021717E50B80>
4        <function delta at 0x0000021717E50B80>
                          ...                  
21608    <function delta at 0x0000021717E50B80>
21609    <function delta at 0x0000021717E50B80>
21610    <function delta at 0x0000021717E50B80>
21611    <function delta at 0x0000021717E50B80>
21612    <function delta at 0x0000021717E50B80>
Name: delta_renovated, Length: 21613, dtype: object
Помогите понять, где ошибка, пожалуйста!

---
{"dg-publish":true,"permalink":"/datura-object/","tags":["Datura/COTLAB"],"noteIcon":""}
---


数据类型

```C
enum datatype// for Nesnode.iden, all entity
{
	//dt_any,
	dt_func = 0x10,

	dt_int,// ChrAr ptrdiff_t
	dt_float = tok_number,// CdeAr double

	dt_num = dt_int + 2,// NumAr _Complex
	dt_posi,// NumAr 4D-vector

	dt_str = tok_string,// ustring
	dt_astr = dt_posi + 2,// wstring
	dt_u8str,// u8string

	// TenAr:
	dt_vector,// V[]
	dt_readonly,// Ro[] Tuple in Python
	dt_comb,// [] List in Python. (type of combination can be different)
	dt_ary,// dt_x[]
	dtx_dictionary,// from Python
	dt_tensor,// T[] ten* > vector
	dt_matrix,// M[], will by MtrAr

	dt_rangei,// [ ~ ] (by HrnAr x and t, t as summit)
	dt_rangec,// 0( , ) 3[ , ] 2[ , ) 1( , ] (by HrnAr x, y and t, t as type)

	dt_bool
};
```


Example for `e`:
- `e` identifier
- `1e` float 1.0
- `e1` identifier
- `1e1` float 10.0

Constant
- 自然常数 `e`
- 圆周率 `pi`

Example
- 复数 `1+2j`


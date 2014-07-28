lua_json-c
==========

json-c lua库.
你可以在lua中使用json-c,像下面这样.
local json = require "json-c"

json.decode( s )
	s是一个字符串,该函数返回一个表.
json.encode( t )
	t是一个表,函数返回一个json字符串.


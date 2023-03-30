json - an opinionated json module for erlang
=============================================

This is how I parse my json in elang YMMV.

To build I use https://github.com/cthulhuology/beamer

	beamer make

To generate a JSON document:


	json:encode([ { <<"foo">>, <<"bar">>}, {<<"narf">>, 123 }, { <<"blat">>, [ 1,-1,2,-2,3]}]).

To parse a JSON document

	json:parse(<<"{\"foo\":\"bar\",\"narf\":123,\"blat\":[1,-1,2,-2,3]}">>).


	



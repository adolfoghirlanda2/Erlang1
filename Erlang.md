-module(hello).
-export([greet/0]).

greet() ->
    io:format("Hello, World!~n").

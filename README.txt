# ruby_me


ruby
using ruby 3way
irb
documentation
object
variable (not object)
integer
float
string
array  (to_s, join, split, sort, uniq, delete_at,delete, push, pop,shift,unshift,clear )
hash(size, to_a, clear, invert)
symbols
booleans (between, empty?, nil?, include?, has_key?,  has_value?)
ranges ( Inclusive 1..10 ,Exclusive 1…10 , begin, end, *splat oparator) 
constants

17.if elsif , unless else, ternary operator
loop ,( break ,next, redo ,retry) ,  while , until, 
iterators ->
integer/floats:  upto, downto, times, step
range: each, step
string: each , each_line, each_byte
array: each, each_index, each_with_index
hash: each, each_key, each_value, 

code blocks: common methods that use blocks
find, merge, collect, sort, inject
find: find, find_all/select, any?, all?, delete_if
merge:  h1.merge(h2) {|key, old, new| old }
collect/map: array.collect { |a| a * 2 } [map/collect always return array ]
hash.collect { |k,v|  v*2}  /  hash.map {|k,v| “#{k}: #{v * 20}”}
sort: array.sort {|v1,v2|  v1<=> v2 }  /  array.sort_by {|v1|  v1.size }
hash.sort {|item1 , item2| item[0] <=> item[0] } / hash.sort {|item1 , item2| item[1] <=> item[1] }  [like array index]
inject: Accumulator 
sum = array.inject(100) { |memo, n|  memo + n }

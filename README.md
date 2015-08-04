Swift 2 筆記

1. do-while 現在變成 repeat-while

    var i = 0
    repeat {
        i++
        print(i)
    } while i < 10

 2. for-in where 子句

 	let numbers = [20, 18, 39, 49, 68, 230, 499, 238, 239, 723, 332]
	
	for number in numbers where number > 100 {
	    print(number)
	}

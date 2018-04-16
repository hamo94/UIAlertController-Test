# 후행 클로져 예

import UIKit

var numbers = [20, 10, 5, 32, 6]

let mappedNumbers:[Int] = numbers.map({(a:Int) -> Int in

    return a + 1
    
})

var numbers2 = [20, 10, 5, 32, 6]

let mappedNumbers2:[Int] = numbers2.map {

    (a: Int) -> Int in
    
    return a + 1
    
}

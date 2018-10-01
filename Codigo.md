import UIKit
var numeros = 1...100
for numeros in 0...100 {
    
    switch numeros {
    case 5,10,15,20,25,30,35,40,45,50,55,60,65,70,75,80,85,90,95,100:
        print(numeros,"Bingo!!!")
        if numeros<=40 && numeros>=30 {
            print(numeros,"VivaSwift!!!")
        }else{
        }
    default:
        print(numeros,"No divisible entre 5")
        if numeros<=40 && numeros>=30 {
            print(numeros,"VivaSwift!!!")
        }else{
        }
    }
    switch numeros {
    case 2,4,6,8,12,14,16,18,22,24,26,28,32,34,36,38,42,44,46,48,52,54,56,58,62,64,66,68,72,74,76,78,82,84,86,88,92,94,96,98:
        print(numeros,"Par!!!")
        if numeros<=40 && numeros>=30 {
            print(numeros,"VivaSwift!!!")
        }else{
        }
    default:
       print(numeros,"Impar!!!")
       if numeros<=40 && numeros>=30 {
        print(numeros,"VivaSwift!!!")
       }else{
        }
    }
}

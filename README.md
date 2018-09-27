# ReversingString
Reversing a string using swift


class ReverseAString {
  func reverseString(_ stringYouWantToReverse: String) -> String {
    
    let characterArray = Array(stringYouWantToReverse)
    var newString = [Character]()
    for character in (0..<(characterArray.count)).reversed() {
      newString.append(characterArray[character])
    }
    
    return String(newString)
  }
}

print(ReverseAString().reverseString("Raja Poreddy"))

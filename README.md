
# Assignments

# Fibnocci Series in scala or while loop
object FibnocciSeries {
  def fib2( n : Int ) : Unit = {
    var a = 0
    var b = 1
    var i = 0
    while( i < n ) {
      val c = a + b
       print("  " + a + "  ")
      a = b
      b = c
      i = i + 1
    }
    println(a)
  }
  def main(args: Array[String]): Unit = {
    fib2(10)
  }
}

# Output
0    1    1    2    3    5    8    13    21    34  55

# Multiplication table in scala or for loop
object MultiplicationTable {
  def multab(tblnum: Int) = {
    var tab = 0
    for (i <-(1 to 10))
    { tab += tblnum
      println(tblnum + "*" + i +"=" +tab)
    }
  }

  def main(args: Array[String]): Unit = {
    multab(5)
  }

}

# Output
5*1=5
5*2=10
5*3=15
5*4=20
5*5=25
5*6=30
5*7=35
5*8=40
5*9=45
5*10=50

# Check whether number is palindrome or not in scala or if else loop.
object palindromeHW {
  def isPalindrome(n:Int): Unit = {
    if(n.toString.reverse == n.toString)
      println("Palindrome")
    else
      println("Not a palindrome")
  }

  def main(args: Array[String]): Unit = {
    isPalindrome(2435)
  }

}

# Output
Not a palindrome

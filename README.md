
# Assignments

# Fibnocci Series in scala
object FibnocciSeries {
  def fib2( n : Int ) : Unit = {
    var a = 0
    var b = 1
    var i = 0
    while( i < n ) {
      val c = a + b
      println(a)
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
